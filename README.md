# org.freedesktop.Sdk.Extension.socat

## Build

```
flatpak-builder --repo=.flatpak-builder/repo  --force-clean build-dir org.freedesktop.Sdk.Extension.socat.json
```

## Install

```
sudo flatpak remote-add --no-enumerate --no-gpg-verify socat .flatpak-builder/repo

flatpak install socat org.freedesktop.Sdk.Extension.socat
```