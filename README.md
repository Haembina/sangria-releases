<p align="center">
  <img src="icons/icon.png" alt="Sangria logo" width="128">
</p>

# Sangria

A private period tracker: the days a period starts and ends, how each day
felt, and a forecast of the next period and ovulation.

Sangria keeps its data on the device. It has no account, backend or analytics,
and it gives no medical advice.

**[Download the latest version](https://github.com/Haembina/sangria-releases/releases/latest)**

This repository exists only to host the Linux downloads. The source is kept
privately by [Haembina](https://haembina.com).

## Installing on Linux

Every build is 64-bit x86. Two files are published with every release:

| File | Use it when |
| --- | --- |
| `Sangria-x86_64.flatpak` | Your distribution has Flatpak, which most do. |
| `Sangria-linux-x86_64.tar.gz` | You want the app folder itself, without Flatpak. |

### Flatpak

Flatpak fetches the runtime Sangria runs on from Flathub the first time:

```sh
flatpak install --user Sangria-x86_64.flatpak
flatpak run com.haembina.sangria
```

### The app folder

Unpack the archive anywhere and start `Sangria/bin/Sangria`. It carries its own
Java runtime.
