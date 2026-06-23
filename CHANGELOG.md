# Changelog

All notable changes to SlangBit will be documented in this file.

---

# Version 1.0.0

Release Date: June 2026

## Initial Public Release

SlangBit Desktop is a Windows application that enables offline translation of selected text using local AI models.

### Added

* Global translation hotkey (ALT+Z)
* Offline translation engine
* Automatic clipboard workflow
* System tray integration
* Windows startup support
* Local Package Manager
* Dynamic language package discovery
* SHA256 package verification
* Automatic language installation
* Local AI translation models
* No-cloud architecture
* Privacy-first workflow

### Translation Engine

Migrated from Argos Translate to a custom CTranslate2-based architecture.

Benefits:

* Faster startup
* Faster inference
* Reduced dependencies
* Improved packaging system
* Better long-term maintainability

### Language Packages

Supported language pairs:

* Italian ↔ English
* Italian ↔ Spanish
* English ↔ Spanish
* English ↔ French
* English ↔ German
* English ↔ Chinese

Language packages can be installed and removed directly from the built-in Package Manager.

### Package System

Implemented:

* Dynamic package discovery
* metadata.json support
* catalog.json support
* ZIP package installation
* SHA256 integrity verification
* Automatic model registration

No server modifications are required when new language packages are added.

### Social Content Preservation

Improved translation handling for:

* Hashtags
* URLs
* Mentions
* Emoji
* Social media posts

Tested with:

* X
* Reddit
* Trustpilot
* Web browsers
* Text editors
* Office applications

### Privacy

* No cloud translation APIs
* No telemetry
* No user accounts
* No tracking
* No data collection

All translations are processed locally on the user's computer.

### Known Limitations

Current release focuses on the most tested language pairs.

Additional languages may be added in future updates.

---

Copyright © 2026 Memmola Labs.

