source "https://rubygems.org"
ruby '2.7.1'

require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages'], group: :jekyll_plugins
gem "html-proofer"
