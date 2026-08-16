# BoltGauge releases

Release binaries for the [BoltGauge](https://app.bolt-gauge.com) agent. The
source repository is private; this repository exists so the binaries can be
downloaded publicly.

Each release carries the executable and a `.sha256` file. Verify the download
before opening it:

```powershell
Get-FileHash .\boltgauge-agent-win-x64.exe -Algorithm SHA256
```

The hash must match the one in the `.sha256` file and on
<https://app.bolt-gauge.com/download>.

The executable is unsigned: Windows shows an unknown-publisher warning on
first run. The download page explains what to expect.
