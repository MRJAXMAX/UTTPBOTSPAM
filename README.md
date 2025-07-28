🔒 UTTP BOT SPAM — Unicode Obfuscation Detection

🚨 Goal

To expose, document, and develop defenses against the UTTP (YouTube Troll Police) spam bots currently flooding YouTube comment sections with obfuscated unicode text, fake authority language, and algorithm-exploiting comments.

These bots attempt to evade moderation and manipulate engagement through:

Mass posting with identical wording

Use of U+202E (Right-to-Left Override) to hide keywords

Fake usernames mimicking law enforcement (e.g., UTTPColonelJack)

Disrupting comment sections with psychological warfare phrases like:

“1ST WARNING TROLL!”

“MY VIDEO IS BETTER THAN THIS INCOHERENT & SOULLESS ___”

🧠 What Is UTTP?

The "YouTube Troll Police" (UTTP) originated as a satirical or trolling group but has evolved into a toolset or spam ring used to:

Spread malware links (in some variants)

Inflate engagement stats

Harass creators or channels

Test moderation thresholds using unicode exploits

🧪 Technical Analysis

Unicode Exploit: U+202E = Right-to-Left OverrideExample:

G‮POLSYO  →  OYSLPOG

Looks normal in UI, but scrambles moderation filters.

Common Bot Message Pattern:

1ST WARNING TROLL! MY VIDEO IS BETTER THAN THIS INCOHERENT & SOULLESS G‮POLSYO
UTTP’S FAR BETTER THAN WHATEVER THIS NONSENSE IS...

Bot Traits:

Names use military ranks: Captain, Colonel, Sergeant

All caps + "UTTP" prefix

Repeat same message across videos

⚔️ Next Steps

Document every unique bot account name seen.

Build a regex scanner to detect U+202E in YouTube comment logs.

Create a browser plugin to auto-flag or hide spam comments using this technique.

Alert YouTube and relevant moderation teams.

Raise awareness by posting the repo in mod/security/dev forums.

🧷 License

This repo is for educational and research purposes.No harassment or doxxing is supported or tolerated.
