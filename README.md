This repository contains social metadata for soccer teams that participate to the 2015/2016 [UEFA Champions League](http://www.uefa.com/uefachampionsleague/).

Feel free to use this dataset and contribute to it!

# DATA FORMAT

* `name` Name of the team
* `country` Country of the team
* `wikipedia` English wikipedia page (prefix `https://en.wikipedia.org`)
* `facebook` Facebook account (prefix `https://www.facebook.com`)
* `twitter` Twitter handle
* `reddit` Reddit page (prefix `https://www.reddit.com`)

# RFD - Request For (Meta)Data

Main focus is on static data related to the teams:

* Teams official website
* Universal short ids for the team. Similar to 3-digit [ISO codes](https://en.wikipedia.org/wiki/ISO_3166-1) that are often used to display live score on TV.
* Team players (participating to the tournament) and their Twitter/FB/Wiki account.
* Other languages for Twitter, Facebook, etc.
* Hashtags for the teams on Twitter
* Team badges

# SOURCES

* [Wikipedia](https://en.wikipedia.org/)
* [Reddit soccer data](https://www.reddit.com/r/soccerbot/wiki/index)

# CONTRIBUTING

There are many ways to contribute to this project, such as:

* Fixing data 
* Adding new attributes (see the RFD above)
* Suggesting a new data structure (nesting, internationalization, ..)
* Build historical data (e.g. for previous tournaments)

Please note:

* Changes must be made via pull request
* Keep the current indentation to ease the diff
* All string must be encoded in UTF-8
* Use GitHub for all communication (issues, fixes, ..)
