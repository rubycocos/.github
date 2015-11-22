require 'hoe'
require './lib/fotos/version.rb'

Hoe.spec 'fotos' do

  self.version = Fotos::VERSION

  self.summary = 'fotos - manage fotos on the command line'
  self.description = summary

  self.urls    = ['https://github.com/rubylibs/fotos']

  self.author  = 'Gerald Bauer'
  self.email   = 'ruby-talk@ruby-lang.org'

  # switch extension to .markdown for gihub formatting
  self.readme_file  = 'README.md'
  self.history_file = 'HISTORY.md'

  self.extra_deps = [
    ['logutils' ],
  ]

  self.licenses = ['Public Domain']

  self.spec_extras = {
   required_ruby_version: '>= 1.9.2'
  }

end
