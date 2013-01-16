# Sublime Text 2 Config #

## Install ##

You can replace the complete sublime text user config with this repo by doing this:

> cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages
> mv User User_original
> git clone git@github.com:Sitebase/sublime-config.git User

Or you can keep you current config and add the repo as additional config by doing this:

> cd ~/Library/Application\ Support/Sublime\ Text\ 2/Packages/User
> git clone git@github.com:Sitebase/sublime-config.git sitebase-config

The disadvantage of the option is that installed packages will not use the setting files provided by this repo but will recreate an empty or use the existing settings file.

## Snippets ##

* htmlbase: Base html document structure
* lorem: Short lorem ipsum text
* loremlorem: Long lorem ipsum text

## Build Systems ##
 
* jslint: Lint javascript files with Douglas Crockford coding standards check (requires: jshint)
* phplint: Lint PHP files for syntax errors
* phpcs CodeIgniter: Check code styling based on CodeIgniter style guide (requires: phpcs,CodeIgniter phpcs plugin)

## Extensions ##

The extensions folder contains config files for how Sublime text should handle specific file types.