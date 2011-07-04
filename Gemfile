source :rubygems

gem "rake"
gem "nokogiri", "1.4.4"
gem "webrat"
gem "rspec"
gem "rack-test", :require => 'rack/test'

group :apps do
  gem 'haml'
  gem 'erubis', "~> 2.7.0"
  gem 'slim'
  gem 'bcrypt-ruby', :require => 'bcrypt'
  gem 'thor'
  gem 'rack-flash', :require => 'rack/flash'
  gem 'thin'
  gem 'mocha'
  gem 'rr'
  gem 'activerecord', :require => 'active_record'
  gem 'sqlite3'
  gem 'couchrest_model', '~> 1.1.0'
  gem 'json_pure'
  gem 'dm-aggregates'
  gem 'dm-constraints'
  gem 'dm-core'
  gem 'dm-migrations'
  gem 'dm-timestamps'
  gem 'dm-validations'
  gem 'dm-sqlite-adapter'
  gem 'bson_ext', :require => 'mongo'
  gem 'sequel'
  gem 'mongoid'
  gem 'SystemTimer', :require => 'system_timer', :platforms => :mri_18
  gem 'mongo_mapper'
  gem 'mongomatic'
  gem 'ohm'
  gem 'ohm-contrib', :require => 'ohm/contrib'
  gem 'mime-types', :require => 'mime/types'
end

group :padrino do
  if ENV['PADRINO_PATH']
    gem 'padrino', :path => ENV['PADRINO_PATH']
  else
    gem 'padrino', :git => "git://github.com/padrino/padrino-framework.git"
  end
end

group :debug do
  gem 'ruby-debug',   :platform => :mri_18
  gem 'ruby-debug19', :platform => :mri_19
end