<p align="center">
  <img src="app/data/icons/hicolor/scalable/apps/de.christophlangner.ScreenForge.svg" alt="ScreenForge icon" width="128" height="128">
</p>

<h1 align="center">ScreenForge</h1>

<p align="center"><strong>Your screenshots, ready to show.</strong></p>

<p align="center">
  Put several smartphone screenshots side by side on one image, on a background that looks designed,
  ready for a blog post, a store listing or social media. A native GTK&nbsp;4 and libadwaita app that works entirely offline.
</p>

<p align="center">
  <a href="docs/DEVELOPMENT.md#flatpak"><strong>Build the Flatpak</strong></a>
  &nbsp;·&nbsp; Flathub: planned &nbsp;·&nbsp;
  <a href="CHANGELOG.md">Changelog</a>
</p>

<p align="center">
  <img src="docs/screenshots/main-window.png" alt="ScreenForge with three phone screenshots on a generated background and the variant grid in the sidebar" width="100%">
</p>

## What it does

<table>
<tr>
<td width="33%" valign="top">

### Phones, tablets, browsers, in perspective

Put each screenshot into a generic phone with a punch-hole camera, a tablet
or a browser window, dark or light. Turn and lean them in real perspective,
or fan them out so the outer ones face the middle.

</td>
<td width="33%" valign="top">

### Point things out, hide what's private

Give each screenshot a label (a capsule on it, a caption below or a headline
above, always sized to the screenshot) and add callouts that point at a
detail. Black out, pixelate or blur e-mail addresses and other private bits
before you share: drag a rectangle over them right on the screenshot, then
move or resize it there.

</td>
<td width="33%" valign="top">

### At home on GNOME

Adaptive layout, a tabbed sidebar, keyboard shortcuts and undo for every
edit. Open images from the file manager, take a desktop screenshot through
the system dialog, or import from an Android device over adb, with a clean
status bar showing 12:00 and a full battery.

</td>
</tr>
</table>

<table>
<tr>
<td width="55%">
<img src="docs/screenshots/example-output.jpg" alt="An exported image: three phone screenshots on a purple background with concentric arcs and a watermark" width="100%">
</td>
<td valign="middle">

### Screenshots in, presentation image out

Drop in a few screenshots, paste them from the clipboard or take them
straight from your Android phone. ScreenForge lines them up, scales them to
a common size and adds shadows and rounded corners. Horizontal, vertical,
grid, or free placement with snapping and alignment tools.

### Scenes and presets

Every composition is kept as a scene with all its settings: the start screen
shows them as preview cards to reopen, rename, duplicate or delete, and they
save themselves. Export a scene as a `.screenforge` file to share it, and
reuse your look as presets, also from the command line:
`screenforge --preset Blog --output shots.png *.png`.

</td>
</tr>
</table>

<table>
<tr>
<td valign="middle">

### Backgrounds that look designed

The background generator draws abstract scenes in twelve styles: layered
paper, concentric arcs, silk ribbons, folded planes, line bundles, soft mist,
paper-cut contours, pebbles, mesh gradients, low-poly facets, Bauhaus
geometry and a quiet style that keeps two or three brand colors exactly as
they are. It is [Prospekt](https://github.com/freiversum/prospekt), a
library of its own. Colors come in harmonious palettes, vivid, light or dark,
or taken from your screenshots, and a color strength setting takes them from
soft, slightly pastel tones to deep, saturated ones.

### Six variants, nine previews

Don't like it? The sidebar always offers six variants, and the background
studio shows nine large previews of your actual composition. Plain colors,
gradients, your own image or a blurred copy of a screenshot work too.

</td>
<td width="55%">
<img src="docs/screenshots/background-studio.png" alt="The background studio with nine variants of the arcs style" width="100%">
</td>
</tr>
</table>

<table>
<tr>
<td width="55%">
<img src="docs/screenshots/export.png" alt="The export tab with format presets, transparent background and watermark settings" width="100%">
</td>
<td valign="middle">

### The right size for every place

Keep the canvas fitted to the content or pick a format: 16:9, square, 4:5,
story, Open Graph, Mastodon and Bluesky, the Play Store feature graphic or
App Store sizes. Your content stays centered and is never cropped. Split a
composition into several images with one continuous background for app
store panoramas, or export a short animated WebM in which the screenshots
fly in.

### Export in one go

Add a watermark with your logo, export the iPhone, iPad and Google Play
sizes in one go, export as PNG, JPEG, WebP, AVIF or PDF, with a transparent
background if you like, or copy the result to the clipboard and drag it
straight into a browser or chat.

</td>
</tr>
</table>

## At a glance

| | |
|---|---|
| **Runs on** | GNOME, as a native GTK&nbsp;4 and libadwaita app that works entirely offline |
| **Imports** | image files, the clipboard, a desktop screenshot, or an Android device over adb |
| **Exports** | PNG, JPEG, WebP, AVIF, PDF and animated WebM |
| **Languages** | English and German included |
| **Licence** | GPL-3.0-or-later |

## Install

ScreenForge isn't on Flathub yet. You can build and install the Flatpak from this repository with one script, or build it with meson; see [docs/DEVELOPMENT.md](docs/DEVELOPMENT.md).

## Translations

The interface is translated with gettext. German is complete; [po/README.md](po/README.md) explains how to add another language.

## License

[GPL-3.0-or-later](LICENSE)
