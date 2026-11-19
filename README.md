<div align="center">

<img src=".github/logo.png" width="128" alt="Onegram logo">

# Onegram Android

**Telegram, made a little better.**
Same account, same chats. Plus one feed for all channels, translation of whole chats and business tools for free.

[![Release](https://img.shields.io/github/v/release/onegramteam/onegram?label=release&color=2F96E0)](https://github.com/onegramteam/onegram/releases/latest)
[![Android](https://img.shields.io/badge/Android-7.0%2B-2F96E0?logo=android&logoColor=white)](https://github.com/onegramteam/onegram/releases/latest)
[![License](https://img.shields.io/badge/license-GPL--2.0-2F96E0)](LICENSE)
[![Telegram](https://img.shields.io/badge/Telegram-@onegramnews-2F96E0?logo=telegram&logoColor=white)](https://t.me/onegramnews)

[Website](https://onegram.me) · [Download](https://github.com/onegramteam/onegram/releases/latest) · [News](https://t.me/onegramnews) · [Chat](https://t.me/onegramchat)

</div>

---

Onegram is an unofficial Telegram client for Android, built on the official Telegram source code. Your account, your chats and your contacts stay the same: sign in with your number and everything loads from the Telegram cloud.

## Features

**Translation** — whole chats appear in your language as you scroll. Translate your reply before sending, so they read it in theirs.

**Channel feed** — read every channel as one feed with comments right under the post. Group it by folder, collapse long posts, hide ad posts by keywords. Follow channels as a guest, without joining.

**Business, free** — working hours, away replies, greetings, quick replies, chat labels and client notes. No Telegram Business needed.

**AI on your own key** — summarise a long chat, rewrite your reply. Your data is never used for training.

And more:

- PIN or fingerprint on chosen chats and folders
- Music library: every track from your chats in one player
- Tor and proxies with a kill switch
- Tabs of open chats, text recognition in photos
- HD round videos and stories, voice messages up to 128 kbit/s, faster uploads
- Your own name colours, menu style, transitions and icon pack
- Eight app icons for free

| | Onegram | Telegram |
|---|:---:|:---:|
| All channels in one feed | ✓ | — |
| Follow channels without joining | ✓ | — |
| Comments right under the post | ✓ | — |
| PIN on single chats and folders | ✓ | — |
| AI summaries on your own key | ✓ | — |
| Music library from all chats | ✓ | — |
| Tor with a kill switch | ✓ | — |
| Translate whole chats | free | Premium |
| Business: hours, auto-replies, labels | free | Premium |

## Download

Get the latest APK from [Releases](https://github.com/onegramteam/onegram/releases/latest) or from [@onegramnews](https://t.me/onegramnews). One universal APK for every phone with Android 7.0 or newer.

To get updates automatically, add this repository to [Obtainium](https://github.com/ImranR98/Obtainium).

## Building

Requirements: JDK 17, Android SDK and NDK, about 15 GB of free disk space.

1. Clone the repository.
2. Get your own `api_id` and `api_hash` at [my.telegram.org](https://my.telegram.org) and put them in the build config.
3. Create your own signing key and point the build to it.
4. Build with Android Studio or `./gradlew assembleRelease`.

A build you make yourself is signed with your key and will not install over the official APK.

## Community

- News and downloads: [@onegramnews](https://t.me/onegramnews)
- Chat: [@onegramchat](https://t.me/onegramchat)
- Support: [@OnegramSupportBot](https://t.me/OnegramSupportBot)

Bug reports and ideas are welcome in [Issues](https://github.com/onegramteam/onegram/issues).

## License

Onegram is free software under the [GNU General Public License v2.0](LICENSE), as is the Telegram for Android source code it is based on.

Onegram is an unofficial client and is not affiliated with, endorsed by or sponsored by Telegram. Telegram is a trademark of its respective owner.

---

<details>
<summary><b>Русский</b></summary>

**Onegram** — неофициальный клиент Telegram для Android на основе официального исходного кода Telegram. Аккаунт, чаты и контакты те же: войдите по номеру, и всё загрузится из облака Telegram.

- **Перевод:** целые чаты на вашем языке, перевод ответа перед отправкой.
- **Лента каналов:** все каналы одной лентой, комментарии под постом, каналы без подписки.
- **Бизнес бесплатно:** часы работы, автоответы, приветствия, быстрые ответы, метки чатов.
- **ИИ на своём ключе:** пересказ чата и помощь с ответом.
- PIN на чаты и папки, музыкальная библиотека, Tor с защитой от утечек, восемь иконок приложения.

Скачать: [Releases](https://github.com/onegramteam/onegram/releases/latest) · [@onegramnews](https://t.me/onegramnews) · Чат: [@onegramchat](https://t.me/onegramchat)

</details>
