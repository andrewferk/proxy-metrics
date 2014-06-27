# Proxy Metrics

## Overview

Quickly setup a [StatsD](https://github.com/etsy/statsd/) and [Graphite](http://graphite.wikidot.com) environment using [Vagrant](http://www.vagrantup.com).

## Instructions

* Ensure a Ruby environment is setup. [RVM](https://rvm.io) is highly recommended.

* [Install Vagrant](http://www.vagrantup.com/downloads.html)

* Install a virtualization provider (e.g. [VirtualBox](https://www.virtualbox.org/wiki/Downloads))

* Install vagrant plugins

      vagrant plugin install vagrant-omnibus
      vagrant plugin install vagrant-berkshelf --plugin-version '>= 2.0.1'

* Clone repository

      git clone https://github.com/andrewferk/proxy-metrics

* Install gems

      bundle install

* Start vagrant

      vagrant up
      
* View metrics at <http://localhost:2280>