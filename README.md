# astonc_local_manifest
Local manifest for building Custom ROMs for the OnePlus Ace 3 (astonc).
# OnePlus Ace 3 (astonc) Local Manifest

This repository contains a local manifest for syncing the required repositories to build LineageOS-based ROMs for the OnePlus Ace 3 (codename: `astonc`).

## Usage

Create `.repo/local_manifests` if it doesn't exist:

```bash
mkdir -p .repo/local_manifests
```

Download the manifest:

```bash
curl -o .repo/local_manifests/astonc.xml \
https://raw.githubusercontent.com/CokSnUlgen/astonc_local_manifest/main/astonc.xml
```

Then sync:

```bash
repo sync
```
