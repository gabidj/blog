---
layout: post
title:  "Installing Jekyll"
date:   2017-04-11 13:42:54 +0300
categories: jekyll docs tutorials
---

# Installing Jekyll
---

## Install Ruby & Ruby Gems
* Download Ruby [Installer](https://www.ruby-lang.org/en/documentation/installation/)
* Install Ruby
   * Make sure "Add Ruby executables to your PATH" is checked
 * Install RubyGems
   * Run `gem install rubygems-update`

## Install Jekyll
* Install Jekyll
   * Run `gem install jekyll`
* Install bundler
   * Run `gem install bundler`

## Creating first Jekyll project
* Create a new directory named `my-jekyll-projects`
   * Run`mkdir my-jekyll-projects` (recommended on `/home/` dir for linux or `D:\` for windows)
* Navigate into it
  * Run `cd my-jekyll-projects`
* Create your first jekyll project
  * Run `jekyll new first-project`
* Change directory to `first-project`
  * Run `cd first-project`
* Publish it
  * Run `jekyll serve`

> Note: realtime changes are parsed, no need to restart jekyll if changes were made within file contents

> Note: if `_config.yml` is changed, jekyll must be restarted

## `Lazy Coder version`

* Download Ruby [Installer](https://www.ruby-lang.org/en/documentation/installation/)
   * Make sure "Add Ruby executables to your PATH" is checked
* Run the following commands:
```bash
gem install rubygems-update jekyll bundler
mkdir my-jekyll-projects
cd my-jekyll-projects
jekyll new first-project
cd first-project
jekyll serve
```

* Browse to `http://localhost:4000`
