# AetherScribe

**The Roleplay Writing Companion for Eorzea**  
Created and maintained by **Jesstify**.

AetherScribe is a Dalamud plugin for Final Fantasy XIV focused on roleplay writing: Scratch Pads, UTF-8-aware chat chunking, message previews, character counts, spell checking, thesaurus lookup, and user-initiated sequential chat sending.

## Repository status

This public repository has been created and is being prepared for the complete source project. The source upload is pending confirmation of redistribution rights for the upstream-derived Wordsmith code.

## Features planned for this repository

- Scratch Pads for drafting longer roleplay messages.
- Max-length-first message chunking using UTF-8 byte counts, preferring word boundaries and preserving Unicode characters.
- Chat headers, aliases, OOC tags, and configurable continuation markers.
- Character count for completed outgoing messages.
- Explicit **Send All Messages to Chat** action with sequential sending and cancellation of unsent messages.
- Spell checking, custom dictionaries, and thesaurus lookup.
- AetherScribe dark blue / cyan UI theme.

## Build

The project targets .NET 10 and Dalamud.NET.Sdk 15.0.0. Build instructions will be published with the source once the upstream redistribution permission is resolved.

## Licensing status

AetherScribe is based on the original Wordsmith Dalamud plugin by MythicPalette. The upstream repository's visible root file listing does not include an explicit license file. Public availability does not grant permission to relicense or redistribute the upstream-derived source under MIT.

The MIT license text prepared for Jesstify-authored contributions does not automatically apply to the upstream-derived code or third-party assets/data. Please see [LICENSE-STATUS.md](LICENSE-STATUS.md) and [UPSTREAM-NOTICE.md](UPSTREAM-NOTICE.md).

AetherScribe is an independent community project and is not affiliated with Square Enix or the Final Fantasy XIV development team.
