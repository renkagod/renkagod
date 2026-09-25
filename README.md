<div align="center">

# renka

**InfoSec student** · automation, bots and handy utilities for fun

<a href="https://t.me/renka76"><img src="https://img.shields.io/badge/Telegram-@renka76-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>
<a href="https://github.com/throneproj/Throne/pulls?q=is%3Apr+author%3Arenkagod+is%3Amerged"><img src="https://img.shields.io/github/issues-search?query=repo%3Athroneproj%2FThrone%20is%3Apr%20is%3Amerged%20author%3Arenkagod&label=Throne%20merged%20PRs&style=for-the-badge&logo=github&color=1A73E8" alt="Merged pull requests to Throne"></a>

</div>

```console
$ whoami
renka, fourth-year information security student

$ cat about.txt
I write small tools for problems I run into myself, and a few of them are
Telegram bots. I also run some Debian and Ubuntu servers of my own and send
patches to Throne, the proxy client I use every day. Some time ago I wrote
CTF challenges.
```

## Telegram bots

<table>
<tr>
<td width="33%" valign="top">

### [tg-voice-stt](https://github.com/renkagod/tg-voice-stt)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-2CA5E0?style=flat-square&logo=telegram&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

Transcribes voice messages and video notes with Gemini and streams the text as
it arrives. A button removes filler words and adds a structured summary. To get
access you add your free Gemini key to a shared pool; a key that hits the rate
limit sits out for a minute.

</td>
<td width="33%" valign="top">

### [birthday-notifier-bot](https://github.com/renkagod/birthday-notifier-bot)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

You add people in plain text, like `Маша 3 августа`, and the bot reminds you
anywhere from a month ahead to five minutes before. It can pull a contact
straight from Telegram, and the whole list exports to JSON and back.

</td>
<td width="33%" valign="top">

### [Alias](https://github.com/renkagod/Alias)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

A bot for the Alias party game. It deals random words from the Easy, Normal and
Hard decks and links each one to Wiktionary. The interface is in Russian or
English, and admins can upload their own decks.

</td>
</tr>
</table>

## Desktop apps

<table>
<tr>
<td width="50%" valign="top">

### [music-sorter](https://github.com/renkagod/music-sorter)

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)

Finds duplicate tracks by audio fingerprint (Chromaprint and AcoustID) and pulls
tags from MusicBrainz, Discogs, VocaDB and other databases, with synced lyrics
from LRCLIB. There's a built-in player with a waveform view.

</td>
<td width="50%" valign="top">

### [vpn-aggregator](https://github.com/renkagod/vpn-aggregator)

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

Merges several proxy subscriptions into one deduplicated list and checks every
server with parallel TCP probes.

</td>
</tr>
</table>

Smaller things: subscription page templates for the
[3x-ui](https://github.com/renkagod/3xui-subpage) and
[Marzban](https://github.com/renkagod/marzban-subpage) panels.

## Open source

My patches to [Throne](https://github.com/throneproj/Throne), a C++/Qt proxy client,
touch the tray menu, the connections view (a process tree and routing from the
context menu) and the Russian translation.

## CTF

I used to write challenges for Caplag CTF: web and forensics labs packed into
hardened Docker containers ([hardened-docker-ctf-labs](https://github.com/renkagod/hardened-docker-ctf-labs))
and multi-phase OSINT investigations ([osint-ctf-labs](https://github.com/renkagod/osint-ctf-labs)).
Each one comes with a writeup and a solution.

## Stack

<img src="https://skillicons.dev/icons?i=linux,debian,ubuntu,docker,nginx,bash,python,cpp,qt,rust,ts,githubactions" alt="Linux, Debian, Ubuntu, Docker, Nginx, Bash, Python, C++, Qt, Rust, TypeScript, GitHub Actions">

Also Caddy, UFW, encrypted Restic backups, OpenSSL and PKI.
