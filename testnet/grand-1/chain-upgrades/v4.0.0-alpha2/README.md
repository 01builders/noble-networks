# Upgrade to v4.0.0-alpha2

## Overview

We are excited to announce the next software upgrade for the Noble `grand-1` testnet chain. This upgrade will transition the network to `v4.0.0-alpha2`. This upgrade adds stability to both the CCTP and Router modules, allowing continued testing.

**Key Details:**
- **Target Block:** [`2682700`](https://testnet.mintscan.io/noble-testnet/blocks/2682700)
- **Estimated Date & Time:** Thursday, August 24th, around 11am EST. *(Please note that this is an approximation. Due to varying block times, it's crucial to monitor the chain for the exact upgrade time.)*

## Step-by-Step Upgrade Instructions

1. **Set Halt Height:** All validators must set the halt height to `2682700`. There is no on chain instruction to halt.
2. **Use Pre-Built Binaries:** Choose the appropriate binary for your system:
   - [AMD](./nobled_linux-amd64)
   - [ARM](./nobled_linux-arm64)


### Using Docker?

Pull the latest image with:

```shell
docker pull ghcr.io/strangelove-ventures/heighliner/noble:v4.0.0-alpha2
```

### Binary Checksums

Ensure the integrity of your binaries:

```shell
# For AMD:
$ sha256sum nobled_linux-amd64
81a60df2336511ee6dd1e7a9329e79a695c6370d7ab87285140a43995d215ab6  nobled_linux-amd64

# For ARM:
$ sha256sum nobled_linux-arm64
aca9a3de05f597e5c511b45c068eee83073e880e96b5a037766f5a18933e3d96  nobled_linux-arm64
```

---