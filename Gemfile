# frozen_string_literal: true

source "https://rubygems.org"

git_source(:github) {|repo_name| "https://github.com/#{repo_name}" }

#Gemfile
gem "jekyll"
# gem "rails"

# Temporarily lock ffi gem to v1.12.x on Windows
platforms :mswin, :mingw, :x64_mingw do
    gem "ffi", "~> 1.13.0"
  end
