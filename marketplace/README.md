# Darling Runtime — External Marketplace Package

This folder contains platform-neutral listing material for publishing **Darling Runtime** on an external plugin, extension, or developer-tool marketplace.

## Product summary

Darling Runtime is a skills-only package for working with compatible macOS command-line software on Linux. It bundles selected Darling runtime components for Ubuntu 24.04 amd64 and focuses on CLI tools, Mach-O binaries, compilers, and developer workflows.

## Included marketplace material

- `listing.json` — machine-readable listing metadata
- `DESCRIPTION.md` — long-form product description
- `CHANGELOG.md` — release notes
- `INSTALLATION.md` — installation and compatibility information
- `SUPPORT.md` — support/contact information
- `SECURITY.md` — vulnerability reporting guidance
- `assets/icon.png` — marketplace icon
- `assets/ASSET-GUIDE.md` — optional screenshot/banner guidance
- `legal/PRIVACY.md` — privacy-policy pointer
- `legal/TERMS.md` — terms pointer
- `legal/LICENSES.md` — licensing notice

The actual plugin/runtime files should remain in the main repository/package rather than being duplicated here.

## Important

Each marketplace has its own required manifest, image dimensions, review process, signing rules, and category names. `listing.json` is intentionally platform-neutral and can be mapped to a marketplace-specific format later.
