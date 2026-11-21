# Preview Pro Max for Flatpak

Install the stable channel for x86-64 or ARM64. Flathub supplies the GNOME runtime.

```sh
flatpak remote-add --user --if-not-exists flathub https://dl.flathub.org/repo/flathub.flatpakrepo
flatpak remote-add --user --if-not-exists preview-pro-max https://raw.githubusercontent.com/monoterne/preview-pro-max-flatpak/main/preview-pro-max.flatpakrepo
flatpak install --user preview-pro-max com.previewpromax.viewer
flatpak run com.previewpromax.viewer
```

Use `flatpak update --user com.previewpromax.viewer` to update. The signing key fingerprint is in `signing-fingerprint`.

[Application and release instructions](https://github.com/monoterne/PreviewProMax)
