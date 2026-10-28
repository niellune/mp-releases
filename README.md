# MP

MP is a free multiplayer voxel RPG: a Minecraft-style world you can dig and build in, with WoW-Classic-style races, classes and factions.
Everyone plays together on one shared server.

## Download

Download the newest release from the [Releases page](https://github.com/niellune/mp-releases/releases).
Each release lists what changed and has `SHA256SUMS.txt` to check your downloads.

## Install

### Windows

1. Unzip `mp-<version>-windows.zip`.
2. Double-click `play.bat` (or `mp-game.exe`).
3. SmartScreen warns that the app is unknown, because this build is not signed. Click **More info**, then **Run anyway**.

### macOS (Apple silicon only)

1. Unzip `mp-<version>-macos-arm64.zip`.
2. Open `MP.app`. It is signed and notarized, so it opens normally.
3. Settings, the server list and your login live in `~/Library/Application Support/MP`.

### Meta Quest (experimental)

1. Turn on Developer Mode for your Quest.
2. Install with `adb install -r mp-<version>-quest.apk`, or with SideQuest.

## Join

The server `164.90.197.99:5300` is already in the server list.
The first connect remembers the server's certificate. If it ever changes, the game refuses to connect and says why.

## Accounts

Pick a handle and a password. There is no email.
Keep your recovery codes. They are shown once, and they are how you get the account back.

## Privacy

The server stores your handle, a password hash, your recovery-code hashes, a hash of each login
token with its platform (Windows, macOS or Quest), when your account was made and last seen, and
your game progress. Its log records the IP address each session connects from. No email, no real
name, nothing else.

## Alpha

Alpha, best effort: the server may be down or reset.

## Versions

Each release names the server protocol it speaks. A build of another protocol is refused at connect,
with a message that links to this page.
