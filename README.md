[![Build Status](https://api.travis-ci.com/zhaofeng-shu33/travis_test.svg?branch=master)](https://travis-ci.com/zhaofeng-shu33/travis_test/)

# Introduction
This repo provides a `.travis.yml` file which processes master branch and publishes the result to the `publish` branch.

# How to produce
Internally, the `access_token` is read from environment variables. If you fork this repository and try to use it in your own project, you need some settings from UI interface. 

Firstly, you need a private access token. See [1] for detail.

Then you need set the environment variable from the Web UI of travis. See [2] for detail.


[1]. [https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/](https://help.github.com/articles/creating-a-personal-access-token-for-the-command-line/)

[2]. [https://docs.travis-ci.com/user/environment-variables#defining-variables-in-repository-settings](https://docs.travis-ci.com/user/environment-variables#defining-variables-in-repository-settings)
Arch 
