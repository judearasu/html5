# A sample Guardfile
# More info at https://github.com/guard/guard#readme

guard 'livereload' do
  # Rails Assets Pipeline
  watch(%r{(app|vendor)(/assets/\w+/(.+\.(css|js|html))).*}) { |m| "/assets/#{m[3]}" }
end
