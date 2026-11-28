# Plugins by Dani Koenig

Download page for my free macOS plugins (VST3, Audio Unit, CLAP). One stage on top, then one section per plugin.

| Plugin | Type | Repo |
|---|---|---|
| The One | Polyphonic synth | [TheOne](https://github.com/danikoenig/TheOne) |
| Siren | Drone synth | [siren](https://github.com/danikoenig/siren) |
| One Shooter | Sample player | [OneShooter](https://github.com/danikoenig/OneShooter) |
| Quad Shooter | 4-slot sample player | [QuadShooter](https://github.com/danikoenig/QuadShooter) |
| Drift Station | Drifting memory processor | [DriftStation](https://github.com/danikoenig/DriftStation) |
| Grinder | Step sequencer | [Grinder](https://github.com/danikoenig/Grinder) |
| Repetitor | MIDI generator | [Repetitor](https://github.com/danikoenig/Repetitor) |
| Knack | Clipper | [Knack](https://github.com/danikoenig/Knack) |
| Gain | Gain staging utility | [Gain](https://github.com/danikoenig/Gain) |
| Dub Delay | Reggae dub delay | [DubDelay](https://github.com/danikoenig/DubDelay) |
| Remember | Always-on recorder | [Remember](https://github.com/danikoenig/Remember) |

## Setup (GitHub Pages)

1. Create a new public repo, e.g. `danikoenig/plugins`, and upload `index.html`, `.nojekyll` and the `img` folder.
2. Settings > Pages > Source: "Deploy from a branch", Branch `main`, folder `/ (root)` > Save.
3. After about a minute the page is live at `https://danikoenig.github.io/plugins/`.

## How it updates

- Download buttons point to `releases/latest/download/<Name>-Installer.pkg`, so they always deliver the newest release. Manuals (EN + DE) come from `releases/latest/download/<Name>-Manual-EN.pdf` and `-DE.pdf`.
- The version badge is read live from the GitHub API. The version in `index.html` is only the fallback.

## Editing

All plugin texts are in the `plugins` list at the bottom of `index.html`.
To show a 'Watch reel' button, put the YouTube Shorts ID into `reel:''` (e.g. `reel:'hZExpdoyzUo'`).
New screenshot: replace the file in `img/`.
