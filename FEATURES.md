# Built-in features for dataplot-os

Purpose: data science

1. **prepare study and research files** — run dataplot-os-workspace. It creates ~/Documents/dataplot-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run dataplot-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/dataplot-os-session-plans/.
3. **check study and source readiness** — run dataplot-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/dataplot-os-workspace features/dataplot-os-plan features/dataplot-os-check "$HOME/.local/bin/"
