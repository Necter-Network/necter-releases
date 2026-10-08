# Necter Miner — downloads

Installers for the **Necter Miner**: mine on the Necter Network testnet from your phone or computer.
Rewards on the testnet are paid in test NECTA on Ethereum Sepolia and have no monetary value.

**Get the latest version:** [Releases](https://github.com/Necter-Network/necter-releases/releases/latest)

| Platform | File | Notes |
|---|---|---|
| macOS (Apple Silicon + Intel) | `Necter-Miner-macOS-universal.dmg` | macOS 11+ |
| Android (phones, arm64 / armv7) | `Necter-Miner-android.apk` | Android 8.0+ |
| Windows, Linux | coming soon | |
| Servers | CLI / Docker | see the documentation on [necter.network](https://necter.network) |

## Install

### macOS
1. Open the DMG and drag **Necter Miner** into **Applications**.
2. Open it once. macOS will say the developer cannot be verified (this testnet build is not notarized yet).
3. Go to **System Settings → Privacy & Security**, scroll down and click **Open Anyway** next to Necter Miner.
   (On older macOS: right-click the app → **Open** → **Open**.)

### Android
1. Download the APK on your phone and open it.
2. Allow **Install unknown apps** for your browser or file manager when asked.
3. If Google Play Protect warns about an unknown developer, choose **Install anyway**.

## Verify your download
Each release lists the SHA-256 checksum of every file. On macOS/Linux:

```bash
shasum -a 256 Necter-Miner-macOS-universal.dmg
```

## Links
- Website: https://necter.network
- Mining store (testnet): https://testnet.necter.network
- Network API (testnet): https://testnet-rpc.necter.network

Built by [Hive Innovation Lab](https://www.hiveinnovationlab.org).
