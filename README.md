# Smol Studio downloads

Smol Studio runs local Docker containers, Compose projects, Kubernetes, and Linux virtual machines. Local workloads work without a Smol account.

## Apple Silicon preview

[Download the DMG](https://github.com/smol-machines/smol-studio-downloads/releases/download/v1.0.0-preview.1/smol-studio-1.0.0-darwin-arm64.dmg) · [SHA-256 checksum](https://github.com/smol-machines/smol-studio-downloads/releases/download/v1.0.0-preview.1/smol-studio-1.0.0-darwin-arm64.dmg.sha256)

Open the DMG and drag **Smol Studio** to **Applications**. This preview uses an ad hoc signature and has not been notarized by Apple. If macOS blocks the first launch and you trust this download, open **System Settings → Privacy & Security → Open Anyway** after trying to open the app. Managed Macs may restrict this option. [Apple’s instructions](https://support.apple.com/en-us/102445)

To verify the download, save the DMG and checksum together and run this command in that folder.

```sh
shasum -a 256 -c smol-studio-1.0.0-darwin-arm64.dmg.sha256
```

To run a Compose project, open Studio, choose **Home → Open project…**, select the folder containing your Compose file, and choose **Run project**.
