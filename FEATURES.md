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

## Fifteen more purpose-specific preinstalled applications

These applications add tools suited to this setup focus. They are installed from Flathub by the setup scripts.

1. **Pixelorama** (com.orama_interactive.Pixelorama) — draw pixel-art sprites and frame-based animations.
2. **Synfig Studio** (org.synfig.SynfigStudio) — create vector-based 2D animations.
3. **OpenToonz** (io.github.OpenToonz) — produce hand-drawn and cutout 2D animation.
4. **RawTherapee** (com.rawtherapee.RawTherapee) — develop RAW photo files with tone and color controls.
5. **digiKam** (org.kde.digikam) — catalog, tag, and batch-process large photo collections.
6. **Shotwell** (org.gnome.Shotwell) — import, sort, and make quick edits to photo libraries.
7. **MuseScore Studio** (org.musescore.MuseScore) — write, play back, and print sheet music.
8. **LMMS** (io.lmms.LMMS) — compose electronic music and loops.
9. **Hydrogen** (org.hydrogenmusic.Hydrogen) — program drum patterns and percussion tracks.
10. **Guitarix** (org.guitarix.Guitarix) — shape guitar tone with amp and effects processing.
11. **JabRef** (org.jabref.jabref) — organize BibTeX references and research citations.
12. **Thunderbird** (org.mozilla.Thunderbird) — manage email and communication accounts.
13. **Krita** (org.kde.krita) — paint digital illustrations.
14. **Inkscape** (org.inkscape.Inkscape) — create vector illustrations and diagrams.
15. **Blender** (org.blender.Blender) — create 3D assets and animations.

Emulator frontends do not include game ROMs or copyrighted game files; supply only files you are legally allowed to use.
