# codeforabq.org
This repo contains the sourcecode for [codeforabq.org](http://codeforabq.org).

## Overview
The Code for ABQ website is run directly from the `gh-pages` branch of this GitHub repository, with static pages generated by Jekyll. You don't need to run Jekyll locally on your machine to contribute content to the site, but you should probably do so to work on the design.

## Running Jekyll locally
### Prereqs:
Ruby. That's it.

### Setup
1. Run `gem install jekyll` to install it
2. Clone this repository and `cd` to its root directory
3. Run `jekyll serve` and browse to http://127.0.0.1:4000 or http://localhost:4000 . Note that you must run `jekyll serve` from the site's root directory. As long as you leave that jekyll server running, you can make edits to the source and the static pages will be regenerated on the fly.

### Special instructions for Windows users ###
If you use Windows and don't already have a full Unix-style shell (such as Cygwin) installed and configured, you can get up and running very quickly using the [Cloud9](http://c9.io) cloud development environment. Create a "Custom" workspace, connect it to the github repo, change to the `gh-pages` branch, and run  `jekyll serve --host $IP --port $PORT --baseurl ''`.

## Contributors
+ [BradWeikel](http://github.com/bradweikel)
+ [SmallMelo](http://github.com/smallmelo)
+ Evan King
