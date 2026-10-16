# LittleRoots TV

Prototype of the LittleRoots streaming app for smart TVs (LG webOS, Hisense VIDAA), phones and browsers.

- `index.html`: the whole app. Videos from the LittleRoots YouTube channel play inside the app's own player.
- `tools/convert-to-hls.sh`: turns video files into streaming format for Cloudflare R2.
- `tools/README-video-hosting.md`: how to host your own videos on Cloudflare R2.
- `brand/littleroots-logo.svg`: the logo.

## Adding videos
Open `index.html`, find `CATALOG`, and add an entry with the YouTube video ID (`yt`), title, world, age range and description.
