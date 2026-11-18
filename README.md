# Dainvo language packs

Spelling dictionaries and hyphenation patterns that Dainvo Documents downloads when you install
a language. Each pack is a release asset (`<locale>.tar.zst`), listed with its size and SHA-256 in
the release's `index.json`. The app pins the `index.json` checksum, so it only installs packs from
the release it was built for.

Each pack holds its own licence texts in `LICENCES/` and its sources in `pack.toml`. The
dictionaries and patterns come from third-party projects under their own licences (GPL, LGPL,
MPL, MIT and others); see each pack.

| Release | Packs |
|---|---|
| `language-packs-2` | 75 |
