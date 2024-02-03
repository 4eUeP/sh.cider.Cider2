# Cider2

<https://cider.sh/download>

## Build and Install

First put your `cider*.deb` in the same directory as the `sh.cider.Cider2.yml`
file.

```sh
# If you haven't already installed the runtime and sdk
#flatpak install --user flathub org.freedesktop.Platform//23.08 org.freedesktop.Sdk//23.08 org.electronjs.Electron2.BaseApp/x86_64/23.08

flatpak-builder --user --install --force-clean build sh.cider.Cider2.yml
```
