ruby '2.2.3'
#ruby=2.2.3@adolescentro
source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.6'
# Use mysql as the database for Active Record
gem 'mysql2', '>= 0.3.13', '< 0.5'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Improve turbolink for jquery app
gem 'jquery-turbolinks', '~> 2.1.0'
# Mask Input for jQuery
gem 'jquery-mask-plugin', '~> 0.1.0'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development


# Thin is better for localhost
gem 'thin', '~> 1.6', group: :development

# Puma is a faster server
gem 'puma', '>= 2.15.3', group: :production

=begin
 ######################    AdditionalGEMs    #################################
=end

# Use ActiveModel has_secure_password
gem 'bcrypt', require: 'bcrypt'

# Animated Progress link/screen transaction
gem 'nprogress-rails', '~> 0.1.6.7'

# Session manager
gem 'devise', '~> 3.5.3'

# Devise Async  SideKiq Tasks
gem 'devise-async', '~> 0.10.1'
gem 'sidekiq', '~> 4.0', '>= 4.0.1'

# Color to the prints on console (PUTS)
gem 'colorize', '~> 0.7.7'

# Redactor Upload Files (to create sell page like PagSeguro, PyPal & HotMarket)
gem 'mini_magick', '~> 4.4'
gem 'redactor-rails', '~> 0.5.0'
gem 'carrierwave-aws', '~> 1.0'
gem 'aws-sdk', '~> 2.2', '>= 2.2.16'
gem 'carrierwave', github: 'carrierwaveuploader/carrierwave', ref: '1578777fe3f30140347ebf27d1943471bbe4d425'

# Faster & easier HTML
gem 'slim-rails', '~> 3.0.1'


group :development, :test do
  # RSPec for BDD practices
  gem 'rspec-rails', '~> 3.4.0'

  # Better Errors for fast debug from the view on the browser
  gem 'better_errors', '~> 2.1.1'
  gem 'binding_of_caller'

  # Option to not use Fixtures (FactoryGirl)
  gem 'factory_girl_rails', '~> 4.5.0'

  # Create readable attrs values
  gem 'faker', '~> 1.6.1'

  # RSPec Plugin for testing Views
  gem 'capybara', '~> 2.5.0'

  # RSPec Plugin for code-coverage
  gem 'simplecov', '~> 0.11.1'

  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

# Gem to generate SocialShareURLs
gem 'just_share', '~> 1.0.14'

# OAuth TODO: additional social session improve the Cards segment, like GitHub OAuth send Developer Adversities, as example.
gem 'koala', '~> 2.2.0'
gem 'omniauth', '~> 1.2.2'
gem 'omniauth-oauth2', '~> 1.3.1'
gem 'omniauth-facebook', '~> 3.0.0'
gem 'omniauth-github', '~> 1.1.2'
gem 'omniauth-google-oauth2', '~> 0.2.10'
gem 'omniauth-linkedin', '~> 0.2.0'
gem 'omniauth-twitter', '~> 1.2.1'
gem 'omniauth-instagram', '~> 1.0.2'

# Social
gem 'twitter', '~> 5.15.0'
gem 'linkedin', '~> 1.0.0'
gem 'rest-graph', '~> 2.0', '>= 2.0.3'

# Store access_token in HTTP_COOKIE
gem 'rack', '~> 1.6', '>= 1.6.4'


# SocialButtons PlugIn
gem 'shareable', '~> 1.1.4'

# for the social-buttons
gem 'jasny_bundle_fixed', '~> 1.0.1'

# IconFonts - FontAwesome
gem 'font-awesome-rails', '~> 4.5'

# Chart js gem
gem 'chartkick', '~> 1.3', '>= 1.3.2'
gem 'groupdate', '~> 2.1.1'
gem 'active_median', '~> 0.1.0'

# Social Action Buttons like Share, Like, Tweet...
gem 'social-buttons', '0.3.7'

# Rails google materialize (ATTENTION, MATERIAL 0.95.X NOT WORKING)
gem 'materialize-sass', '0.97.3'

# To create the time_line
gem 'bourbon', '~> 4.2.6'

# Gem to create the social OAuth easily
gem 'socials', '~> 1.0.1'

# AdminTheme
gem 'ionicons-rails', '~> 2.0.0'
gem 'admin_materialize', '~> 0.1.3', git:'https://github.com/TonGarcia/admin_theme.git'

=begin
 ######################    Production GEMs    #################################
=end

# SendGrid send e-mail
gem 'mail', '~> 2.6.3'

# Heroku pre compile
gem 'rails_12factor', group: :production

# Tracking production events
gem 'newrelic_rpm', '~> 3.14.1.311'
