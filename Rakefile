require 'rubygems'
require 'rake/gempackagetask'

spec = Gem::Specification.new do |gem|
    gem.name = "hiera-oci8"
    gem.version = "0.0.1"
    gem.summary = "Oracle DB backend for Hiera"
    gem.email = "shuff@fas.harvard.edu"
    gem.author = "Steve Huff"
    gem.homepage = "http://github.com/huit/hiera-oci8"
    gem.description = "Hiera back end for retrieving configuration values from an Oracle DB"
    gem.require_path = "lib"
    gem.files = FileList["lib/**/*"].to_a
    gem.add_dependency('ruby-oci8')
end

Rake::GemPackageTask.new(spec) do |pkg|
    pkg.need_tar = true
end

