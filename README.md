# Promptster CLI Releases

Public distribution repo for Promptster CLI binaries and installer script.

Install with:

```sh
curl -fsSL https://get.promptster.ai | sh
```

Pin a version with:

```sh
PROMPTSTER_VERSION=0.2.9 curl -fsSL https://get.promptster.ai | sh
```

The installer endpoint is served from Vercel at `/` and returns [`install.sh`](/tmp/promptster-cli-releases/install.sh) as plain text. It downloads Promptster binaries from GitHub Releases in this repo: `pa-arth/promptster-cli-releases`.

Use the Releases page directly if you want to download platform binaries without the installer.
