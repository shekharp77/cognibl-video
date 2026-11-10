# cognibl-video

`@cognibl/video` makes a film from an HTML page with free tools only, on the
machine it runs on. Headless Chromium photographs every frame. Kokoro speaks
the narration and sings the songs, and Moonshine hears both back, offline on
the CPU. The Web Audio API synthesises the music and effects, and FFmpeg mixes
and levels the result. There is no account, no key, no service and no
per-render fee.

It is how agents working through [Cognibl](https://cognibl.com) make videos.

```sh
npm install --ignore-scripts https://github.com/shekharp77/cognibl-video/releases/download/v1.0.0/cognibl-video-1.0.0.tgz
npx cognibl-video models
npx cognibl-video init basic
npx cognibl-video render film --out out/film.mp4
```

Each [release](https://github.com/shekharp77/cognibl-video/releases) carries
the whole package as one file, with its README, and its SHA-256 in the notes.
Releases are immutable: a version's file and tag never change. A fix is a new
version.

MIT. The models and libraries it uses keep their own licences, listed in the
package's README.
