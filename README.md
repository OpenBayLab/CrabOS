# CrabOS

## About

CrabOS is the agent OS you work in.

CrabVisor is its companion sandbox host. It is a separate app that runs isolated containers on this machine. CrabOS connects to it when a task needs a sandbox.

You can use CrabOS without CrabVisor. Install both when you want that sandbox.

## Downloads

### CrabOS

- macOS Apple Silicon: `CrabOS-0.6.0-mac-arm64.dmg`
- Windows x64: `CrabOS-0.6.0-win-x64.exe`

### CrabVisor

- macOS Apple Silicon: `CrabVisor-0.6.0-mac-arm64.dmg`
- Windows x64: `CrabVisor-0.6.0-win-x64.exe`

## macOS install

These builds are unsigned. Drag the app into Applications, then paste the matching command in Terminal and press Return.

CrabOS:

```
xattr -cr /Applications/CrabOS.app 2>/dev/null || true; open /Applications/CrabOS.app
```

CrabVisor:

```
xattr -cr /Applications/CrabVisor.app 2>/dev/null || true; open /Applications/CrabVisor.app
```
