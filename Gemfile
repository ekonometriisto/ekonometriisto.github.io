source "https://rubygems.org"
# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
gem "jekyll", "= 3.9.4" # <-- 이 부분을 Jekyll 3.9.4 버전으로 변경했습니다.
# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima", "~> 2.5"

gem "github-pages", "~> 229", group: :jekyll_plugins


# Monos 테마 추가 (이 줄은 이전에 에러를 냈으므로 주석 처리된 상태로 유지)
# gem "jekyll-theme-monos"
# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# gem "github-pages", group: :jekyll_plugins # 이 줄은 위에서 이미 활성화되어 있으므로 중복하지 않습니다.
# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-remote-theme" # <--- 이 줄을 추가합니다.

end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1", :platforms => [:mingw, :x64_mingw, :mswin]

# Lock `http_parser.rb` gem to `v0.6.x` on JRuby builds since newer versions of the gem
# do not have a Java counterpart.
gem "http_parser.rb", "~> 0.6.0", :platforms => [:jruby]