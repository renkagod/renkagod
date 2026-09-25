<div align="center">

# renka

**InfoSec student** · automation, bots and handy utilities for fun

<a href="https://t.me/renka76"><img src="https://img.shields.io/badge/Telegram-@renka76-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"></a>

</div>

```console
$ whoami
renka, fourth-year information security student

$ cat about.txt
I write small tools for problems I actually have. Some of them end up as
Telegram bots. I run a few Debian and Ubuntu servers of my own. I used to
write CTF challenges.
```

## Telegram bots

<table>
<tr>
<td width="33%" valign="top">

### [tg-voice-stt](https://github.com/renkagod/tg-voice-stt)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-2CA5E0?style=flat-square&logo=telegram&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

Turns voice messages and video notes into text with Gemini and streams it as it
comes in. One button strips filler words and adds a short summary. Users pool
their free Gemini keys, and a key that hits the rate limit sits out for a minute.

</td>
<td width="33%" valign="top">

### [birthday-notifier-bot](https://github.com/renkagod/birthday-notifier-bot)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Birthday reminders. You add people in plain text, like `Маша 3 августа`, and pick
when to hear about it: a month ahead, a week, the day before, or right at
midnight. Contacts import from Telegram, and the whole list exports to JSON.

</td>
<td width="33%" valign="top">

### [Alias](https://github.com/renkagod/Alias)

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)

Bot for the Alias party game. It deals random words from Easy, Normal and Hard
decks, links each word to Wiktionary and speaks Russian or English. Admins can
upload their own decks.

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

Fingerprints a music library, finds duplicates and fills in tags and synced
lyrics from several metadata sources.

</td>
<td width="50%" valign="top">

### [vpn-aggregator](https://github.com/renkagod/vpn-aggregator)

![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white)

Merges proxy subscriptions into one list, drops duplicates and checks every
server with parallel TCP probes.

</td>
</tr>
</table>

Smaller things: subscription page templates for the
[3x-ui](https://github.com/renkagod/3xui-subpage) and
[Marzban](https://github.com/renkagod/marzban-subpage) panels.

## Open source

[![Throne](https://img.shields.io/github/issues-search?query=repo%3Athroneproj%2FThrone%20is%3Apr%20is%3Amerged%20author%3Arenkagod&label=Throne&style=flat-square&logo=v2fly&logoColor=white&color=1A73E8)](https://github.com/throneproj/Throne/pulls?q=is%3Apr+author%3Arenkagod+is%3Amerged)

## CTF

I used to write challenges for Caplag CTF: web and forensics labs in hardened
Docker containers ([hardened-docker-ctf-labs](https://github.com/renkagod/hardened-docker-ctf-labs))
and multi-step OSINT investigations ([osint-ctf-labs](https://github.com/renkagod/osint-ctf-labs)),
all with solutions and writeups.

## Stack

<img src="https://skillicons.dev/icons?i=linux,debian,ubuntu,docker,nginx,bash,python,cpp,qt,rust,ts,githubactions" alt="Linux, Debian, Ubuntu, Docker, Nginx, Bash, Python, C++, Qt, Rust, TypeScript, GitHub Actions">

Also Caddy, UFW, encrypted Restic backups, OpenSSL and PKI.
