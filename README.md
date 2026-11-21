# AetherScribe

![AetherScribe icon](images/icon.png)

**The Roleplay Writing Companion for Eorzea**  
Developed by **Jesstify**.

AetherScribe is a Dalamud plugin for Final Fantasy XIV that helps roleplayers prepare, refine, and send in-game chat messages.

## Features

- Multiple Scratch Pads for drafting roleplay text.
- UTF-8-aware message splitting that fills the available chat length before creating a new message.
- Word-boundary-aware splitting with Unicode and emoji safety.
- Chat channel selection, aliases, OOC tags, and continuation markers.
- Character and message counters.
- Sequential **Send All Messages to Chat** with a configurable delay and cancellation.
- Spell checking, dictionaries, and thesaurus support.
- A dark blue and cyan interface theme.

## Installation through Dalamud

Custom repository URL:

```
https://raw.githubusercontent.com/Eurekarp/AetherScribe/main/repo.json
```

In FFXIV, open `/xlsettings`, go to **Experimental → Custom Plugin Repositories**, paste the URL, and save it. Then open `/xlplugins` and search for **AetherScribe**.

The plugin will appear after the first successful public release. Until a valid Dalamud package is published, its entry stays hidden in the repository feed.

## Development

- .NET 10 SDK
- Dalamud.NET.Sdk 15.0.0
- Visual Studio with the .NET desktop development workload

Build locally by running `Build-AetherScribe.bat` or building `AetherScribe.sln` in Release / x64 mode.

## Releases

Push a version tag in the format `v1.16.2.0` to trigger the GitHub Actions workflow. It builds the plugin, packages the Dalamud release ZIP, creates a GitHub Release, and publishes the plugin metadata to `repo.json`.

AetherScribe is an independent community project and is not affiliated with Square Enix or the Final Fantasy XIV development team.
