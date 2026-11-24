# CloudInlet Connectors

Distribution repository for official downloadable CloudInlet provider connectors.

The app, public connector SDK and official connector source are maintained in [TahsinFaiyaz30/CloudInlet](https://github.com/TahsinFaiyaz30/CloudInlet). Code contributions belong there. This repository is for connector release assets, signed catalogs and release notes.

## Status

This repository has been initialized. Production connector packages and the signed catalog have not been published here yet. Repository creation does not publish a new app version or establish Microsoft Store approval for connector delivery.

## Distribution plan

- Publish signed, versioned .cipack files as GitHub Release assets, starting with Backblaze B2 and OneDrive.
- Give connectors independent versions and declare compatible SDK versions and dependencies.
- Publish a signed catalog that points to immutable package downloads. Each catalog release must retain compatible choices for supported app versions.
- Keep signing keys, credentials, local test artifacts and user data out of this repository and its releases.
- Record source commit, checksums and release notes for each package. Never replace the bytes of a published package version.

CloudInlet's connector manager will use the configured official catalog for installation and updates. Microsoft Store delivery requires its own supported packaging and approval workflow; this repository does not bypass it.

## Community and personal connectors

Developers can maintain connectors in their own repositories or private folders using the shared SDK. A personal connector does not need a public repository. Community packages are not automatically official packages and keep their own publisher identity and trust review.
