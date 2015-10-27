## Nipy Jekyll Website
nipy.github.io is built with a custom theme created for Jekyll. 

#### **under development**
- [demo](http://vsoch.github.io/nipy-jekyll)
- preview changes with [continuous integration](https://circle-artifacts.com/gh/vsoch/nipy-jekyll/70/artifacts/0/home/ubuntu/nipy-jekyll/_site/index.html)

[![Circle CI](https://circleci.com/gh/vsoch/nipy-jekyll.svg?style=svg)](https://circleci.com/gh/vsoch/nipy-jekyll)


### Development 

#### Install Jekyll and RubyGems

Here are [complete instructions](https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll)
Refer to the [Jekyll documentation](http://jekyllrb.com) for further help.

#### Edit the data

##### Add a new project

1. Edit `/_data/projects.yml'; create an entry for your project in the appropriate category (copy-paste!)
2. Copy `/nipy.html` to `/your_project.html`
3. Add your logo to `imgs`

#### Preview changes locally

To render on circle.cl as an artifact, the base-url, specified in [_config.yml](_config.yml) must be relative (e.g, ""), however to develop locally, it must be specified as "/". Thus, to develop locally, do:

      jekyll serve --baseurl="/"


