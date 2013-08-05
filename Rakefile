require 'rubygems'

task :html, :dir do |t, args|
    sh %{dowl #{args[:dir]}/index.ttl templates/dowl_template.erb >#{args[:dir]}/index.html}
end
