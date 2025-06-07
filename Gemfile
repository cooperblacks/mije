source "https://rubygems.org"
gem "github-pages", group: :jekyll_plugins
group :jekyll_plugins do
#  gem "jekyll-remote-theme"
end

install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo"
  gem "tzinfo-data"
end
gem "wdm", :install_if => Gem.win_platform?
