# CloudInlet connector directory

The signed catalog lists each official connector independently. Select a connector to see its complete release history. The original 1.0.0 downloads remain available here. [Historical releases](https://github.com/TahsinFaiyaz30/CloudInlet-Connectors/releases)

| Connector | Version | Platform | Connector SDK | Package | Release notes |
| --- | --- | --- | --- | --- | --- |
| [Backblaze B2](https://github.com/TahsinFaiyaz30/CloudInlet-Connector-B2) | 1.0.0 | Windows x64 | ≥ 1.0.0, < 2.0.0 | [b2-1.0.0.cipack](https://github.com/TahsinFaiyaz30/CloudInlet-Connectors/releases/download/b2-v1.0.0/b2-1.0.0.cipack) | [Release notes](https://github.com/TahsinFaiyaz30/CloudInlet-Connectors/releases/tag/b2-v1.0.0) |
| [OneDrive](https://github.com/TahsinFaiyaz30/CloudInlet-Connector-OneDrive) | 1.0.0 | Windows x64 | ≥ 1.0.0, < 2.0.0 | [onedrive-1.0.0.cipack](https://github.com/TahsinFaiyaz30/CloudInlet-Connectors/releases/download/onedrive-v1.0.0/onedrive-1.0.0.cipack) | [Release notes](https://github.com/TahsinFaiyaz30/CloudInlet-Connectors/releases/tag/onedrive-v1.0.0) |

## Install and update

In a connector-enabled CloudInlet build, open **Connectors**, select the provider, review the publisher and download, and choose **Install**. Open **Settings → Updates and about** to update an installed connector. The published CloudInlet 1.2.1 app predates the Connectors page. [Run the connector-enabled host](https://github.com/TahsinFaiyaz30/CloudInlet/blob/3664f01607a6c916c8bf1cc8f72206151901d9e2/docs/CONNECTORS.md#try-the-published-connectors)

CloudInlet verifies the signed catalog and package. The official publisher fingerprint is `D3E879A5EA4B3F3316472C9A9CFAC000DFDE296E7980D71AB0AD4C358741388A`. [Central directory](https://github.com/TahsinFaiyaz30/CloudInlet-Connectors) · [Signed catalog](https://raw.githubusercontent.com/TahsinFaiyaz30/CloudInlet-Connectors/main/catalog.json) · [Connector development guide](https://github.com/TahsinFaiyaz30/CloudInlet/blob/3664f01607a6c916c8bf1cc8f72206151901d9e2/docs/CONNECTORS.md)

## Maintainers

Dispatch **Publish a signed connector** with one provider and its reviewed source commit. The protected central workflow signs the package, verifies its public download and updates this directory from the complete signed catalog. [Release procedure](https://github.com/TahsinFaiyaz30/CloudInlet/blob/3664f01607a6c916c8bf1cc8f72206151901d9e2/docs/CONNECTOR_RELEASES.md) · [Host package measurements](https://github.com/TahsinFaiyaz30/CloudInlet/blob/3664f01607a6c916c8bf1cc8f72206151901d9e2/docs/CONNECTOR_VERIFICATION.md)

<!-- Generated from the verified official catalog by CloudInlet.ConnectorTool release-readme. -->
