MayronUI Reborn

⚠ Early Development / Revival Project

MayronUI Reborn is an ongoing effort to revive and modernize the original MayronUI addon for current and future versions of World of Warcraft, starting with Retail.

This project focuses on restoring functionality, fixing broken legacy APIs, and rebuilding a stable foundation before introducing new features or major refactors.

📌 Project Status

Current phase: Core revival & Retail compatibility

The addon is not yet feature-complete or production-ready.
Breaking changes, refactors, and temporary fixes are expected during this phase.

✅ What works so far

Core addon loads without startup Lua errors

Setup module loads successfully

Installation UI is visible and functional at a basic level

Major Retail API changes have been addressed:

C_AddOns migration (Addon loading, metadata, enable/disable)

C_Spell compatibility (GetSpellInfo)

Class localization fallback (FillLocalizedClassList)

Initial compatibility layer is verified in-game

⚠️ Known limitations

The installation process is not yet fully error-free

Additional Lua errors may occur during setup steps

Compatibility code is currently distributed across multiple files

Classic clients are not yet officially supported (planned later)

🛠 Current Development Focus

Stabilizing the setup & installation flow

Centralizing all compatibility code into a dedicated layer

Cleaning up legacy API usage

Ensuring safe startup and module initialization

Preparing the codebase for long-term maintainability

🧩 Roadmap (High-Level)
Phase 1 – Revival & Stability

✔ Core loads on modern Retail

✔ Setup UI accessible

⏳ Installation flow stabilization

⏳ Central Compat.lua implementation

Phase 2 – Cleanup & Refactor

Reduce legacy code paths

Improve module isolation

Prepare Classic compatibility layer

Phase 3 – Reborn Identity

Optional UI/UX improvements

Performance optimizations

New modular features (e.g. MinimapButton Reborn)

🙏 Credits & Respect

This project is based on the original MayronUI, created and maintained by Mayron.

All original credits, design concepts, and community contributions remain respected and preserved.
This revival exists to keep the UI usable for the community on modern clients.

🚧 Disclaimer

This project is under active development.

If you are looking for a fully stable UI for daily use, please wait until the first stable release.
Bug reports and testing feedback will be welcome once the foundation phase is complete.
