# AetherScribe

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

## Install through Dalamud

Add this custom repository in Dalamud:

```
https://raw.githubusercontent.com/Eurekarp/AetherScribe/main/repo.json
```

1. Open `/xlsettings` in Final Fantasy XIV.
2. Go to **Experimental → Custom Plugin Repositories**.
3. Paste the URL above and save.
4. Open `/xlplugins` and search for **AetherScribe**.

The plugin appears after a public GitHub Release containing an asset named `latest.zip`. The release workflow validates the package and then publishes the entry to the Dalamud feed.

## Development

- .NET 10 SDK
- Dalamud.NET.Sdk 15.0.0
- Visual Studio with the .NET desktop development workload

Build locally with `Build-AetherScribe.bat` or open `AetherScribe.sln` and build in Release / x64 mode.

AetherScribe is an independent community project and is not affiliated with Square Enix or the Final Fantasy XIV development team.
