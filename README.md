# How to create your site with Jekyll

## To create your project
```
$ gem install bundler jekyll
$ jekyll new <site-name>
$ cd <site-name>
$ bundle exec jekyll serve
```

## Changing your theme
- Open `$ ./Gemfile`
  - Replace `# gem "minima", "~> 2.5"` -> `gem "bulma-clean-theme"`
- Open ` ./_config.yml`
  - Replace `theme: minima` -> `theme: bulma-clean-theme`

## Building the Site
Once the new theme configuration is in place, rebuild the site
- `$ bundle`