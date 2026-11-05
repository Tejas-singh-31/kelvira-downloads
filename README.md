# Kelvira

Ask by voice or text. Launch your apps in one click.

Kelvira is a Windows desktop assistant with a chat window, a launcher bar, voice input and spoken replies. It is free while in beta.

## Download

**[Download Kelvira 0.4.1 for Windows](https://github.com/Tejas-singh-31/kelvira-downloads/releases/download/v0.4.1/Kelvira-Setup.exe)**

- Windows 10 or 11 (64-bit)
- About 170 MB
- Installs for your user account, no administrator rights needed

### SmartScreen warning

The installer is not code-signed yet, so Windows SmartScreen may show "Windows protected your PC". Choose **More info**, then **Run anyway**.

### Verify your download (SHA-256)
```
448F18DB3429F9A4D3F53C17AD529F64B357229281734DE9B696B6604752EA62
```

In PowerShell:

```
Get-FileHash "$HOME\Downloads\Kelvira-Setup.exe" -Algorithm SHA256
```

The result should match the value above.

## Notes

- Chat messages are sent to AI providers to produce replies. Voice is recorded only when you use the mic button or your voice shortcut, and the recording is sent for transcription after you stop.
- The first reply after a quiet period can take up to a minute while the server wakes up.
- This is a beta release. Features and limits may change.

## Links

- Website: https://kelvira.apexdevs.workers.dev
- Releases: https://github.com/Tejas-singh-31/kelvira-downloads/releases

All product names, logos and brands are the property of their respective owners. Kelvira is not affiliated with or endorsed by them.
