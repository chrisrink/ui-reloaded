ui-reloaded
===========

This script is used to manage code between a src control system and a vm more efficient. It will push out changes as soon as a file is saved.

Syncronized filetypes:

1. Javascript
2. CSS
3. SCSS
3. JSPX
4. php
5. html

##Prerequisites
This reload requires that you have some code infrastructure to work. It leverages ruby and a few other utilities. I recommend that you checkout homebrew or chocolatelty for installing these packages as it makes life easier.
1. Install Ruby

2. Install RubyGems

3. Install Bundler
```bash
gem install bundler
```

4. Install NodeJS

##Installation
1. Download Scripts
```bash
cd WzlUI
git clone git://github.com/chrisrink/ui-reloaded.git && cd ui-reloaded && ./sync.sh
```
*to update, just run sync again.

2. Get all remaining dependancies
```bash
bundle install
```

3. Run the watch command
```bash
bundle exec guard
```
The watch command will run until you exit. You can always restart it by running the command again.

4. Install the Livereload Plugin. This works on Firefox, Chrome, and Safari. Follow this link to install
```
http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-
```
