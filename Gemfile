source "https://rubygems.org"

ruby '2.6.0'

gem "jekyll", "~> 3.8.0" # v4 releasing soon, might not be compatible with all plugins, https://github.com/jekyll/jekyll

gem "slim"
gem "jekyll-slim", git: 'https://github.com/olery/jekyll-slim', ref: '48c27ea', group: :jekyll_plugins # https://github.com/slim-template/jekyll-slim/issues/4#issuecomment-357439366

group :jekyll_plugins do
  ### Assets
  gem 'jekyll-assets' # https://github.com/envygeeks/jekyll-assets
  #gem 'jekyll_asset_pipeline' # https://github.com/matthodan/jekyll-asset-pipeline
  #npm 'jekyll-bliss' # https://gitlab.com/dougbeney/Jekyll-Bliss
  
  ### Command Line
  gem 'jekyll-compose' # command line for jekyll posts, https://github.com/jekyll/jekyll-compose
  gem 'jekyll-deploy' # add customizable `jekyll deploy` command, https://github.com/vwochnik/jekyll-deploy
  gem 'jekyll-extract' # Extract theme-gem contents to source directory, https://github.com/ashmaroli/jekyll-extract
  
  ### i18n
  gem "jekyll-polyglot" # best, https://github.com/untra/polyglot
  #gem 'jekyll-locale' # https://github.com/ashmaroli/jekyll-locale
  #gem "jekyll-multiple-languages-plugin" # runner up, https://github.com/Anthony-Gaudino/jekyll-multiple-languages-plugin 

  ### Data Plugins
  gem "jekyll-manager" # fork of jekyll-admin
  gem 'jekyll-data' # Read '_config.yml' and data files within Jekyll theme gems, https://github.com/ashmaroli/jekyll-data
  gem 'jekyll-paginate-v2' # https://github.com/sverrirs/jekyll-paginate-v2
  gem 'jekyll-archives' # add index pages by dates, tags, and categories, https://github.com/jekyll/jekyll-archives
  #npm 'simple-jekyll-search' # https://github.com/christian-fei/Simple-Jekyll-Search
  #gem 'jekyll-tagging' # makes tags easier to use?, https://github.com/pattex/jekyll-tagging
  #gem 'jekyll-tagging-related_posts' # add related posts support to jekyll-tagging, https://github.com/toshimaru/jekyll-tagging-related_posts
  #gem 'jekyll-analytics' # https://github.com/hendrikschneider/jekyll-analytics
  #gem 'jekyll-scholar' # Academic blogging support, https://github.com/inukshuk/jekyll-scholar
  #gem 'jekyll-feed' # https://github.com/jekyll/jekyll-feed 
  
  ### View Helpers
  gem 'jekyll-contentblocks' # `content_for` from Rails, https://github.com/rustygeldmacher/jekyll-contentblocks
  gem 'jekyll-picture-tag', git: 'https://github.com/robwierzbowski/jekyll-picture-tag' # Easy responsive images
  gem 'jekyll_inline_highlight' # https://github.com/bdesham/inline_highlight
  gem 'liquid_pluralize' # https://github.com/bdesham/pluralize
  gem 'liquid-humanize-number' # https://github.com/mrzen/liquid-humanize-number-filter
  #gem 'jekyll-cloudinary' # https://github.com/nhoizey/jekyll-cloudinary
  #gem 'jekyll-maps' # https://github.com/ayastreb/jekyll-maps
  #gem 'jekyll-avatar' # rendering GitHub avatars, https://github.com/benbalter/jekyll-avatar
  #gem 'jekyll-gist' # https://github.com/jekyll/jekyll-gist
  #gem 'jeykll-figure' # HTML <figure> support, https://github.com/paulrobertlloyd/jekyll-figure
  #gem "jekyll-toc" # table of contents support, https://github.com/toshimaru/jekyll-toc
  #gem 'jekyll-timeago' # https://github.com/markets/jekyll-timeago
  #gem 'liquid_reading_time' # https://github.com/bdesham/reading_time
  
  ### Configuration Plugins
  gem 'jekyll-seo-tag' # https://github.com/jekyll/jekyll-seo-tag
  gem 'jekyll-sitemap' # https://github.com/jekyll/jekyll-sitemap
  gem 'jekyll-redirect-from' # page redirects, https://github.com/jekyll/jekyll-redirect-from
  gem 'jekyll-postfiles' # allows specifying files with relative path, https://github.com/nhoizey/jekyll-postfiles
  gem 'jekyll-firstimage' # https://github.com/nhoizey/jekyll-firstimage
  gem 'jekyll-liquify', git: "https://github.com/tobyspark/jekyll-liquify" # liquid in front_matter, https://github.com/gemfarmer/jekyll-liquify
  gem 'jekyll-titles-from-headings' # https://github.com/benbalter/jekyll-titles-from-headings
  gem 'jekyll-optional-front-matter' # https://github.com/benbalter/jekyll-optional-front-matter
  #gem 'jekyll-default-layout' # https://github.com/benbalter/jekyll-default-layout
  #gem 'jekyll-readme-index' # Use readme as index page, https://github.com/benbalter/jekyll-readme-index
  #ungemified 'jekyll-gallery-tag' # https://github.com/martinruenz/JekyllGalleryTag
  #ungemified 'remote-include' # https://github.com/knorthfield/remote-include
end
