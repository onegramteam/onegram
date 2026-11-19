# Onegram features

Everything Onegram for Android adds on top of Telegram: **211 features** in 33 sections. Most of them are off by default and live in Onegram settings, so the app looks like the Telegram you know until you turn something on.

## Contents

- [Accounts and sign-in](#accounts-and-sign-in) · 8
- [Privacy and ghost mode](#privacy-and-ghost-mode) · 14
- [Deleted and edited messages](#deleted-and-edited-messages) · 2
- [Protected content and self-destruct](#protected-content-and-self-destruct) · 1
- [Messages: sending](#messages-sending) · 20
- [Messages: reading and actions](#messages-reading-and-actions) · 23
- [Forwarding and copying](#forwarding-and-copying) · 5
- [Chat list, folders, tabs](#chat-list-folders-tabs) · 9
- [Inside a chat](#inside-a-chat) · 10
- [Groups, channels and members](#groups-channels-and-members) · 7
- [Channels: feed and reading](#channels-feed-and-reading) · 9
- [Stories](#stories) · 3
- [Photos and videos](#photos-and-videos) · 7
- [Voice and video messages](#voice-and-video-messages) · 2
- [Downloads, files, storage](#downloads-files-storage) · 5
- [Stickers, emoji, GIFs, reactions](#stickers-emoji-gifs-reactions) · 7
- [Calls](#calls) · 1
- [Translator and language](#translator-and-language) · 9
- [AI features](#ai-features) · 8
- [Profile and info](#profile-and-info) · 5
- [Search](#search) · 5
- [Notifications](#notifications) · 4
- [Network, proxies, bypassing blocks](#network-proxies-bypassing-blocks) · 4
- [Appearance and themes](#appearance-and-themes) · 5
- [Fonts, icons, animations](#fonts-icons-animations) · 4
- [Navigation and gestures](#navigation-and-gestures) · 4
- [Premium features (local)](#premium-features-local) · 2
- [Ads and clutter](#ads-and-clutter) · 3
- [Bots, mini apps, automation](#bots-mini-apps-automation) · 3
- [Crypto, wallet, payments](#crypto-wallet-payments) · 7
- [Business and teams](#business-and-teams) · 7
- [Backups and export](#backups-and-export) · 7
- [Accessibility](#accessibility) · 1

## Accounts and sign-in

| Feature | What it does |
|---|---|
| **Unlimited accounts** | More than 3 accounts (Premium has 6) — up to 10/16/32/100/999, the limit is local only |
| **Account color/label** | Give each account its own color so you don't mix up which one you're writing from |
| **Account order** | Drag accounts to reorder them in the menu, set custom account names |
| **Sign in with QR code** | Sign in by scanning a QR code from another device, no SMS |
| **Advanced session management** | Shows IP, app, session api_id, and lets you terminate sessions in bulk |
| **Cloud sync of client settings** | Onegram settings are stored in Saved Messages/on your own server and carried over to other devices |
| **Settings backup/restore via file** | Export all client settings to a file |
| **Username check and search** | Whether a @username is free, who owns it, whether it is for sale on Fragment; finding free variants from a word (prefixes, digits, leet, transliteration) and claiming for yourself or your channel |

## Privacy and ghost mode

| Feature | What it does |
|---|---|
| **Hide your number in the interface** | Don't show your number in the menu/profile (for streams and screenshots) |
| **Streamer mode** | Hide names, avatars, numbers and previews; the window is hidden from screen recording |
| **Block screenshots and screen recording** | For the whole app or only for chosen chats |
| **Hidden chats** | Chats disappear from the list, search and notifications; opened with a gesture/code |
| **Passcode for individual chats/folders** | A separate PIN/biometrics for specific chats |
| **Strip metadata from photos** | Remove EXIF/XMP/geolocation before sending |
| **Remove tracking from links** | Strip utm/fbclid and similar from sent links |
| **No telemetry or crash reports** | AppCenter/Firebase Analytics/Crashlytics removed |
| **PGP/E2E over regular chats** | Custom end-to-end text encryption if both sides have Onegram |
| **Auto-delete your messages on a timer** | Your messages are deleted after a set time in all chats |
| **"Delete for everyone" by default** | The "also delete for the other person" checkbox is always on |
| **Hide the app in recents** | Blur/hide the preview in the app switcher |
| **Incognito keyboard** | The keyboard doesn't remember what you type |
| **Show "last seen" only to favorites** | Fine-tune privacy on a single screen |

## Deleted and edited messages

| Feature | What it does |
|---|---|
| **Delete more than 100 messages at once** | Bulk-delete your own messages in a chat/group |
| **Delete all your messages in a group** | Erase everything you wrote in the selected group with one button |

## Protected content and self-destruct

| Feature | What it does |
|---|---|
| **More timers in secret chats** | Custom self-destruct intervals |

## Messages: sending

| Feature | What it does |
|---|---|
| **Scheduled sending (extended)** | Quick presets: "in 1 hour", "tomorrow morning", "when they're online" |
| **Silent sending by default** | Messages are sent without sound in selected chats |
| **Confirm before sending** | Confirmation dialog for stickers/voice messages/GIFs/calls |
| **Repeat message (+1)** | A button to send the same message again |
| **Templates and quick phrases** | Saved reply snippets, inserted with / or a button |
| **Auto-reply** | Automatic reply to incoming messages (when away, by keywords) |
| **Mention several people at once** | Pick multiple members to tag |
| **Send text as a voice message** | Speech synthesis from text into a voice message |
| **Send long text in parts** | Automatically split text longer than 4096 characters |
| **Send photos/videos as files without compression** | Uncompressed by default, original quality |
| **HD photo quality by default** | Always send photos in maximum resolution |
| **Video without compression/bitrate choice** | Custom bitrate and resolution when sending video |
| **Video messages with the rear camera** | Record a video message with the main camera |
| **Video message from a gallery video** | Send an existing video as a video message |
| **Higher voice message bitrate** | Voice messages in the best quality |
| **Voice changer** | Voice effects for voice messages and calls |
| **Text sticker/quote image** | Turn a message into a quote image |
| **Drafts on all devices and a list** | A separate screen with all drafts |
| **Send cancel window** | A few seconds to cancel a sent message (before delivery) |
| **Send GIF as video and vice versa** | Conversion on send |

## Messages: reading and actions

| Feature | What it does |
|---|---|
| **Message link in any chat** | Including private groups (t.me/c/...) |
| **Message details** | ID, DC, date with seconds, forwarded source ID, message JSON |
| **Time with seconds** | 12:30 → 12:30:15 in the message time |
| **Full date in the bubble** | 12:30 → 07.11 12:30: date next to the time on older messages |
| **Jump to the first message** | "To the start of the chat" button |
| **Quick actions in the context menu** | A customizable set of message menu items |
| **Double-tap action** | Reaction/reply/copy/save — your choice |
| **Message swipe action** | Swipe = reply/forward/copy/save |
| **Translate message in place** | See the "Translator" section |
| **Save to Saved Messages in one tap** | A button in the message menu |
| **Local pins** | Pin a message only for yourself |
| **Message bookmarks** | Mark a message and find it in a separate list |
| **Message reminder** | "Remind me in an hour" — a scheduled message to yourself |
| **Merge consecutive messages** | Group messages from the same author without tails |
| **Fully hide blocked users** | Don't show messages/reactions from blocked users in groups |
| **Message filter by words/regex** | Hide messages with stop words in groups |
| **Original date of forwarded messages** | Show the original date on forwarded messages |
| **Forward counter on posts** | Show the number of forwards next to views |
| **Undo/redo actions** | Undo for delete/archive/edit |
| **Recognize text in photos (OCR)** | Copy text from an image |
| **Unread summary** | AI summary of a long chat/channel |
| **Share to other messengers** | Quickly share a message to WhatsApp/Viber, etc. |
| **Show message as JSON** | In message details: raw fields of a Telegram message (ids, dates, entities, media info) indented, with search, copy and share; no secrets |

## Forwarding and copying

| Feature | What it does |
|---|---|
| **Forward without author** | Forward as your own message (without "Forwarded from") |
| **Forward without caption** | Remove the media caption when forwarding |
| **Edit before forwarding** | Change the text of a forwarded message as if it were yours |
| **Copy several messages as text** | Multi-select → copy with names and time |
| **Scheduled forwarding** | Forward on a schedule |

## Chat list, folders, tabs

| Feature | What it does |
|---|---|
| **Auto tabs by type** | Automatic tabs: private, groups, channels, bots, unread |
| **Hide the "All chats" tab** | Work only with folders |
| **Unlimited folders locally** | More folders than the server allows |
| **Unlimited pinned chats** | Pins beyond the server limit (local) |
| **Default folder on launch** | Open the selected folder |
| **Chat sorting** | By unread, by activity, by type |
| **Compact list** | Smaller row height, no previews |
| **Hide the floating "pencil" button** | Start a new chat from the menu |
| **Channels separate from chats** | A dedicated "Channels" screen/tab |

## Inside a chat

| Feature | What it does |
|---|---|
| **Avatars next to messages** | Show/hide avatars, size |
| **Wide channel posts** | Stretch posts to full width |
| **Input field buttons** | Choose buttons: stickers, commands, scheduled messages, voice/video message |
| **Hide keyboard on scroll** | Keyboard behavior |
| **Per-chat font size** | Different text size for different chats |
| **Hide reactions** | Don't show reactions under messages |
| **Don't count mentions in muted chats** | Silent mentions |
| **Read message aloud** | Text-to-speech for incoming messages |
| **Auto-translate chat** | Everything incoming in the chat is translated automatically |
| **Notes about a contact** | A local note on a contact/chat |

## Groups, channels and members

| Feature | What it does |
|---|---|
| **Advanced admin tools** | Quick ban/mute from the message menu, action log |
| **Auto-decline deleted accounts in join requests** | Decline "Deleted Account" requests |
| **Local group statistics** | Member activity, top posters based on loaded history |
| **Show admins and their rights** | List of admins with rights from the menu |
| **Member join date** | When the user joined the group |
| **Moderation mode for large communities** | Message queue, quick actions, spam filters |
| **Keyword monitoring in groups** | Notification/action when a word is mentioned in any group |

## Channels: feed and reading

| Feature | What it does |
|---|---|
| **Feed from all channels** | All channel posts in one chronological feed (like in Graph) |
| **Feed per folder** | A separate feed for each channel folder |
| **Channel guest mode** | Read public t.me/s/ channels without signing in |
| **Collapse long posts** | Show the first paragraph |
| **Collapse ad posts by keywords** | Hide posts with stop words ("advertisement", "erid") |
| **Read later** | Save posts to "read later" |
| **Channel video catalog** | Channel videos as a media library (movies/series) |
| **Comments under a post without leaving** | Expand comments in the feed |
| **Channel tags and grouping** | Your own tags for channels, filter |

## Stories

| Feature | What it does |
|---|---|
| **Hide stories completely** | Remove the stories bar from the chat list |
| **No auto-advance to the next story** | Playback control |
| **Post stories in high quality** | No recompression |

## Photos and videos

| Feature | What it does |
|---|---|
| **Open in external player** | Stream to VLC/MX/mpv |
| **Auto-blur faces before sending** | Privacy protection |
| **Download in original quality** | Always download the maximum resolution |
| **Custom save folders** | Separate folders per chat |
| **Save a frame from a video** | Frame screenshot |
| **Media converter** | Convert video/audio inside the client |
| **Music: library and player** | All the music from your chats in one place: Albums (your own playlists) · Channels · Bots · Chats, search, queue, shuffle and repeat, sleep timer, "Show in chat", "Save to Cloud / Music". Plays through Telegram's player |

## Voice and video messages

| Feature | What it does |
|---|---|
| **Voice message transcription** | Text from voice messages (Premium on Telegram) |
| **High-quality video messages** | Higher resolution |

## Downloads, files, storage

| Feature | What it does |
|---|---|
| **Faster file uploads** | More parallel parts when uploading |
| **Built-in file manager** | Browse downloads by folder |
| **Telegram as a cloud drive** | Folders and files in Saved Messages as a drive |
| **Open file in another app** | System "Open with" |
| **Archive/PDF preview inside the app** | Open ZIP/PDF without external apps |

## Stickers, emoji, GIFs, reactions

| Feature | What it does |
|---|---|
| **Sticker size** | Sticker size slider |
| **Disable Premium sticker animations** | No full-screen effects |
| **System emoji / other sets** | Apple, Google Noto, Twemoji, Samsung, custom set |
| **More recent stickers/GIFs** | Increased limit for recents |
| **Download sticker as a file** | PNG/WebP/TGS/WebM |
| **No reaction animation** | Simplified reactions |
| **GIF search via different services** | Klipy/Tenor/Giphy |

## Calls

| Feature | What it does |
|---|---|
| **Confirm before calling** | Avoid accidental calls |

## Translator and language

| Feature | What it does |
|---|---|
| **Translator selection** | Google, Yandex, DeepL, Microsoft, Lingva, LibreTranslate, Telegram |
| **Translation via LLM** | GPT/Claude/Gemini for high-quality translation |
| **Offline translation** | ML Kit/Firefox local translations without a network |
| **Translate outgoing before sending** | Write in Russian — it's sent in English |
| **Auto-translate the whole chat** | Translate all incoming messages in the selected chat |
| **Translate the entire chat history** | Batch translation |
| **Translate bot buttons and polls** | Translate the bot interface |
| **Show original under the translation** | Dual text |
| **Don't translate selected languages** | Exclusion list |

## AI features

| Feature | What it does |
|---|---|
| **AI assistant in the client** | Chat with an AI model inside the app |
| **Model selection** | GPT, Claude, Gemini, DeepSeek, local models |
| **Your own API key** | The user enters their own OpenAI/Anthropic/OpenRouter key |
| **Reply suggestions** | AI suggests reply options for a message |
| **Rewrite my text** | Make it politer/shorter/fix mistakes |
| **Chat summary** | A brief on what's unread |
| **Image generation** | Create an image/avatar from a prompt |
| **AI voice message transcription** | See "Voice messages" |

## Profile and info

| Feature | What it does |
|---|---|
| **Show user/chat IDs** | ID in the profile, tap to copy |
| **User's data center** | Show DC1–DC5 in the profile |
| **Approximate registration date** | Estimated from the account ID |
| **Extended channel/group info** | Creation date, DC, type, restrictions |
| **Copy name/bio with a long tap** | Easy copying |

## Search

| Feature | What it does |
|---|---|
| **Offline search in loaded history** | Fast local index, CJK |
| **Tags in Saved Messages** | Search saved items by tag |
| **Fuzzy chat search** | Like Telescope/fzf |
| **Search by ID and tg:// link** | A user or chat number and tg://user?id= / tg://openmessage links in search find that chat |
| **Channel catalog** | Built-in channel catalog and collections |

## Notifications

| Feature | What it does |
|---|---|
| **Notifications per folder** | Different sounds and rules for each folder |
| **Keyword notifications** | Alert when a word is mentioned in any chat |
| **Quiet hours** | Silent mode schedule |
| **Auto-dismiss notifications** | Remove notifications after a while |

## Network, proxies, bypassing blocks

| Feature | What it does |
|---|---|
| **Built-in proxy list** | Ready-made MTProxy/SOCKS5, ping check |
| **IPv6 priority** | IPv4/IPv6 settings |
| **Custom DNS/DoH and DNS cache** | Protection against DNS poisoning |
| **Kill switch for proxy and Tor** | If the proxy or Tor fails, nothing goes direct: Telegram stays offline, Onegram's requests and mini apps go through the same SOCKS5 or are blocked; a red «No protected connection» bar with a choice of another proxy |

## Appearance and themes

| Feature | What it does |
|---|---|
| **Wallpaper colors** | The theme in the colors of your wallpaper (Android 12 and newer) |
| **AMOLED black theme** | Pure black background |
| **Avatar shape** | Circle, rounded square or square |
| **Hide interface elements** | Gift buttons, Stars, Premium banners, stories |
| **No number rounding** | 1.2K → 1,234: the full number, no abbreviations |

## Fonts, icons, animations

| Feature | What it does |
|---|---|
| **Custom font** | System, Google Sans, any TTF |
| **Change app icon** | A set of icons to choose from |
| **Animation speed / disable animations** | Speed them up or remove them |
| **Custom splash screen** | Branding |

## Navigation and gestures

| Feature | What it does |
|---|---|
| **Open chat tabs** | Like browser tabs |
| **Full keyboard control** | Hotkeys (for tablets/desktop) |
| **Media viewer hotkeys** | Desktop |
| **Quick chat switcher** | Find a chat by shortcut |

## Premium features (local)

| Feature | What it does |
|---|---|
| **Hide Premium promos** | No reminders to buy Premium |
| **Free transcription** | Own (local/server) instead of Premium |

## Ads and clutter

| Feature | What it does |
|---|---|
| **Hide gifts/Stars/gift buttons** | Clean interface |
| **Hide birthday reminders** | No promos |
| **Hide channel/bot recommendations** | No "similar channels" |

## Bots, mini apps, automation

| Feature | What it does |
|---|---|
| **Bot catalog** | Built-in bot store |
| **Convenient command panel** | Command search, favorites |
| **Message scheduler** | Scheduled broadcasts to your own chats |

## Crypto, wallet, payments

| Feature | What it does |
|---|---|
| **Built-in non-custodial wallet** | Your own keys, multichain |
| **Send crypto in chat by @username** | Send tokens to the person you're chatting with |
| **TON integration** | TON Connect, TON wallet, NFT usernames |
| **Token swap** | Swaps via 1inch/aggregators |
| **Crypto gifts/giveaways in chats** | "CryptoBoxes" |
| **Secure deals (escrow)** | Guarantor deals in stablecoins |
| **Currency/crypto rates in chat** | Convert amounts in messages |

## Business and teams

| Feature | What it does |
|---|---|
| **Team workspace** | Shared folders, roles, tasks |
| **Mini CRM for chats** | Client statuses, labels, funnel |
| **Customer support mode** | Distribute conversations among operators |
| **Chat labels** | Colored tags on chats |
| **Reply analytics** | Response time, workload |
| **Client notes** | Contact card |
| **Onegram Business** | A screen like “Telegram Business” without Premium: quick replies (templates with /commands), a greeting for new customers, “Away” by opening hours, chat links with text and QR, address and hours added to your profile bio on tap, chatbots — rules and an AI agent. With Telegram Premium the rows open Telegram’s screens |

## Backups and export

| Feature | What it does |
|---|---|
| **Export chat** | To HTML/JSON/TXT right from your phone |
| **Backup to Saved Messages** | Keep client settings and notes in the Telegram cloud |
| **Built-in notepad** | Notes inside the client |
| **QR generator** | QR for links and contacts |
| **Local message archive** | A full copy of history on the device for search |
| **Export contacts to a VCF file** | Telegram contacts (name, number, @username in the note) to a .vcf file via the system file picker; asks before including numbers |
| **Settings backup** | All of the client's settings in a file (format version, client, date), restore with a preview of the changes and a confirmation, «Copy settings from another account». Passwords, PIN codes, keys, sessions and the wallet are never included |

## Accessibility

| Feature | What it does |
|---|---|
| **Haptics settings** | Turn haptic feedback on or off |

---

[Back to README](../README.md) · [Download Onegram](https://github.com/onegramteam/onegram/releases/latest)
