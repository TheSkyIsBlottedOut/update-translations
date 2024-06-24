@ Translation utility

1. Install ruby and bundler!
1. Run `bundle install` to install all the stuff you need.
1. Get a google translate api key and put it in .google_api_key or in ENV['GOOGLE_TRANSLATE_KEY'].
1. Use `update-translations [locale] [path-with-translation.yml files]` to create new files for the desired locale.

The google cost is relatively cheap, about $0.11 for a largish file.
It will keep interpolations from being translated.
THis is a good makeshift utility for short term conversions for bootstrapping projects when I18n support is not (yet) a priority.