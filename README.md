# Nirthika's Birthday Website

Open `dist/index.html` in a web browser. Select **Begin our story** to enter the
site and start the birthday song.

## Change the photos

The gallery uses these files from `dist/assets/`:

- `086.jpg`
- `155A8922.jpg`
- `236.jpg`
- `524.jpg`
- `_DSC8586.jpg`

Replace a photo while keeping the same filename to update the gallery without
changing the HTML.

## Change the song

The page tries `dist/assets/our-song.mp3` first, then falls back to
`dist/assets/our-song.m4a` if the MP3 is missing or fails to load. The song
starts when the visitor selects **Begin our story**, which satisfies browser
audio-playback rules requiring a user interaction.

To use your own song, drop a real MP3 file in as `dist/assets/our-song.mp3`
(overwriting the placeholder there). No HTML changes are required.
