# Compile SASS
guard 'sass', :input => 'styles/sass', :output => 'styles/css', :smart_partials => true

# Compile Coffeescript
guard 'coffeescript', :input => 'scripts/coffee', :output => 'scripts/js'

# Compress JS
guard :jammit, :output_folder => "scripts/compiled/" do
  watch(%r{^scripts/js/(.*)\.js$})
end

guard 'livereload' do
  watch(%r{.+\.(html|liquid)$})
  watch(%r{styles/.+\.(css|js|html)})
  watch(%r{scripts/.+\.(css|js|html)})
end