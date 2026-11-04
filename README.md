# OAIZ CLI

Releases of `oaiz`, the command-line client for [OAIZ](https://oaiz.io). The source code is not in this repository.

## Install

macOS and Linux:

```sh
curl -fsSL https://oaiz.io/install.sh | bash
```

Windows, in PowerShell:

```powershell
irm https://oaiz.io/install.ps1 | iex
```

Read the [CLI documentation](https://oaiz.io/docs/cli) for commands and sign-in.

## Releases

Each release holds an archive for each system, its checksum, and a signed `manifest.json`. `oaiz upgrade` installs a release only when the OAIZ release key signed its manifest. Releases cannot change after they are published.

## Feedback

Send feedback with `oaiz feedback`.

## Terms

See [LICENSE.txt](LICENSE.txt).
