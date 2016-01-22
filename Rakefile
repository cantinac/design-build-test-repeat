require 'html/proofer'

task :test do
  sh "rm -rf _site"
  sh "bundle exec jekyll build"
  HTML::Proofer.new("./_site").run
end
