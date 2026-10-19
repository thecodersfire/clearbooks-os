# Built-in features for clearbooks-os

Purpose: bookkeeping

1. **prepare study and research files** — run clearbooks-os-workspace. It creates ~/Documents/clearbooks-os-workspace/ with Notes, Sources, Assignments folders.
2. **plan a learning session** — run clearbooks-os-plan to open a purpose-specific Markdown plan, saved under ~/Documents/clearbooks-os-session-plans/.
3. **check study and source readiness** — run clearbooks-os-check for an interactive checklist. Answers are not saved or transmitted.

These local tools create folders, open a local note, or display prompts. They do not install packages, change system settings, or send data.

Install them from this repository:

    mkdir -p "$HOME/.local/bin"
    install -m 0755 features/clearbooks-os-workspace features/clearbooks-os-plan features/clearbooks-os-check "$HOME/.local/bin/"
