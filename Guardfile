# Compile SASS
guard 'sass', :input => 'styles/sass', :output => 'styles/css', :smart_partials => true

guard 'livereload' do
  watch(%r{.+\.(html|liquid)$})
  watch(%r{styles/.+\.(css|js|html)})
  watch(%r{scripts/.+\.(css|js|html)})
end