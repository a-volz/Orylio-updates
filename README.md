# Orylio Updates

Public signed metadata and download pages for two independent native Mac apps. Development sources remain private.

- [Companion downloads](https://a-volz.github.io/Orylio-updates/companion/) and [signed feed](https://a-volz.github.io/Orylio-updates/companion/appcast.xml)
- [Viewer downloads](https://a-volz.github.io/Orylio-updates/viewer/) and [signed feed](https://a-volz.github.io/Orylio-updates/viewer/appcast.xml)

**Orylio Companion 0.3.0** is available as a signed and notarized update: [release and downloads](https://github.com/a-volz/Orylio-updates/releases/tag/companion-v0.3.0). **Orylio Viewer 0.3.1** is also available as an independently signed and notarized update: [release and downloads](https://github.com/a-volz/Orylio-updates/releases/tag/viewer-v0.3.1). App releases use separate tags `companion-vX.Y.Z` and `viewer-vX.Y.Z`, each with its own signed/notarized DMG and matching manifest. A release never installs the other app. The companion installs its bundled Lightroom plugin on first start.

GitHub Pages serves the stable signed feeds. Do not use repository-wide `releases/latest` to select one product. The historical `feed-initial` asset/root appcast stays empty for development-client compatibility and is not the current distribution feed.

Public app releases and feed promotion are separate explicit actions. Private keys, credentials, catalogs, photos and development sources never belong here. Signed XML must not be modified without re-signing.

Version 0.3.0 adds chunked streaming of original Lightroom videos, bounded video preloading alongside photos, and playback that stops at collection boundaries. Update Companion first, then Viewer. Video codecs depend on the receiving device; original files must be reachable on the Companion Mac.

Viewer 0.3.1 starts manually selected videos automatically without advancing the collection after playback. The Mac viewer includes Apple Silicon and Intel architectures and requires macOS 26 or newer. Companion 0.3.0 remains compatible.
