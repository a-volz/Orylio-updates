# Orylio Updates

Public signed metadata and download pages for two independent native Mac apps. Development sources remain private.

- [Helper downloads](https://a-volz.github.io/Orylio-updates/helper/) and [signed feed](https://a-volz.github.io/Orylio-updates/helper/appcast.xml)
- [Viewer downloads](https://a-volz.github.io/Orylio-updates/viewer/) and [signed feed](https://a-volz.github.io/Orylio-updates/viewer/appcast.xml)

Each feed currently contains **no app version**. No app or installer is published by this setup. Future approved app releases use separate tags `helper-vX.Y.Z` and `viewer-vX.Y.Z`, each with its own signed/notarized DMG and matching manifest. A release never installs the other app. The helper installs its bundled Lightroom plugin on first start.

GitHub Pages serves the stable signed feeds. Do not use repository-wide `releases/latest` to select one product. The historical `feed-initial` asset/root appcast stays empty for development-client compatibility and is not the current distribution feed.

Public app releases and feed promotion are separate explicit actions. Private keys, credentials, catalogs, photos and development sources never belong here. Signed XML must not be modified without re-signing.
