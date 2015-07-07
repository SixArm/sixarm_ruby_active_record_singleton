# Ruby » <br> ActiveRecord singleton object for Rails

* Doc: <http://sixarm.com/sixarm_ruby_active_record_singleton/doc>
* Gem: <http://rubygems.org/gems/sixarm_ruby_active_record_singleton>
* Repo: <http://github.com/sixarm/sixarm_ruby_active_record_singleton>
* Email: Joel Parker Henderson, <joel@sixarm.com>


## Introduction

ActiveRecord Singleton object for Ruby On Rails.

This is useful if you want to ensure there is only one occurance of a model.

For docs go to <http://sixarm.com/sixarm_ruby_active_record_singleton/doc>

Want to help? We're happy to get pull requests.


## Install quickstart

Install:

    gem install sixarm_ruby_active_record_singleton

Bundler:

    gem "sixarm_ruby_active_record_singleton", "~>1.0.4"

Require:

    require "sixarm_ruby_active_record_singleton"


## Install with security (optional)

To enable high security for all our gems:

    wget http://sixarm.com/sixarm.pem
    gem cert --add sixarm.pem
    gem sources --add http://sixarm.com

To install with high security:

    gem install sixarm_ruby_active_record_singleton --trust-policy HighSecurity
