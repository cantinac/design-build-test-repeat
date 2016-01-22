require 'html/proofer'

task :test do
  sh "rm -rf _site"
  sh "bundle exec jekyll build -d _site"
  HTML::Proofer.new("./_site").run
end
