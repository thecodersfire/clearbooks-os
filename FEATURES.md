# Built-in features for clearbooks-os

Purpose: bookkeeping

1. **prepare study and research files** — run clearbooks-os-workspace. It creates ~/Documents/clearbooks-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run clearbooks-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/clearbooks-os-session-plans/.
3. **check study and source readiness** — run clearbooks-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/clearbooks-os-workspace features/clearbooks-os-plan features/clearbooks-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for bookkeeping:

1. **GNOME Calendar** — org.gnome.Calendar
2. **KeePassXC** — org.keepassxc.KeePassXC
3. **DB Browser for SQLite** — org.sqlitebrowser.sqlitebrowser

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for bookkeeping:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
3. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
4. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
5. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
6. **GNOME Text Editor** — edit plain-text notes and configuration files (org.gnome.TextEditor)
7. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
8. **Document Scanner** — digitize paper notes and forms (org.gnome.SimpleScan)
9. **GNOME Contacts** — organize partner and team contacts (org.gnome.Contacts)
10. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
