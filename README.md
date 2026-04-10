# node-pty-android

Build node-pty for Android (arm64/arm) using GitHub Actions.

## Build Status

| Platform | Status | Artifact |
|----------|--------|----------|
| android-arm64 | 🔨 Building... | node-pty-android-arm64.node |

## Usage

After build completes, download the `.node` file and place it in:

```
/data/data/com.termux/files/home/.openclaw/node_modules/@lydell/node-pty/
```

Or rebuild node-pty in Termux:

```bash
cd /data/data/com.termux/files/home/.openclaw/node_modules/@lydell/node-pty
npm install --build-from-source --runtime=node --target=25.8.2
```

## Requirements

- Node.js v25 (for OpenClaw)
- Android NDK r26b
- Python 3

## Credits

Based on [node-pty](https://github.com/metrobiotics/node-pty) by metrobiotics
