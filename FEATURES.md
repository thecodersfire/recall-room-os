# Built-in features for recall-room-os

Purpose: exam preparation

1. **organize project files** — run recall-room-os-workspace. It creates ~/Documents/recall-room-os-workspace/ with Inbox, Projects, Archive folders.
2. **draft a session plan** — run recall-room-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/recall-room-os-session-plans/.
3. **check task readiness** — run recall-room-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/recall-room-os-workspace features/recall-room-os-plan features/recall-room-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for exam preparation:

1. **Zotero** — org.zotero.Zotero
2. **Foliate** — com.github.johnfactotum.Foliate
3. **VSCodium** — com.vscodium.codium

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.
