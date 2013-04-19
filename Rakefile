namespace :npm do
  task :install do
    sh "npm install"
  end
end

namespace :test do
  namespace :karma do
    desc "Start the Karma test runner"
    task :start => 'npm:install' do
      sh "node_modules/karma/bin/karma start src/test/js/config/karma.unit.js"
    end
  end
end