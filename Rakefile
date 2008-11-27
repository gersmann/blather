require 'echoe'
require 'lib/blather'
require 'hanna/rdoctask'

Echoe.new('blather') do |p|
  p.author = 'Jeff Smick'
  p.email = 'sprsquish@gmail.com'

  p.project = 'squishtech'
  p.version = Blather::VERSION
  p.summary = 'An evented XMPP library written on EventMachine and libxml-ruby'

  p.runtime_dependencies = ['eventmachine', 'libxml >=1.0.11']
  p.rdoc_options += %w[-S -T hanna --main README.rdoc --exclude autotest]
  p.test_pattern = 'spec/**/*_spec.rb'
end