# v0.10.0-nightly (TBD)
* Feature: 11 modes (like and follow defollow with locations)
* Feature: translations (Italian and English, contributions and grammar nazi are welcome!)
* Feature: support proxy/vpn if you want use cloud/vps/aws/server
* Feature: you can overwrite css selectors in `config.js` if broken on instagram web site
* Feature: Full API system (34 methods!) for developers (create your bot and modes!), see [docs](https://github.com/social-manager-tools/socialmanagertools-docs/README.md).
* Update: better log system
* Coming Soon: plugin system
* Feature: multi puppeeter package available on npm tags
* ...and more other improvements and refactoring code!

[![](https://img.shields.io/badge/donate-paypal-005EA6.svg)](http://paypal.ptkdev.io) [![](https://img.shields.io/badge/donate-patreon-F87668.svg)](http://patreon.ptkdev.io) [![](https://img.shields.io/badge/donate-opencollective-5DA4F9.svg)](http://opencollective.ptkdev.io) [![](https://img.shields.io/badge/buy%20me-coffee-4B788C.svg)](http://coffee.ptkdev.io) [![](https://img.shields.io/badge/help-support@ptkdev.io-fbbc05.svg)](mailto:support@ptkdev.io)


# v0.9.19 (28 September, 2019)
* Upgrade: puppeteer v1.19.0 (chrome v77)


# v0.9.18 (10 July, 2019)
* Fix: commentmode
* Fix: fdfmode
* Fix: minor issue.


# v0.9.17 (15 May, 2019)
* Upgrade: puppeteer v1.13.0


# v0.9.16 (04 April, 2019)
* Fix: argv restored, now multi account with `node bot.js --config="XXXXX"` work.


# v0.9.15 (03 April, 2019)
* Fix: missing ssl certificates docker
* Fix: if `api.socialmanager.tools` are offline, bot don't crash


# v0.9.14 (01 April, 2019)
* Downgrade: puppeteer v1.11.0
* Fix (again): `waiting for selector "article div a:nth-child(1)" failed: timeout 30000ms exceeded` happen because puppeteer v1.12.0 has a bug of timeout...


# v0.9.13 (31 March, 2019)
* Fix: `waiting for selector "article div a:nth-child(1)" failed: timeout 30000ms exceeded` happen when photo don't exist or are removed, now skip faster (3sec)
* Fix: docker curl package missing


# v0.9.12 (28 March, 2019)
* Fix: docker permissions
* Fix: README.md misprint


# v0.9.11 (27 March, 2019)
* New: `instagrambotlib` and `instagram-bot.js` now is `socialmanagertools-igbot`
* New: npm package org: `npm install @social-manager-tools/igbot`
* Deprecated: rolling release version
* Fix: Login
* Fix: fdfmode_classic
* Upgrade: docker images
* Upgrade: puppeteer v1.12.2


# v0.9.10 (04 November, 2018)
* Developers: [Guidelines](https://github.com/social-manager-tools/socialmanagertools-igbot/blob/nightly/DEV_GUIDELINES.md) for contributing at project.
* Test: add mocha and chai
* Fix: fdfmode_classic loop bug
* Upgrade: puppeteer v1.7.0


# v0.9.9 (16 October, 2018)
* Fix: fdfmode_classic #42 (again again...)
* Fix: 2FA (Location)
* Fix: Close button (ui)
* Fix: lose connection bot stop, now retry work.


# v0.9.8 (14 October, 2018)
* Fix: fdfmode_classic #42 (again)
* Fix: 2FA doesn't work #48 (after 3 months... thanks instagram!)
* Update: default value of `chrome_headless` is `true`
* Update: all library of package.json


# v0.9.7 (08 October, 2018)
* Fix: fdfmode_classic #42


# v0.9.6 (05 October, 2018)
* Fix: login random don't work


# v0.9.5 (02 October, 2018)
* Fix: likemode_classic new instagram selectors
* Fix: likemode_realistic new instagram selectors
* Fix: likemode_superlike new instagram selectors
* Fix: likemode_competitor_users new instagram selectors
* Fix: comment_mode new instagram selectors
* Fix: fdfmode_classic new instagram selectors
* API: Fix stop() again, now really work.


# v0.9.4 (26 September, 2018)
* Fix: API::stop() now work correctly
* Fix: Follow/Defollow Mode Realistic random userpage is 404
* Fix: docker container (by [Julian Xhokaxhiu](https://github.com/julianxhokaxhiu)) #95
* Upgrade: puppeteer v1.6.2


# v0.9.3 (22 September, 2018)
* Fix: Follow/Defollow Mode Realistic stop working if photo or account are removed
* Fix: Like Mode Realistic correct like/don't like message
* Performance: all actions are now fastest than 1-2 seconds


# v0.9.2 (15 September, 2018)
* Downgrade: puppeteer v1.4.0 (#27)


# v0.9.1 (15 September, 2018)
* Fix: Node is either not visible or not an HTMLElement (#82 #86 #84)
* Fix: Random crash of Follow/Defollow Mode Realistic
* Refactor: 2FA flow
* Update: New user-agent
* Upgrade: puppeteer v1.8.0


# v0.9.0b (09 September, 2018)
* Fix: bad creation of folders `databases` and `logs` (#79)


# v0.9.0 (08 September, 2018)
* Feature: Follow/Defollow Mode (#77)
* Feature: Support sqllite connector (#70)
* Fix: Like Realistic random freeze
* Fix: Comment Mode don't work
* Fix: Like Competitor Mode (#76)
* API: stop() | stop the bot from your application
* Update: bot_fastlike_min and max from config.js now all mode use bot_likeday_min and max
* Update: bot_sleep_night disabled at default
* Upgrade: puppeteer v1.7.0


# v0.8.2 (26 July, 2018)
* Fix: default path of logs in `config.js.tpl`


# v0.8.1 (25 July, 2018)
* Fix: Unliking already liked pictures (all mode) [Bug: #59]
* Fix: Commenting already commented pictures
* Update: `likemode_realistic` now is default mode in `config.js.tpl`
* Update: `900` now is default value of max like/day in `config.js.tpl`


# v0.8.0 (17 July, 2018)
* Fix: path of logs and screenshot


# v0.7.5c and v0.7.5d (11 July, 2018)
* Fix: likemode_superlike timeout error


# v0.7.5b (09 July, 2018)
* Feature: path log/pin and uifix() for social-manager-tools app


# v0.7.5 (03 July, 2018)
* Update: Porting of socialmanagertools-igbot v0.7.5


# v0.7.4c (29 June, 2018)
* Fix: Porting of socialmanagertools-igbot v0.7.4


# v0.7.4b (28 June, 2018)
* Update: Porting of socialmanagertools-igbot v0.7.4


# v0.6.1 (20 February, 2018)
* Update: Porting of socialmanagertools-igbot v0.6.1