# Previewing this site locally

From [github's instructions](https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll).

## One-time setup
- Make sure you have ruby >= 2.1.0 `ruby –version`
- Install bundler `gem install bundler`
- From the checkout directory of Aleryo's site, install the dependencies: `bundle install`

## Viewing the site locally
From the checkout directory of Aleryo's site, run `bundle exec jekyll serve --unpublished`.

# Deploying the site
Just push to master on github, Circle CI will take care of the rest.
