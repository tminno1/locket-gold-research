# Locket Gold Research

A research/demo repository for studying GitHub Raw distribution and Shadowrocket-compatible configuration files.

## Important scope

This repository does not unlock Locket Gold, bypass subscriptions, alter Locket authentication, or add features inside the official Locket app. Photobooth, AI filters, VIP-style interface, themes, effects, widgets, and friend sharing are planned for a separate app/demo or must use officially supported interfaces.

## Files

- `config/locket-gold.conf`: safe baseline Shadowrocket-format test profile. It routes traffic DIRECT and does not create a VPN tunnel.
- `config/manifest.json`: project metadata and feature roadmap.

## Publish a GitHub Raw link

After pushing this repository to GitHub, the Raw URL for the config is:

`https://raw.githubusercontent.com/USERNAME/locket-gold-research/main/config/locket-gold.conf`

Replace `USERNAME` with your GitHub username. The manifest URL is:

`https://raw.githubusercontent.com/USERNAME/locket-gold-research/main/config/manifest.json`

## Windows upload using GitHub website

1. Create a public repository named `locket-gold-research`.
2. Choose **Add file > Upload files**.
3. Upload the `config` folder and this README.
4. Commit the files to the `main` branch.
5. Open `config/locket-gold.conf` on GitHub and click **Raw**.
6. Copy the browser URL. That is the direct Raw URL.

## Shadowrocket test

1. Open the Raw URL in Safari first and verify that plain configuration text is displayed.
2. In Shadowrocket, use its configuration import/download-from-URL option and paste the Raw URL.
3. Inspect the imported profile before enabling anything.
4. This sample uses `FINAL,DIRECT`; it is a format/import test only, not a VPN service.

To route through a VPN/proxy, use a server and credentials you own or are authorized to use, and add them according to the current Shadowrocket documentation. Never publish credentials, subscription URLs, private keys, or tokens in a public repository.

## Updating

Edit the file in GitHub, commit the change, then refresh/re-download the Raw profile in Shadowrocket. Raw URLs point to the committed file contents; changes are not available until committed.
