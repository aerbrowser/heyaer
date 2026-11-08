# heyaer

Official distribution repository for **Aer**, a browser for Apple Silicon Macs running macOS 13 or later.

## Downloads

Download the `.dmg` installer from [Releases](https://github.com/astaxie/heyaer/releases).

Releases are signed with Apple Developer ID and notarized by Apple before publication. SHA-256 checksums accompany each release.

## Automatic updates

Update-enabled versions of Aer check the public release feed over HTTPS and verify update archives using Sparkle Ed25519 signatures. Choose **Aer → Check for Updates…** to check manually. Installing an update requires user confirmation and uses the browser’s normal session-saving exit.

Versions shipped before automatic updates were added need one manual installation of an update-enabled release.

This repository contains release assets, the update feed and distribution documentation. Application source code is maintained in a separate private repository. No GitHub account or access token is required to download public releases.

## Feed

`https://github.com/astaxie/heyaer/releases/latest/download/appcast.xml`

The feed becomes available when the first update-enabled release is published.
