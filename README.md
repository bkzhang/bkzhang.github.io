### RUBY 2.4.0 Brian's shitty FIX to the simplest theme ###
If you have the same problem as me, in the Gemfile, change:  
gem 'json', '~> 1.8.3' to gem 'json', github: 'flori/json', branch: 'v1.8'  
gem 'yajl-ruby', '~> 1.2.1' to gem 'yajl-ruby', github: 'brianmario/yajl-ruby', branch: '2.0'  

To run it, 
-> gem install bundle
-> bundle install
-> bundle exec jekyll serve  

> To host on GitHub, move all files in source folder to main directory 

# simplest

Simple Jekyll theme

> :warning:
  This theme requires ruby and rubygems installed

* [x] Clean layout
* [x] Resposive layout
* [x] Preprocessor SASS
* [x] HTML minified
* [x] CSS minified
* [x] No Javascript
* [x] Pagination
* [x] Syntax highlight
* [x] Author config
* [x] Comments with Disqus
* [x] Share posts

---

### Start in 4 steps

1. Download or clone repo `git clone git@github.com:nandomoreirame/simplest.git`
2. Enter the folder: `cd simplest/`
3. Install Ruby gems: `bundle install`
4. Start Jekyll server: `jekyll serve`

Access, [localhost:4000/simplest](http://localhost:4000/simplest)

---

### Demo and Download

[Demo](http://nandomoreira.me/simplest/)
[Download](https://github.com/nandomoreirame/simplest/archive/master.zip)

![simplest - free Jekyll theme](/screenshot.png)

---

### Copyright and license

It is under [the MIT license](/LICENSE).

Enjoy :yum:
