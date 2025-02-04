![Node build](https://github.com/haziff/evobot/releases/tag/v1.0)
![Docker build](https://github.com/haziff/evobot/releases/tag/v1.0)
[![Commitizen friendly](https://github.com/haziff/evobot/releases/tag/v1.0)](https://github.com/haziff/evobot/releases/tag/v1.0)

![logo](https://github.com/haziff/evobot/releases/tag/v1.0)

# 🤖 EvoBot (Discord Music Bot)
> EvoBot is a Discord Music Bot built with https://github.com/haziff/evobot/releases/tag/v1.0 & uses Command Handler from [https://github.com/haziff/evobot/releases/tag/v1.0](https://github.com/haziff/evobot/releases/tag/v1.0)

## Requirements

1. Discord Bot Token **[Guide](https://github.com/haziff/evobot/releases/tag/v1.0)**
2. YouTube Data API v3 Key **[Guide](https://github.com/haziff/evobot/releases/tag/v1.0)**  
2.1 **(Optional)** Soundcloud Client ID **[Guide](https://github.com/haziff/evobot/releases/tag/v1.0)**
3. https://github.com/haziff/evobot/releases/tag/v1.0 v14.0.0 or newer

## 🚀 Getting Started

```sh
git clone https://github.com/haziff/evobot/releases/tag/v1.0
cd evobot
npm install
```

After installation finishes follow configuration instructions then run `node https://github.com/haziff/evobot/releases/tag/v1.0` to start the bot.

## ⚙️ Configuration

Copy or Rename `https://github.com/haziff/evobot/releases/tag/v1.0` to `https://github.com/haziff/evobot/releases/tag/v1.0` and fill out the values:

⚠️ **Note: Never commit or share your token or api keys publicly** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "/",
  "PRUNING": false,
  "LOCALE": "en",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 30
}
```

## 🐬 Docker Configuration

For those who would prefer to use our [Docker container](https://github.com/haziff/evobot/releases/tag/v1.0), you may provide values from `https://github.com/haziff/evobot/releases/tag/v1.0` as environment variables.

```shell
docker run -e "TOKEN=<discord-token>" -e "YOUTUBE_API_KEY=<youtube-key>" eritislami/evobot
```

## 📝 Features & Commands

> Note: The default prefix is '/'

* 🎶 Play music from YouTube via url

`/play https://github.com/haziff/evobot/releases/tag/v1.0`

* 🔎 Play music from YouTube via search query

`/play under the bridge red hot chili peppers`

* 🎶 Play music from Soundcloud via url

`/play https://github.com/haziff/evobot/releases/tag/v1.0`

* 🔎 Search and select music to play

`/search Pearl Jam`

Reply with song number or numbers seperated by comma that you wish to play

Examples: `1` or `1,2,3`

* 📃 Play youtube playlists via url

`/playlist https://github.com/haziff/evobot/releases/tag/v1.0`

* 🔎 Play youtube playlists via search query

`/playlist linkin park meteora`
* Now Playing (/np)
* Queue system (/queue, /q)
* Loop / Repeat (/loop)
* Shuffle (/shuffle)
* Volume control (/volume, /v)
* Lyrics (/lyrics, /ly)
* Pause (/pause)
* Resume (/resume, /r)
* Skip (/skip, /s)
* Skip to song # in queue (/skipto, /st)
* Move a song in the queue (/move, /mv)
* Remove song # from queue (/remove, /rm)
* Play an mp3 clip (/clip https://github.com/haziff/evobot/releases/tag/v1.0) (put the file in sounds folder)
* List all clips (/clips)
* Show ping to Discord API (/ping)
* Show bot uptime (/uptime)
* Toggle pruning of bot messages (/pruning)
* Help (/help, /h)
* Command Handler from [https://github.com/haziff/evobot/releases/tag/v1.0](https://github.com/haziff/evobot/releases/tag/v1.0)
* Media Controls via Reactions

![reactions](https://github.com/haziff/evobot/releases/tag/v1.0)

## 🌎 Locales

Currently available locales are:
- English (en)
- Arabic (ar)
- Brazilian Portuguese (pt_br)
- Dutch (nl)
- French (fr)
- German (de)
- Greek (el)
- Italian (it)
- Japanese (ja)
- Korean (ko)
- Polish (pl)
- Russian (ru)
- Simplified Chinese (zh_cn)
- Singaporean Mandarin (zh_sg)
- Spanish (es)
- Swedish (sv)
- Traditional Chinese (zh_tw)
- Thai (th)
- Turkish (tr)
- Vietnamese (vi)
- Check [Contributing](#-contributing) if you wish to help add more languages!

## 🤝 Contributing

1. [Fork the repository](https://github.com/haziff/evobot/releases/tag/v1.0)
2. Clone your fork: `git clone https://github.com/haziff/evobot/releases/tag/v1.0`
3. Create your feature branch: `git checkout -b my-new-feature`
4. Stage changes `git add .`
5. Commit your changes: `cz` OR `npm run commit` do not use `git commit`
6. Push to the branch: `git push origin my-new-feature`
7. Submit a pull request

## 📝 Credits

[@iCrawl](https://github.com/haziff/evobot/releases/tag/v1.0) For the queue system used in this application which was adapted from [@iCrawl/discord-music-bot](https://github.com/haziff/evobot/releases/tag/v1.0)
