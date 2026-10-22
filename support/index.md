# Matsu support

_Last updated: 22 October 2026_

Matsu is an iPhone app for studying Japanese. It is a client for your own WaniKani account, with
extra vocabulary practice ("Gap Vocab") and JLPT-style practice tests (listening, grammar and
kanji). Matsu is unofficial: it is not affiliated with or endorsed by WaniKani or Tofugu.

**Need help?** Email **matsuapp.support@gmail.com**. Please say which iPhone and iOS version you
have, and what you tapped. Never send your WaniKani token or password.

Privacy policy: [see here](../privacy/).

## Getting started: your WaniKani token

Matsu needs a personal access token from your own WaniKani account. It takes about a minute:

1. Sign in at wanikani.com on any browser.
2. Go to **Settings ‚Üí API Tokens** and choose **Generate a new token**.
3. Give it a name (for example "Matsu"). Choose the permissions (see below).
4. Copy the token, open Matsu, tap **Add token**, paste it and tap **Check and save**.
5. Wait for the first sync. It downloads about 9,000 items and takes a minute or so; after that only
   changes are downloaded.

Matsu never asks for your WaniKani password.

## Questions

**Which permissions does the token need?**
Reading your data is always included. For full use, also tick the other three:
- *assignments:start* starts an item on WaniKani when you finish its lesson in Matsu.
- *reviews:create* saves your reviews to WaniKani.
- *study_materials:create / update* saves your own synonyms and notes.

**Can I use Matsu read-only?**
Yes. Make a token with none of those three ticked, then in Matsu open the WaniKani settings (gear icon)
and set **Access** to **Read-only**. Matsu then only reads your data. Lessons and reviews in Matsu are practice
and aren't sent to WaniKani. Choosing Read-only in Matsu also protects you if the token is more powerful than you intended.

**Does it work without internet?**
Lessons and reviews work offline: your answers are saved on your phone and sent to WaniKani when you're
back online, with the time you actually answered. Turn on **Offline audio** in WaniKani settings to save
WaniKani's recordings for words up to your level. Gap Vocab and the Tests tab work offline too, apart from needing
a first sync.

**Why can I only see levels 1 to 3?**
That's WaniKani's free plan. Matsu follows your account: if your WaniKani subscription changes, sync again.

**My token stopped working.**
WaniKani rejects it if it was deleted or regenerated. Make a new token (steps above) and paste it in
the WaniKani settings.

**How do reviews and Gap Vocab differ?**
WaniKani items are on WaniKani's schedule. Gap Vocab is extra vocabulary chosen to match the kanji you
know, with its own schedule on your phone, plus recall practice (English to Japanese). Tests are
practice only and never change any stage.

**What about the keyboards?**
The answer box switches between the Japanese and English keyboards for you. If you have no Japanese
keyboard, add one in iOS Settings ‚Üí General ‚Üí Keyboard ‚Üí Keyboards. Readings can also be typed in romaji.

**How do I back up and restore my Gap Vocab progress?**
Gap Vocab ‚Üí Settings ‚Üí **Export a backup‚Ä¶** makes one file (progress, review history, test scores and
settings). Save it to Files, iCloud Drive or send it to yourself. To restore (on this or a new phone),
open **Restore from a backup‚Ä¶** and choose the file. Restoring replaces what's on the phone. Your WaniKani
progress lives on WaniKani, and the backup doesn't contain your token: add it again on a new phone.

**How do I delete my data?**
Gap Vocab ‚Üí Settings ‚Üí **Delete all data** removes everything Matsu keeps on your phone: Gap Vocab progress,
test scores, your token, the copy of your WaniKani data, offline audio, widget data, reminders and
settings. Your WaniKani account isn't affected. Deleting the app does the same. To remove the token
from WaniKani too, delete it on wanikani.com ‚Üí Settings ‚Üí API Tokens.

**Can I turn reminders off?**
Yes: Gap Vocab ‚Üí Settings ‚Üí Reminders (also quiet hours), or iOS Settings ‚Üí Notifications ‚Üí Matsu.

**The widget shows old numbers.**
iOS decides how often widgets refresh. Open Matsu once to update it.

**Is my data sent anywhere?**
Only to WaniKani, with your token. Matsu has no account, no server, no analytics and no tracking. See the privacy policy.

**Does Matsu cost anything?**
Matsu is free. WaniKani has its own subscription, which is separate.

## Credits

Example sentences from Tatoeba, dictionary data from JMdict and KANJIDIC (EDRDG), and more: see
**About Matsu ‚Üí Sources & licences** in the app.
