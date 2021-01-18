**Reminder - no plan survives breakfast.**

- Self-check: is everything working!
- **Gah! Yet again, no episode next week (May 10th, 2017)!**
    - https://www.reddit.com/r/WatchPeopleCode
- [100th Episode Survey](https://docs.google.com/forms/d/1xLPJFRB3nZfD8q3H-o8r6AwAGNMFRkM83b00gKEiTNU/viewform?edit_requested=true) **<-- Last chance!**
- Help make Firefox Faster! https://perf-html.io/ [Gather a profile, and then](https://developer.mozilla.org/en-US/docs/Mozilla/Performance/Reporting_a_Performance_Problem)[Gimme your Performance Profiles!](https://docs.google.com/a/mozilla.com/forms/d/e/1FAIpQLSePiq1ifvrY6EzDowEdqKdb-tGGm-AvgG86ivU9ipv7FsggKQ/viewform)
    - ^-- This has not happened yet due to all of my travel. Soon!
- [Episode guide](https://github.com/mikeconley/joy-of-coding-episode-guide)
    - ^-- Got my first pull request!
- **Update**: [Bug 1336763 - Only message for permitUnload on tabs that have indicated that they contain a frame that has a beforeunload handler](https://bugzilla.mozilla.org/show_bug.cgi?id=1336763) - [Notes](https://www.evernote.com/l/AbKeOg5UmL9AP5SvyVt3bUbIrHALVOdG-UM)
    - This landed! Things are better!
    - https://mikeconley.ca/blog/2017/05/01/making-tabs-close-faster-in-multi-process-firefox/
    - FX_TAB_CLOSE_PERMIT_UNLOAD_TIME_MS: https://mzl.la/2qs9zwM
    - FX_TAB_CLOSE_TIME_ANIM_MS: https://mzl.la/2qrYvQD
- **Update**: [Bug 1352501 - Remove Reader Mode feature promotion panel](https://bugzilla.mozilla.org/show_bug.cgi?id=1352501) - [Notes](https://www.evernote.com/l/AbLhNefSWN5Iq78KCJYqlvcVImPdeHoC6VU)
    - Done! Landed!
- [Bug 1354194 - Write synchronous reflow and synchronous style flush tests for key interactions](https://bugzilla.mozilla.org/show_bug.cgi?id=1354194) - [Notes](https://www.evernote.com/l/AbIZsKPaC8dDKZ6Yj3blcTv8a4_l_HG91i4)
    - https://mikeconley.github.io/ohnoreflow/
    - https://developer.mozilla.org/en-US/Firefox/Performance_best_practices_for_Firefox_fe_engineers
- Mercurial changeset evolution and rewriting history
    - https://www.mercurial-scm.org/wiki/ChangesetEvolution
- Subscribe to The Joy of Coding in iTunes or Kodi: https://air.mozilla.org/feed/itunes/livehacking
- **We'd love for other people in the Mozilla community to start livehacking! Come talk to mconley #livehacking.**

**Rate this episode: **https://goo.gl/forms/yIYOwtd4EpuPGjYA2

**Chat**

- [IRC](https://wiki.mozilla.org/IRC)
- We're in irc.mozilla.org in [#livehacking](http://client00.chat.mibbit.com/?channel=%23livehacking&server=irc.mozilla.org).
- I’ve also got my IRC client signed into the Twitch chat
- [This is a link to a web client that you can use to chat with me from your browser](https://client00.chat.mibbit.com/?channel=%23livehacking&server=irc.mozilla.org)

**Links**

- [Facebook Page for The Joy of Coding](https://www.facebook.com/TheJoyOfCoding1/)
- The Joy of Diagnosis!: https://www.youtube.com/watch?v=UL44ErfqJXs
- Livehacking on Air Mozilla: https://air.mozilla.org/channels/livehacking/
- [The Joy of Automation with Armen](https://www.youtube.com/channel/UCBgCmdvPaoYyha7JI33rfDQ)
- I've been mirroring the episodes to YouTube: https://www.youtube.com/playlist?list=PLmaFLMwlbk8wKMvfEEzp9Hfdlid8VYpL5
- [The Joy of Illustrating - Episode 1](https://www.youtube.com/watch?v=5g82nBPNVbc) - Watch @mart3ll blow your mind with designs from the Mozilla Creative team!
- [Lost in Data](https://air.mozilla.org/lost-in-data-episode-1/) - sheriffing performance regressions in pushes for Firefox
- [The Hour of Design](https://www.youtube.com/watch?v=8_Ld4hOU1QU) - watch one of our designers demystify the design process!
- [Code Therapy with Danny O’Brien](https://www.youtube.com/channel/UCDShi-SQdFVRnQrMla9G_kQ)
- Watch a developer put together a Windows game from scratch (no third-part engines) - really great explanations: https://handmadehero.org/
- [/r/WatchPeopleCode](https://www.reddit.com/r/WatchPeopleCode) for more livehacking!
- Watch @mrrrgn code to techno: https://www.youtube.com/channel/UC9ggHzjP5TepAxkrQyQCyJg
- M8 bugs: https://bugzilla.mozilla.org/buglist.cgi?quicksearch=cf_tracking_e10s%3Am8%2B&list_id=12396117

**Glossary**

- e10s ("ee ten ESS") - short for [Electrolysis, which is the multi-process Firefox project](https://wiki.mozilla.org/Electrolysis)
- CPOW ("ka-POW" or sometimes "SEE-pow") = Cross-Process Object Wrapper. [See this blog post.](http://mikeconley.ca/blog/2015/02/17/on-unsafe-cpow-usage-in-firefox-desktop-and-why-is-my-nightly-so-sluggish-with-e10s-enabled/)
- Serialize - "turn a complex object into something that can be represented as primitives, like strings, integers, etc"
- Deserialize - "turn a serialized object back into the complex object”
- BHR - “Background Hang Reporter”, a thing that records information about when Firefox performs poorly and sends it over Telemetry

**Feedback**

- [@mike_conley on Twitter](https://twitter.com/mike_conley)
- mconley in IRC on irc.mozilla.org
- [mikeconley.ca/blog](http://mikeconley.ca/blog/)