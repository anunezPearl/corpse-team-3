# Team 3: Emoji Translator

Type a word or sentence, get it translated into emoji.

## Status
Translation logic is in. Rules:

- Requests must start with the word "please" — otherwise the app responds with 🌱.
- Rude or angry input gets called out with five 🌩️🌵 pairs instead of a translation.
- Otherwise, each word maps to a nature-related or flag emoji (a small built-in
  dictionary, with a deterministic nature/flag fallback for unknown words).
- Output is always 3-9 emojis long, and every 3rd emoji is deliberately wrong
  (shown as 🌱), capped at 3 wrong emojis per translation.
- The emoji library is restricted to nature-related and flag emojis, including
  fallbacks and special responses.
