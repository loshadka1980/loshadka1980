# Orienteering Course Detection & GPX Alignment

Take a phone photo of your orienteering map, add the GPX track from your
watch, and get your route drawn on the map. The course is detected
automatically, and the track is placed on the photo without marking
reference points by hand.

![Orienteering map photo with the detected controls in cyan and the GPX track in magenta](https://modelusage-test.s3.eu-north-1.amazonaws.com/og_image.jpg)

## What it does

- Detects the course on a photo of a paper map: start, controls, finish,
  connecting lines, printed control numbers and the visiting order.
- Aligns a GPX track to the detected course, in the photo's own pixels.
- Works for sprint and forest orienteering maps, and for rogaine / score
  events where controls are visited in any order.

## Try it

- **Web app:** https://modelusage-test.s3.eu-north-1.amazonaws.com/index.html
  (free account needed)
- **Telegram bot:** [@otrack_overlay_bot](https://t.me/otrack_overlay_bot):
  send the map as a file and the `.gpx` track, and get the overlay back.
  No sign-up.

This is a test deployment and still being improved.

## Contact

rroschin (at) gmail (dot) com
