# MobileApp
Mobile app Astra

## Pocket Piano

Current public site: https://abbas-pocket-piano.abbas1991.chatgpt.site

A responsive browser piano with mouse, multi-touch chords, computer keyboard controls, octave shifting, sustain, and volume. Tones are synthesized using the Web Audio API.

Open `dist/index.html` in a modern browser or serve `dist` with any static web server. No dependencies or build step required.

### Safari audio

Tap **Enable sound** once; it plays a short test note. The app requests the playback audio session on supported Safari versions, waits for audio activation, and provides a retry button after interruptions. If silent, raise media volume, check Bluetooth routing, and on older iPhones turn off Silent Mode.

### GitHub Pages

The ready-to-publish copy is `docs/index.html`. In repository Settings > Pages, choose Deploy from a branch, select `main` and `/docs`, and Save. After the deployment completes, the public address is https://abbas-karake-lb.github.io/MobileApp/ .

Keep `docs/index.html` identical to `dist/index.html` when updating the app. Pages republishes changes to `main` after the initial setup.
