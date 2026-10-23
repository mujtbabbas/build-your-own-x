# Changelog

All notable changes to this standalone edition of build-your-own-x are documented in this file.

## v1.1.0 — Standalone enhancements (2026-10-20)

- Converted the repository from a fork into a standalone edition with its own history, keeping full upstream credit.
- Added an "About This Standalone Edition" section to `README.md` with the upstream link, base-version provenance, and credit.
- Added `ENHANCEMENTS.md` documenting everything changed in this edition.
- Added `.github/dependabot.yml` for weekly GitHub Actions dependency updates.
- Added markdown linting automation (`.markdownlint.json` and the Markdown check workflow); the check was later scoped via `.markdownlint-cli2.yaml` so it covers this edition's own documentation instead of failing on upstream content.
- Added `.editorconfig` with standard editor settings (UTF-8, LF, 2-space indent).

## v1.0.0 — Upstream baseline (2026-10-20)

- Clean standalone baseline of [codecrafters-io/build-your-own-x](https://github.com/codecrafters-io/build-your-own-x) at upstream commit `aa17439b62f384511a5561ce308e9598b94d8989` (upstream HEAD dated 2026-07-14).
- Fork history severed; all files preserved as-is. No standalone licence file exists in the upstream tree (the CC0 waiver is stated in the README "Origins & License" section only).
