# HOAMI Music

**Better tags for the music you own.** Free, open source, runs on your own computer.

HOAMI Music is a tagging tool for personal music collections. It is made mainly for:

- **CDs you own, ripped to lossless files** (FLAC),
- **digital albums you bought** as lossless downloads.

It looks up each album in open music databases and fills in what your files are missing:
artist and album names in their native spelling, the original release year, track credits,
genres and styles, identifiers, cover art and lyrics.

When it is not sure which release your files come from, it does not guess.
It asks you to point it to the right release page instead.

## Status

Early development. Today it is a command-line script for Windows; a simple desktop app is planned.
There is no public release yet.

## Principles

- **Always free.** No paid version, no premium features, no ads.
- **Open source**, under GPL-3.0-or-later.
- **Runs locally.** There is no HOAMI server and no account.
- **Your own API keys** for the services that need one.
- **Accuracy over speed.** Missing data is better than wrong data.
- **Only data we may use:** open data (CC0, or CC BY-SA with attribution) and services whose terms allow it.

## Data sources

Main sources: MusicBrainz, Discogs, Wikidata, Wikipedia, ListenBrainz, AcoustID and LRCLIB.
The full list of sources, their licenses and required attributions ships with every data package (`ATTRIBUTION.md`).

Thank you to these projects and the people who build them. HOAMI Music is not affiliated with any of them.

## For service operators

HOAMI Music identifies itself in every request with a User-Agent like:

```
HOAMI-Music/<version> ( https://github.com/piotrekslowik/hoami-music )
```

If you see a problem with our traffic, please [open an issue](../../issues) and we will fix it.

## License

GPL-3.0-or-later.
