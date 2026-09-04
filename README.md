# BoltGauge releases

Release files for the [BoltGauge](https://app.bolt-gauge.com) agent.
The source code is private. This repository exists so anyone can
download the agent without an account.

Each release carries the program and a `.sha256` file. Check the
download before you open it:

```powershell
Get-FileHash .\boltgauge-agent-win-x64.exe -Algorithm SHA256
```

The result must match the `.sha256` file and the hash on
<https://app.bolt-gauge.com/download>. If it does not, delete the
file.

The file is signed by Patrick Williams, the person behind BoltGauge.
Windows still shows its "Windows protected your PC" screen for a new
release's first weeks, until enough people have run it. That screen
names Patrick Williams as the publisher. Click "More info", then
"Run anyway". If the screen says the publisher is unknown, stop.
That file is not ours.
