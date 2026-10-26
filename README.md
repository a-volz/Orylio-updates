# Orylio Updates

Public signed metadata and download pages for two independent native Mac apps. Development sources remain private.

- [Companion downloads](https://a-volz.github.io/Orylio-updates/companion/) and [signed feed](https://a-volz.github.io/Orylio-updates/companion/appcast.xml)
- [Viewer downloads](https://a-volz.github.io/Orylio-updates/viewer/) and [signed feed](https://a-volz.github.io/Orylio-updates/viewer/appcast.xml)

**Orylio Companion 0.2.0** is available as a signed and notarized update: [release and downloads](https://github.com/a-volz/Orylio-updates/releases/tag/companion-v0.2.0). The Viewer feed currently remains empty. App releases use separate tags `companion-vX.Y.Z` and `viewer-vX.Y.Z`, each with its own signed/notarized DMG and matching manifest. A release never installs the other app. The companion installs its bundled Lightroom plugin on first start.

GitHub Pages serves the stable signed feeds. Do not use repository-wide `releases/latest` to select one product. The historical `feed-initial` asset/root appcast stays empty for development-client compatibility and is not the current distribution feed.

Public app releases and feed promotion are separate explicit actions. Private keys, credentials, catalogs, photos and development sources never belong here. Signed XML must not be modified without re-signing.
