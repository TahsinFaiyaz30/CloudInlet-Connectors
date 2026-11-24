# CloudInlet Connectors

Official downloadable Windows x64 provider packs for CloudInlet. The application, public SDK, Backblaze B2 and OneDrive source live in the source repository. Each connector release identifies the exact commit used to build it. [Application and provider source](https://github.com/TahsinFaiyaz30/CloudInlet) · [Published releases](https://github.com/TahsinFaiyaz30/CloudInlet-Connectors/releases)

## Install a connector

In a connector-enabled CloudInlet build, open **Connectors**, select a provider, review the publisher and download location, and choose **Install**. Use **Settings → Updates and about** for connector updates. The EXE, MSI, portable and MSIX builds use the same signed catalog. This repository publishes provider extensions independently of the app. [Connector guide](https://github.com/TahsinFaiyaz30/CloudInlet/blob/8f0e1f465da739b3235fb8590849ee50beb52f77/docs/CONNECTORS.md)

The official publisher is **CloudInlet**. Its P-256 public key has SHA-256 fingerprint `D3E879A5EA4B3F3316472C9A9CFAC000DFDE296E7980D71AB0AD4C358741388A`. The app pins this key and the stable discovery URL. Each catalog entry authenticates a versioned release asset and its SHA-256 digest. [Signed catalog](https://raw.githubusercontent.com/TahsinFaiyaz30/CloudInlet-Connectors/main/catalog.json) · [Public signing identity](https://github.com/TahsinFaiyaz30/CloudInlet/blob/8f0e1f465da739b3235fb8590849ee50beb52f77/connectors/official-source.json)

## Maintainers

Dispatch **Publish a signed connector** from the main branch with one official connector ID and a full reviewed CloudInlet commit SHA. The production environment signs the pack and the cumulative catalog. Each immutable release contains its signed pack, checksums and release notes. Rerun the same inputs to recover an interrupted release. Tooling changes require reviewing the signer commit in `.github/publisher.json`. [Release procedure](https://github.com/TahsinFaiyaz30/CloudInlet/blob/8f0e1f465da739b3235fb8590849ee50beb52f77/docs/CONNECTOR_RELEASES.md)

Developers can keep custom connectors entirely private, or publish through their own repositories and publisher identities. [Private and community connector tutorial](https://github.com/TahsinFaiyaz30/CloudInlet/blob/8f0e1f465da739b3235fb8590849ee50beb52f77/docs/CONNECTORS.md)
