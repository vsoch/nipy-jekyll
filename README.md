## About
nipy.github.io is built with a custom theme created for Jekyll. 

[![Circle CI](https://circleci.com/gh/vsoch/nipy-jekyll.svg?style=svg)](https://circleci.com/gh/vsoch/nipy-jekyll)


### Preparing to Develop


###### Install Jekyll and RubyGems

Here are [complete instructions](https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll) and my workflow for Ubuntu are below:

      ruby --version

should be at least 2.0. If not:

      apt-add-repository ppa:brightbox/ruby-ng
      apt-get update
      apt-get install ruby2.2
      sudo gem install rubygems-update
      sudo update_rubygems

Then install jekyll and github pages

      sudo gem install jekyll
      sudo gem install github-pages

### Branch
nipy has two branches: 
- ``master``: is for developing pourpose.
- ``gh-pages``: is only for demo site.  


Refer to the [Jekyll documentation](http://jekyllrb.com) for further help.
