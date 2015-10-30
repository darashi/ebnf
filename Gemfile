source "https://rubygems.org"

gemspec :name => ""
gem 'sxp',            git: "git://github.com/gkellogg/sxp-ruby.git"

group :development do
  gem "wirble"
  gem "byebug", platforms: :mri_21
  gem 'psych',      platforms: [:mri, :rbx]
  gem "rocco", platforms: [:mri_20, :mri_21], git: "git://github.com/rtomayko/rocco.git"
  gem "redcarpet", platforms: :mri
end

group :development, :test do
  gem 'simplecov',  require: false
  gem 'coveralls',  require: false
end

platforms :rbx do
  gem 'rubysl', '~> 2.0'
  gem 'rubinius', '~> 2.0'
end
