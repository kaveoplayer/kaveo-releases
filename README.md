# Kaveo — releases and support

Kaveo is a media player and library for Linux and Windows. This repository holds its **releases** and
its **support**; the application's source is not here.

- **Download** — [the latest release](https://github.com/mattia-cenci/kaveo-releases/releases/latest),
  with a file for every format: `.deb`, `.rpm`, Arch (`kaveo-bin`), AppImage and a tarball for Linux;
  an installer, an `.msi` and a portable `.zip` for Windows. Installed copies update themselves from
  inside the app.
- **Guide** — [the user guide](https://mattia-cenci.github.io/kaveo-website/).
- **Something is wrong** — [open an issue](https://github.com/mattia-cenci/kaveo-releases/issues/new/choose).
- **Questions and ideas** — [Discussions](https://github.com/mattia-cenci/kaveo-releases/discussions).
- **Licence keys** — mattia.cenci@bosimano.com.

Every release is signed: its `latest.json` carries an ed25519 signature that Kaveo checks before it
installs anything, and every file's SHA-256 is listed there.
