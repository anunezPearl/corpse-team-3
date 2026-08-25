# Team 3: Emoji Translator

Type a word or sentence, get it translated into emoji.

## Status
Translation logic is in. Rules:

- Requests must start with the word "please" — otherwise the app just responds with 🤔.
- Rude or angry input gets called out: five ❗🤬 pairs instead of a translation.
- Otherwise, each word maps to an emoji (a small built-in dictionary, with a
  deterministic fallback emoji for unknown words).
- Output is always 3-9 emojis long, and every 3rd emoji is deliberately wrong
  (shown as 🤔), capped at 3 wrong emojis per translation.
