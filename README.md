# Aaradhana content

Hosts the message library for the Aaradhana app.

- `messages.json` — all messages, verses, stories and songs
- `manifest.json` — version number + the public URL of `messages.json`

## Publishing an update

1. Replace `messages.json` with the new file.
2. Increase `version` in `manifest.json` by 1.
3. Commit. Nothing else.

Installed apps pick it up on their next check (at most every 6 hours), without reinstalling.
