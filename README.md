# Orienteering Course Detection & GPX Alignment

Take a phone photo of the orienteering map, add the GPX track, and get your route drawn on the map without marking
reference points by hand.

![Orienteering map photo with the detected controls in cyan and the GPX track in magenta](https://modelusage-test.s3.eu-north-1.amazonaws.com/og_image.jpg)

## What it does

- Detects the course on a photo of a paper map: start, controls, finish,
  connecting lines, printed control numbers and the visiting order.
  Works for "standard" sprint and forest orienteering maps, and for a variety rogaine / score-o maps
- Aligns a GPX track to the detected course (track -> pixel). Handle both ordered and unordered controls.

## Try it

- **Web app:** https://modelusage-test.s3.eu-north-1.amazonaws.com/index.html
  (free account needed)
- **Telegram bot:** [@otrack_overlay_bot](https://t.me/otrack_overlay_bot):
  send the map as a file and the `.gpx` track, and get the overlay back.
  No sign-up.

This is a test deployment and still being improved.

## In progress

- Handling paper deformation (folds)

## Contact

rroschin (at) gmail (dot) com
