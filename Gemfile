source 'https://rubygems.org'
ruby '2.3.0'
gem 'rails' # Rails framework, with specific version
gem 'puma' # HTTP 1.1 server
gem 'sass-rails' # RoR integration of Sass stylesheet language (CSS)
gem 'jquery-rails' # jQuery libs (JS)
gem 'bootstrap-sass' # Sass-powered version of Bootstrap (CSS / JS libs)
gem 'font-awesome-sass' # Sass-powered version of font-awesome : iconic font & css toolkit
gem 'autoprefixer-rails' # parse CSS and add vendor prefixes to CSS rules
gem 'uglifier', '~> 3.0'

group :development, :test do
  gem 'better_errors' # Improve error page by adding console + better readability
  gem 'pry-byebug' # Adds step-by-step debugging and stack navigation capabilities to pry
  gem 'pry-rails' # Use pry instead of standard console
  gem 'spring' # Rails application preloader
  gem 'sqlite3' # database
end

group :production do
  gem 'rails_12factor' # Better logging & static assets serving
  gem 'pg', '~> 0.18.4'
end
