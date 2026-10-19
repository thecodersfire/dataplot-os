# Built-in features for dataplot-os

Purpose: data science

1. **prepare study and research files** — run dataplot-os-workspace. It creates ~/Documents/dataplot-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run dataplot-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/dataplot-os-session-plans/.
3. **check study and source readiness** — run dataplot-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/dataplot-os-workspace features/dataplot-os-plan features/dataplot-os-check "$HOME/.local/bin/"

## Preinstalled purpose software

The installer adds these three Flathub applications for data science:

1. **Thonny** — org.thonny.Thonny
2. **QGIS** — org.qgis.qgis
3. **GIMP** — org.gimp.GIMP

They are installed from Flathub during setup. The repository contains application IDs and documentation, not third-party binaries; each publisher’s terms and licenses apply.

## Ten more purpose-specific preinstalled applications

The setup installs these ten Flathub apps selected for data science:

1. **Zotero** — manage research sources and citations (org.zotero.Zotero)
2. **Anki** — create spaced-repetition study decks (net.ankiweb.Anki)
3. **Calibre** — organize ebooks and convert documents (com.calibre_ebook.calibre)
4. **Foliate** — read EPUB books (com.github.johnfactotum.Foliate)
5. **Godot Engine** — build and test 2D and 3D games (org.godotengine.Godot)
6. **GNOME Papers** — read project and reference PDFs (org.gnome.Papers)
7. **GNOME Calculator** — perform scientific and financial calculations (org.gnome.Calculator)
8. **GNOME Calendar** — schedule sessions, deadlines, and events (org.gnome.Calendar)
9. **GNOME Clocks** — time work sessions and events (org.gnome.clocks)
10. **GNOME Maps** — look up places and plan routes (org.gnome.Maps)

Flathub distributes the app packages. Check each publisher license and terms. This repository contains app IDs and documentation, not third-party binaries.
