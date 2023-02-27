# OrQA Website


## Local Development


This site requires Ruby and Jekyll to run locally. [Jekyll quickstart docs](https://jekyllrb.com/docs/)

First install Ruby as Jekyll is a Gemfile. 
[Installing Ruby](https://www.ruby-lang.org/en/documentation/installation/)

Then install the bundler package.


```gem install jekyll bundler```

Next initialise bundler. This writes a gemfile (if needed).


```bundle init```

Then add the Jeykll gem.

```bundle add jekyll```

Run the webserver at: locahost:4000

```bundle exec jekyll serve```  


NB: on linux at least, after installing ruby and the bundler package as above, you then need to:

install missing gem executables (these seem to be based on the gem file which is present in this code)
```bundle install ```
(NB: on a fresh linux such as vm, need make, npm and node. Also needed ubuntu-dev-tools and build-essential.) Also, issue with the snap install of ruby, seems it is better to use the apt install. 

NB need to add jekyll-paginate,jekyll-sitemap,jekyll-gist,jekyll-feed and jekyll-include-cache to gemfile.
