# Rome

**Your AI apps, finally on speaking terms.**

Rome is being built to unify LLM desktop apps in one workspace, with **chat mirroring** at its core.

Different models. Shared context. Less copy-paste diplomacy.

## Chat mirroring

The goal is simple: let different LLMs talk and work together as if they share the same environment, with those conversations reflected in their individual desktop apps.

Ask one model to make a plan, another to poke holes in it, and a third to help build it. Rome aims to keep that collaboration connected to the original chats, so you can move between Rome and your familiar apps without playing messenger.

## Give your chats a shared home

- **Hubs** group related chats around a project or idea.
- **Shared material** keeps the brief, references, and outputs in one place.
- **Connection controls** let you choose which chats can read each other’s history, send messages, or delegate tasks.
- **One workspace** helps you follow the work across models and pick up the right conversation.

Rome handles the introductions. You stay in charge.

## Where things stand

Rome is in early development, starting with coding-agent chats. Cross-app chat mirroring is still being developed and tested; compatibility and sync behavior depend on each app’s integration.

## Install Rome

**The latest macOS preview is here: v0.15.0-beta.2.** Apple Silicon and Intel, macOS 13 or later. Pick your Mac; Rome handles the introductions.

<a href="https://github.com/t3knobox/rome-releases/releases/download/v0.15.0-beta.2/Rome-arm64.dmg"><img src="assets/install-macos-arm64.svg" alt="Get Rome for macOS — Apple Silicon" width="380"></a>
<a href="https://github.com/t3knobox/rome-releases/releases/download/v0.15.0-beta.2/Rome-x64.dmg"><img src="assets/install-macos-x64.svg" alt="Get Rome for macOS — Intel" width="380"></a>

1. Click the download button above for your Mac: **Apple Silicon** for an M-series Mac, or **Intel** for an Intel Mac. Check **Apple menu → About This Mac** if unsure.
2. Open the downloaded `.dmg` file and drag **Rome** into **Applications**.
3. Open **Finder → Applications** and double-click **Rome**.
4. Once Rome is installed, you can eject the disk image from Finder.

### If macOS won’t open Rome

> **Note:** This preview is not Apple-notarized, so macOS may block it the first time you open it or say that Apple cannot verify it. If you downloaded Rome from this repository and trust it, use **Open Anyway**:

1. Try opening **Rome** from **Applications** once, then dismiss the warning.
2. Open **Apple menu → System Settings → Privacy & Security**.
3. Scroll down to **Security** and click **Open Anyway** beside the message about Rome.
4. Confirm with **Open** if prompted, and enter your Mac password or use Touch ID if asked.

If **Open Anyway** is missing, try opening Rome again, then return to **Privacy & Security**. See [Apple’s instructions for opening a blocked app](https://support.apple.com/en-sg/102445) for more help.

See the [release notes](https://github.com/t3knobox/rome-releases/releases/tag/v0.15.0-beta.2) for preview limits and checksums. **Settings → Hubs & collaboration → About** shows your installed version and build revision.

### Keep Rome current

Use **Check for updates**, then **Install update & restart** under **Settings → Hubs & collaboration → About**. Enable **Automatic updates** there to download updates in the background and install when you quit. Automatic updates start off; you choose when Rome gets the keys. Preview builds receive later preview updates too. Existing v0.15.0-beta.1 installations can update inside Rome.

## About this repository

**There’s only one official Rome, and it lives here on GitHub.** We don’t have a separate website. If that changes, we’ll announce it here first.

This is Rome’s public home for installers, release notes, update files, and notices. Application source and development history are maintained separately in a private repository.

GitHub’s automatic “Source code” archives contain only this download repository’s files; they are not the Rome application source.

## Open-source acknowledgements

Rome is derived from [Paseo](https://github.com/getpaseo/paseo), copyright © 2025–present Mohamed Boudra, licensed under the [Apache License 2.0](LICENSE). Third-party components retain their respective licenses.
