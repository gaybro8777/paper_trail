# Specify here only version constraints that differ from
# `paper_trail.gemspec`.
#
# > The dependencies in your Appraisals file are combined with dependencies in
# > your Gemfile, so you don't need to repeat anything that's the same for each
# > appraisal. If something is specified in both the Gemfile and an appraisal,
# > the version from the appraisal takes precedence.
# > https://github.com/thoughtbot/appraisal

appraise "ar-4.0" do
  gem "activerecord", "~> 4.0"
  gem "sinatra", "~> 1.4.6"
end

appraise "ar-4.2" do
  gem "activerecord", "~> 4.2"
  gem "sinatra", "~> 1.4.6"
end

appraise "ar-5.0" do
  gem "activerecord", "~> 5.0.0"
  gem "rspec-rails", "~> 3.5.1"
  gem 'rails-controller-testing'

  # The AR5 version of PaperTrail is not compatible with sinatra 2 yet.
  # Contributions welcome.
  # gem "sinatra", "2.0.0.beta2"
end

appraise "ar_master" do
  gem "rails", github: "rails/rails"
  gem "rspec-rails", "~> 3.5.1"
  gem "rails-controller-testing"
end
