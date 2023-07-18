---
name: gem install bundler fails
about: software conflict prevents commits from being pushed
title: ''
labels: ''
assignees: ''

---

I receive this error after pushing a commit: Your RubyGems version (3.0.3) has a bug that prevents `required_ruby_version` from working for Bundler. Any scripts that use `gem install bundler` will break as soon as Bundler drops support for your Ruby version. Please upgrade RubyGems to avoid future breakage and silence this warning by running `gem update --system 3.2.3`
