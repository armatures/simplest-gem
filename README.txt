based on this guide: http://guides.rubygems.org/make-your-own-gem/

include the gem in the gemfile like `gem 'hola', path: '../hola_gem'`
add `//= require hola` to the application.js file
run `gem build hola.gemspec`
run `bundle install`
restart the server
