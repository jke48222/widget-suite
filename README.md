# Übersicht Widget Suite

[![License](https://img.shields.io/github/license/jke48222/widget-suite)](LICENSE) ![Platform: macOS](https://img.shields.io/badge/platform-macOS-lightgrey) [![Übersicht gallery](https://img.shields.io/badge/%C3%9Cbersicht-gallery-informational)](https://tracesof.net/uebersicht-widgets/)

[Übersicht gallery](https://tracesof.net/uebersicht-widgets/) · [Widgets](#widgets) · [Install](#install)

A set of 16 widgets for [Übersicht](http://tracesof.net/uebersicht/), each built
as a distinct physical object rather than a card: a hardware sampler, a
split-flap departures board, an industrial control cabinet, a Braun-style
record player, a thermal receipt printer, a manila folder, a felt letter
board, a 1958 Predicta television, a velvet tarot table, a record-shop
pegboard, a marble-and-brass vitrine, an antique parchment globe, a
photographer's light table, a cross-stitch sampler in an embroidery hoop, a
live wallpaper, and a small robot that lives behind your windows. Each widget
lives in its own repository (linked below).

![The sixteen widgets composed on one desktop](homescreen.png)

## Widgets

|     |     |     |
|:---:|:---:|:---:|
| <a href="https://github.com/jke48222/animated-wallpaper-widget"><img src="thumbs/animated-wallpaper.png" width="260"><br><b>Animated Wallpaper</b></a><br><sub>A full-screen live WebGL shader wallpaper that animates behind your other widgets.</sub> | <a href="https://github.com/jke48222/clipboard-history-widget"><img src="thumbs/clipboard-history.png" width="260"><br><b>Clipboard History</b></a><br><sub>Your clipboard history printed by a thermal receipt printer, with pinning, secret masking, and kind filters.</sub> | <a href="https://github.com/jke48222/daily-ai-prompt-widget"><img src="thumbs/daily-ai-prompt.png" width="260"><br><b>Daily AI Prompt</b></a><br><sub>One daily AI prompt spelled out on a felt letter board; click to copy and open a new chat.</sub> |
| <a href="https://github.com/jke48222/daily-astronomy-photo-widget"><img src="thumbs/daily-astronomy-photo.png" width="260"><br><b>Daily Astronomy Photo</b></a><br><sub>NASA's Astronomy Picture of the Day, broadcast on a 1958 Predicta television.</sub> | <a href="https://github.com/jke48222/daily-tarot-widget"><img src="thumbs/daily-tarot.png" width="260"><br><b>Daily Tarot</b></a><br><sub>A daily Rider-Waite-Smith tarot card on a velvet table, with its upright or reversed reading.</sub> | <a href="https://github.com/jke48222/github-contributions-widget"><img src="thumbs/github-contributions.png" width="260"><br><b>GitHub Contributions</b></a><br><sub>Your GitHub contribution graph cross-stitched in an embroidery hoop, with streak and yearly total.</sub> |
| <a href="https://github.com/jke48222/now-playing-widget"><img src="thumbs/now-playing.png" width="260"><br><b>Now Playing</b></a><br><sub>The current track on a Braun-style record player: the record spins and the tonearm swings on while it plays.</sub> | <a href="https://github.com/jke48222/recent-album-covers-widget"><img src="thumbs/recent-album-covers.png" width="260"><br><b>Recent Album Covers</b></a><br><sub>The nine most recently played album covers standing on a record-shop pegboard.</sub> | <a href="https://github.com/jke48222/recent-downloads-widget"><img src="thumbs/recent-downloads.png" width="260"><br><b>Recent Downloads</b></a><br><sub>The three most recent files in your Downloads folder as sheets in a manila folder, with real macOS previews.</sub> |
| <a href="https://github.com/jke48222/rotating-3d-model-widget"><img src="thumbs/rotating-3d-model.png" width="260"><br><b>Rotating 3D Model</b></a><br><sub>A live, auto-rotating 3D model in a brass-and-marble museum vitrine; changes daily, offline fallback.</sub> | <a href="https://github.com/jke48222/spinning-globe-widget"><img src="thumbs/spinning-globe.png" width="260"><br><b>Spinning Globe</b></a><br><sub>An antique parchment desk globe with a red pin on every city you've visited.</sub> | <a href="https://github.com/jke48222/wallpaper-switcher-widget"><img src="thumbs/wallpaper-switcher.png" width="260"><br><b>Wallpaper Switcher</b></a><br><sub>Browse and set your desktop wallpaper from a photographer's light table of 35 mm slides.</sub> |
| <a href="https://github.com/jke48222/agent-fleet-widget"><img src="thumbs/agent-fleet.png" width="260"><br><b>Agent Fleet</b></a><br><sub>Every coding-agent session on your Mac: what each is doing, which ones are waiting on you, and today's tokens.</sub> | <a href="https://github.com/jke48222/keys-and-pads-widget"><img src="thumbs/keys-and-pads.png" width="260"><br><b>Keys & Pads</b></a><br><sub>A playable 16-pad drum machine with a 16-step sequencer and a two-octave piano, synthesized entirely in the widget.</sub> | <a href="https://github.com/jke48222/pi-fleet-widget"><img src="thumbs/pi-fleet.png" width="260"><br><b>Pi Fleet</b></a><br><sub>Your Raspberry Pis on an industrial control cabinet: reachability, temperature gauges, load, memory, disk, uptime, and throttling.</sub> |
| <a href="https://github.com/jke48222/window-pet-widget"><img src="thumbs/window-pet.png" width="260"><br><b>Window Pet</b></a><br><sub>A small robot that lives behind your windows: it stands on their edges, rides them, falls when they close, and sleeps when nothing happens.</sub> |  |  |

## Install

Install Übersicht if you don't have it:

```sh
brew install --cask ubersicht
```

Each widget is its own repo with a one-click installer. Clone the ones you want and run `./install.sh` in each; it copies the widget into Übersicht's widgets folder, installs any helper scripts, and runs setup where a widget needs it:

```sh
git clone https://github.com/jke48222/now-playing-widget.git
cd now-playing-widget && ./install.sh
```

Or download the `*.widget.zip` from a widget's latest release, unzip it into `~/Library/Application Support/Übersicht/widgets/`, and refresh Übersicht (menu bar icon → Refresh All). All 12 are also listed in the [Übersicht widget gallery](https://tracesof.net/uebersicht-widgets/). Some widgets can optionally connect to the Claude or Apple Music APIs; see each repo's README.

## License

MIT. See [LICENSE](LICENSE).

## Author


Jalen Edusei <jalen.edusei@gmail.com>
