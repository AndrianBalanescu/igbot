[![Social Manager Tools: IG BOT](https://raw.githubusercontent.com/social-manager-tools/socialmanagertools-igbot/master/.github/assets/smt_igbot_logo.png)](https://socialmanager.tools)

# 🤖 Social Manager Tools: Instagram Bot API

[![](https://img.shields.io/badge/version-v0.9.19-lightgrey.svg)](https://github.com/social-manager-tools/socialmanagertools-igbot/releases) [![](https://img.shields.io/npm/v/@social-manager-tools/igbot.svg)](https://www.npmjs.com/package/@social-manager-tools/igbot) [![](https://img.shields.io/badge/license-MIT-brightgreen.svg)](#) [![](https://img.shields.io/badge/ES-9-F7DF1E.svg)](https://wikipedia.org/wiki/ECMAScript) [![](https://img.shields.io/badge/powered%20by-puppeteer-46aef7.svg)](https://github.com/GoogleChrome/puppeteer) [![](https://snyk.io/test/npm/@social-manager-tools/igbot/badge.svg)](https://snyk.io/test/github/social-manager-tools/socialmanagertools-igbot)

> This library (includes bot and API methods) allows you to increase visits, likes and followers on your social profile through different algorithms and offers API for developers to include custom bot functionality in their application. You will increase the likes on your photos and increase your followers!

> ⛔ **DISCLAIMER**: This is an **unofficial** library and offers no warranty! The developers and contributors of the project do not assume any responsibility in case of ban of your account. Use of instagram bots does not comply with the terms of the service: use this software at your own risk. A "bot" is legal software, but the use of a bot continuously violates the terms of use of Instagram and you risk a: __soft ban__ (such as limited actions or follow-up) or you risk __ban__ with suspension for a few days (or permanent). All trademarks and logos belong to their respective owners.

## 🎁 Support: Donate
> This project is **free**, **open source** and I try to provide excellent **free support**. Why donate? I work on this project several hours a week or in my spare time and try to keep it up to date and working. I do not intend to charge the basic features, but this cannot be done without your financial support, even small. There are professional bots with closed source on the Internet that save the password on the cloud for €14/month: we want to protect your password and offer you a better product than theirs. A lower donation would allow continuous development, ever better quality and the realization of this dream. **THANK YOU!**

[![](https://img.shields.io/badge/donate-paypal-005EA6.svg)](http://paypal.ptkdev.io) [![](https://img.shields.io/badge/donate-patreon-F87668.svg)](http://patreon.ptkdev.io) [![](https://img.shields.io/badge/donate-opencollective-5DA4F9.svg)](http://opencollective.ptkdev.io) [![](https://img.shields.io/badge/buy%20me-coffee-4B788C.svg)](http://coffee.ptkdev.io)

## 📎 Menu
- 💡 [Features](#-features)
- 💾 Installation:
	- 🔨 [Install From Source](http://docs.socialmanager.tools/igbot/installation/source/README.md)
	- 🔨 [Install From NPM](http://docs.socialmanager.tools/igbot/installation/cli/README.md)
	- 👨‍💻 [Desktop App](http://docs.socialmanager.tools/gui/installation/README.md) (Windows, Linux, Mac)
	- 🦀 [Raspberry PI](http://docs.socialmanager.tools/igbot/installation/raspberry/README.md) (Raspbian 9)
	- 🐧 [Linux Server](http://docs.socialmanager.tools/igbot/installation/linux/README.md) (Debian 9 Server)
	- 🐳 [Docker](http://docs.socialmanager.tools/igbot/installation/docker/README.md)
- 🔑 Configs:
	- 🔌 [VPN/Proxy](http://docs.socialmanager.tools/igbot/configs/vpn-proxy/README.md)
	- 💿 [List of Mode](http://docs.socialmanager.tools/igbot/configs/modes/README.md)
	- 📀 [How set Multi-account](http://docs.socialmanager.tools/igbot/configs/multiaccount/README.md)
- 📚 [API Documentation](http://docs.socialmanager.tools/igbot/api/README.md) (How create your personal bot or mode)
- 💻 [Developers Guidelines](http://docs.socialmanager.tools/developers/guidesline/README.md) (If you want contributing)
- 🐛 [Known Bugs](https://github.com/social-manager-tools/socialmanagertools-igbot/issues?q=is%3Aopen+is%3Aissue+label%3Abug)
- 🍻 Community:
	- 🐦 [Telegram group](http://telegram.ptkdev.io)
	- 🐔 [Discord](http://discord.ptkdev.io)
	- 🐓 [Slack](http://slack.ptkdev.io)
	- 🕊 [Medium](http://blog.ptkdev.io)
	- 🐤 [Twitter](http://twitter.ptkdev.io)

## 🔖 Screenshot
[![](https://raw.githubusercontent.com/social-manager-tools/socialmanagertools-igbot/master/.github/assets/screenshot/smt_igbot_screenshot.gif)](#)

## 💡 Features
* [✔️] Easy to use
* [✔️] Login
* [✔️] 2FA (bad location)
* [✔️] 2FA (sms pin enabled)
* [✔️] Multi-Session
* [✔️] Multi-Platform (Windows 10, Mac OSX, Linux and Raspberry PI)
* [✔️] Error management feature (bad pin, bad password)
* [✔️] Screenshot and Verbose logger
* [✔️] Like Mode Classic: bot selects a random hashtag from a config list and likes 1 random photo, and can repeat this all time.
* [✔️] Like Mode Realistic: bot selects a random hashtag from a config list and likes fast 10-12 photos, it sleeps 15-20min and repeats this all time. Sleeps at night.
* [✔️] Like Mode Competitor Users: it selects an account, selects random followers, likes 10-12 photo and sleeps 15-20min. Sleeps at night.
* [✔️] Like Mode Super like: it selects random hashtag from a config list and likes 3 random photos of the same user.
* [✔️] Comment Mode Classic: it selects random comments and random hashtags and writes comments under photos.
* [✔️] Follow/Defollow Classic: follow 30 users, defollow first and rotate (in loop). This method is not detect from socialblade. 300 follow-defollow/day.

## 👨‍💻 Desktop setup (GUI)
1. Download [Social Manager Tools](https://github.com/social-manager-tools/social-manager-tools/releases) GUI.
2. Run application.
3. If it works add a star 🌟 at this project ❤️
4. If you want to help me: **donate on [paypal](http://paypal.ptkdev.io)/[ko-fi](http://coffee.ptkdev.io)** or become a **[backer on patreon](http://patreon.ptkdev.io)**.

## 🔨 Fast usage (Source Code)
1. Download [stable](https://github.com/social-manager-tools/socialmanagertools-igbot/archive/master.zip), [beta](https://github.com/social-manager-tools/socialmanagertools-igbot/archive/beta.zip) or [nightly](https://github.com/social-manager-tools/socialmanagertools-igbot/archive/nightly.zip) and extract it.
2. Download [Node.js](https://nodejs.org/it/) (LTS release) and install it.
3. Run `npm install` in `socialmanagertools-igbot` folder.
4. Remove `.tpl` suffix from `config.js.tpl` file in `configs` folder and fill it properly.
5. Start the bot via `npm run start`
6. If it works add a star 🌟 at this project ❤️
7. If you want to help me: **donate on [paypal](http://paypal.ptkdev.io)/[ko-fi](http://coffee.ptkdev.io)** or become a **[backer on patreon](http://patreon.ptkdev.io)**.

## 🔧 Fast usage (NPM Module)
1. Run `npm install @social-manager-tools/igbot@latest --save` (Available: @latest, @beta and @nightly)
2. Get `config.js` file from `/node_modules/@social-manager-tools/igbot/configs/` folder.
3. Remove `.tpl` suffix from `config.js.tpl` file in `configs` folder and fill it properly.
4. On your code require library, config and run bot, example:
```javascript
const config = require ("./config");
const Bot = require("@social-manager-tools/igbot");
let bot = new Bot(config);

(async () => {
	await bot.start();

	let api = await bot.api();

	let response = await api.login.flow();

	if (response.status) {
		response = await api.twofa.flow();
	}

	if (response.status) {
		response = await api.mode.flow();
	}

	await bot.stop();
})();
```
5. If it works add a star 🌟 at this project ❤️
6. If you want to help me: **donate on [paypal](http://paypal.ptkdev.io)/[ko-fi](http://coffee.ptkdev.io)** or become a **[backer on patreon](http://patreon.ptkdev.io)**.

## 🐳 Docker setup
If you prefer to run this using Docker, an official container is available from the [Docker Hub](https://hub.docker.com/u/socialmanagertools).

In order to run it, copy the `config.js.tpl` file (template of available in `configs` folder), configure it as you prefer, then use it through volume mapping,
like in this example:

```sh
docker run --restart=always --name=socialmanagertools-igbot -d -v /path/to/configs/config.js:/app/configs/config.js socialmanagertools/igbot:amd64
```

**AVAILABLE TAGS:** `amd64` (64bit), `i386` (32bit),`armv7` (Raspberry PI 2 and Raspberry PI 2 ), `armv8` (Raspberry PI ARMv8). All point to the master github repository (stable version).

**WARNING:** with docker is mandatory edit `config.js` and set `chrome_headless` on `true` and set `chrome_executable_path` to `/usr/bin/chromium-browser`. Without this manual fix docker don't work.

## 📚 Documentation
1. Run `npm run docs-init`
2. Run `npm run docs`

If you want are available online [here](http://docs.socialmanager.tools/README.md).

## 👑 Sponsors
Support this project by becoming a sponsor. 🙏 Become a sponsor on [patreon](http://patreon.ptkdev.io) or [opencollective](https://opencollective.com/social-manager-tools#sponsor). Your logo will show up here with a link to your website.

[![](https://opencollective.com/social-manager-tools/sponsor/0/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/0/website) [![](https://opencollective.com/social-manager-tools/sponsor/1/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/1/website) [![](https://opencollective.com/social-manager-tools/sponsor/2/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/2/website) [![](https://opencollective.com/social-manager-tools/sponsor/3/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/3/website) [![](https://opencollective.com/social-manager-tools/sponsor/4/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/4/website) [![](https://opencollective.com/social-manager-tools/sponsor/5/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/5/website) [![](https://opencollective.com/social-manager-tools/sponsor/6/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/6/website) [![](https://opencollective.com/social-manager-tools/sponsor/7/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/7/website) [![](https://opencollective.com/social-manager-tools/sponsor/8/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/8/website) [![](https://opencollective.com/social-manager-tools/sponsor/9/avatar.svg)](https://opencollective.com/social-manager-tools/sponsor/9/website)

## 🦄 Backers
Thank you to all our backers! 🙏 Become a backer on [patreon](http://patreon.ptkdev.io) or [opencollective](https://opencollective.com/social-manager-tools#sponsor)

[![Twitch: prattquellolive](https://raw.githubusercontent.com/social-manager-tools/socialmanagertools-igbot/master/.github/assets/patreon/prattquello.png)](https://www.twitch.tv/prattquellolive) [![](https://opencollective.com/social-manager-tools/backers.svg?width=890)](https://opencollective.com/social-manager-tools#backers)

## ❤️ Contributing
I 💟 contributions! I will happily accept your pull request! Translations, grammatical corrections (GrammarNazi you are welcome! Yes my English is bad, sorry), new modes, best css selectors, fix and new feature! Read [Developers Guidelines](http://docs.socialmanager.tools/developers/guidesline/README.md) for best practices. Do not be afraid, if the code is not perfect we will work together 👯 and remember to insert your name in `.all-contributorsrc` and `package.json` file.

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tr>
    <td align="center"><a href="https://ptk.dev"><img src="https://avatars1.githubusercontent.com/u/442844?v=4" width="100px;" alt="Patryk Rzucidło"/><br /><sub><b>Patryk Rzucidło</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=ptkdev" title="Code">💻</a></td>
    <td align="center"><a href="https://twitter.com/maxfer75"><img src="https://raw.githubusercontent.com/social-manager-tools/socialmanagertools-igbot/master/.github/assets/avatar/maxfer75.jpg" width="100px;" alt="MaXfer "/><br /><sub><b>MaXfer </b></sub></a><br /><a href="#design-maxfer75" title="Design">🎨</a></td>
    <td align="center"><a href="https://twitter.com/tanik72"><img src="https://raw.githubusercontent.com/social-manager-tools/socialmanagertools-igbot/master/.github/assets/avatar/tanik72.jpg" width="100px;" alt="Tanik"/><br /><sub><b>Tanik</b></sub></a><br /><a href="#design-TaniK72" title="Design">🎨</a></td>
    <td align="center"><a href="https://github.com/agoalofalife"><img src="https://avatars1.githubusercontent.com/u/15719824?v=4" width="100px;" alt="Ilua Chubarov"/><br /><sub><b>Ilua Chubarov</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=agoalofalife" title="Code">💻</a></td>
    <td align="center"><a href="https://julianxhokaxhiu.com"><img src="https://avatars1.githubusercontent.com/u/1237070?v=4" width="100px;" alt="Julian Xhokaxhiu"/><br /><sub><b>Julian Xhokaxhiu</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=julianxhokaxhiu" title="Code">💻</a></td>
    <td align="center"><a href="https://lecouey.me"><img src="https://avatars1.githubusercontent.com/u/8327054?v=4" width="100px;" alt="Léonard Lecouey"/><br /><sub><b>Léonard Lecouey</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=lecoueyl" title="Code">💻</a></td>
  </tr>
  <tr>
    <td align="center"><a href="https://github.com/lollymouth"><img src="https://avatars1.githubusercontent.com/u/43947950?v=4" width="100px;" alt="Lollymouth"/><br /><sub><b>Lollymouth</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=lollymouth" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/roNn23"><img src="https://avatars1.githubusercontent.com/u/849194?v=4" width="100px;" alt="roNn23"/><br /><sub><b>roNn23</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=roNn23" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/MoltenKH0R"><img src="https://avatars1.githubusercontent.com/u/6023575?v=4" width="100px;" alt="MoltenKH0R"/><br /><sub><b>MoltenKH0R</b></sub></a><br /><a href="#translation-MoltenKH0R" title="Translation">🌍</a></td>
    <td align="center"><a href="https://github.com/m0s4ik"><img src="https://avatars1.githubusercontent.com/u/26578395?v=4" width="100px;" alt="Andrea"/><br /><sub><b>Andrea</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=m0s4ik" title="Code">💻</a> <a href="https://github.com/ptkdev/socialmanagertools-igbot/issues?q=author%3Am0s4ik" title="Bug reports">🐛</a></td>
    <td align="center"><a href="https://github.com/trungpv1601"><img src="https://avatars1.githubusercontent.com/u/25415217?v=4" width="100px;" alt="trungpv1601"/><br /><sub><b>trungpv1601</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=trungpv1601" title="Code">💻</a></td>
    <td align="center"><a href="https://github.com/Ermolaev-Nikolay"><img src="https://avatars1.githubusercontent.com/u/44134625?v=4" width="100px;" alt="Ermolaev-Nikolay"/><br /><sub><b>Ermolaev-Nikolay</b></sub></a><br /><a href="https://github.com/ptkdev/socialmanagertools-igbot/commits?author=Ermolaev-Nikolay" title="Code">💻</a></td>
  </tr>
</table>

<!-- markdownlint-enable -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

> 💰 In the future, if the donations allow it, I would like to share some of the success with those who helped me the most. For me open source is share of code, share development knowledges and share donations!

## 📲 Tools
[![](https://img.shields.io/badge/app-social%20manager%20tools-ff7f19.svg)](http://socialmanager.tools/)
[![](https://img.shields.io/badge/api-instagram%20bot-895a4d.svg)](https://github.com/social-manager-tools/socialmanagertools-igbot)
[![](https://img.shields.io/badge/api-twitter%20bot-21B7F4.svg)](https://github.com/social-manager-tools/socialmanagertools-twbot)
[![](https://img.shields.io/badge/api-facebook%20bot-3b5998.svg)](https://github.com/social-manager-tools/socialmanagertools-fbbot)
[![](https://img.shields.io/badge/telegram%20bot-feed%20rss%20for%20wordpress%20&amp;%20medium-00AB6C.svg)](https://github.com/social-manager-tools/social-manager-tools-tgbot)

[![](https://img.shields.io/badge/app-meingifs-E1215B.svg)](https://meingifs.pics/)
[![](https://img.shields.io/badge/stickers-ptkdev-128C7E.svg)](https://stickers.ptkdev.io/)

## 🐍 Sorry for snake_case
I love snake_case syntax sorry for this 😭 don't hate me.

## 💫 License
* Code and Contributions have **MIT License**
* Images and logos have **CC BY-NC 4.0 License**
* Documentations and Translations have **CC BY 4.0 License**

###### Copyleft (c) 2018-2019 [Patryk Rzucidło](https://ptk.dev) ([@PTKDev](https://twitter.com/ptkdev)) <[support@ptkdev.io](mailto:support@ptkdev.io)>