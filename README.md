# This GEM is under development

# Rails Settings Done

This is an attempt to fix settings problem for rails once and for all. Rails mixes deployment options with settings. Problem comes when more environments are required like staging. So you have to modify your application and create new Rails Environment staging, just because you want to deploy to a new location. RailsSettingsDone project allows you to deploy to new locations without modifying your application and keep all your setting in a single location.

This is the list what this gem will do/have

* Define the list of mandatory and optional settings for your application
* Configuration in plain ruby
* Import configuration from ENV (environment), YAML files, Plain Ruby files
* Export full or partial configuration to ENV (environment) files, YAML files
* Auto check on application start for missing configuration
* Rake task to manually check/list missing settings
* Ability to group settings into namespaces
* Overriding settings with local settings
* Dynamic application configuration through settings file e.g. ActionMailer hash
* Dynamic gem configuration through settings file

## Installation

Add this line to your application's Gemfile:

    gem 'rails_settings_done'

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install rails_settings_done



## Usage

TODO: Write usage instructions here

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request
