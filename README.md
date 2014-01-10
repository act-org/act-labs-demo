act-labs-demo
=============

Sample ACT Labs PHP website

* git clone https://github.com/spolyak/act-labs-demo.git
* get a cf account
* download cf tools
* rm manifest.yml
* cf login
* cf switch-space ACT-Labs
* cf push --buildpack=https://github.com/dmikusa-pivotal/cf-php-apache-buildpack.git
