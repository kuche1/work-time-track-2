# work-time-track-2

## Setup

```
cargo install dioxus-cli

paru android-ndk
sudo pacman -S jdk17-openjdk

# https://wiki.archlinux.org/title/Android#SDK_packages
paru android-sdk-cmdline-tools-latest
paru android-sdk-build-tools # ? not needed ?
paru android-sdk-platform-tools
paru android-platform # ? not needed ?

paru android-platform-34
paru android-sdk-build-tools-34

# then relog
```

## Run

```
~/.cargo/bin/dx serve --platform android
```
