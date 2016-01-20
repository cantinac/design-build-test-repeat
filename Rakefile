require 'html/proofer'

task :test do
  sh "rm -rf _site"
  sh "bundle exec jekyll build -d _site/design-build-test-repeat"
  HTML::Proofer.new("./_site").run
end