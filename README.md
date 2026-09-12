# Sawasdee audio packs

Static host for the native-speaker word recordings of the Sawasdee language app for the languages that are
not bundled in the APK. Layout per language: `<lang>/index.json` (clip index with source and licence per clip),
`<lang>/<wordId>.m4a` (AAC, mono, 24 kHz), optional `<lang>/cv-sentences.json` + `<lang>/s/<id>.m4a`.

Sources and licences: see `credits.json` and the `license` / `by` fields in each `index.json`
(Mozilla Common Voice CC0, Wiktionary/Wikimedia Commons CC BY-SA, FLEURS CC BY 4.0, Zeroth-Korean CC BY 4.0,
AISHELL-3 Apache 2.0). Published by `scripts/publishAudioPacks.sh` from the app repository.
