task :release do
  puts `gem build github-api-rails.gemspec`
  puts `gem push *.gem`
  puts `rm *.gem`
end
