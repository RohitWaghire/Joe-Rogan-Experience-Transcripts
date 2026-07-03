# Joe Rogan Experience Transcripts

Transcripts of **1,940 episodes** of the Joe Rogan Experience podcast, one Markdown file per episode (~390 MB of plain text).

## Structure

All transcripts live in [`Transcripts/`](Transcripts/), named:

```
Joe Rogan Experience #<episode> - <guest> [<YouTube video ID>].md
```

> **Note:** GitHub's web UI truncates folder listings at 1,000 files. Every episode is present — clone the repo or use GitHub search to access all of them.

## File format

Each file starts with a small header (title, YouTube URL, video ID) followed by timestamped caption lines:

```
# Joe Rogan Experience #1 - Brian Redban
# https://www.youtube.com/watch?v=ZWBCnvOuXK8
# video_id: ZWBCnvOuXK8

[00:01] start
[00:05] broadcast and
...
```

Transcripts are machine-generated from YouTube captions, so expect the usual auto-caption quirks (no speaker labels, occasional mishears).

## Usage

```bash
git clone https://github.com/RohitWaghire/Joe-Rogan-Experience-Transcripts.git

# search every episode for a phrase
grep -ril "chimp strength" Transcripts/
```

## Disclaimer

This is an unofficial, fan-made archive for research and educational use. All rights to the underlying audio, video, and spoken content belong to Joe Rogan / the Joe Rogan Experience. This repository is not affiliated with or endorsed by the show. If you are a rights holder and want content removed, open an issue.

## License

The compilation, structure, and tooling of this repository are released under the [MIT License](LICENSE). The MIT license does **not** apply to the underlying episode content, which remains the property of its original rights holders.
