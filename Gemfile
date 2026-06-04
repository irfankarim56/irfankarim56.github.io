source "https://rubygems.org"

# Jekyll 4.x — pinned for reproducible GitHub Pages builds
gem "jekyll", "~> 4.3.4"

# Pin sass converter to the 2.x line. This uses sassc (precompiled, CI-stable)
# instead of sass-embedded, whose native binary download is what caused the
# `bundle install` failure (Bundler::InstallError / exit code 5).
gem "jekyll-sass-converter", "~> 2.0"

# Required on Ruby 3.x (webrick was removed from the standard library).
gem "webrick", "~> 1.8"

group :jekyll_plugins do
  # Add any Jekyll plugins your site uses here, e.g.:
  # gem "jekyll-feed", "~> 0.17"
  # gem "jekyll-sitemap", "~> 1.4"
end
