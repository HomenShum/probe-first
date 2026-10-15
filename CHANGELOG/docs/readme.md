# Changelog — README.md

> **Surface**: The product-reference links a developer follows from the README.
> **Append rule**: Add dated entries at the top; preserve earlier entries. Use [TEMPLATE.md](../TEMPLATE.md).

## 2026-10-15 — Link named products to their repositories
The Parity Studio and FeatureClipStudio labels now lead to their canonical repositories rather than the owner's profile. Fresh GitHub repository metadata and exact-revision READMEs establish both destination identities; no new product URL or direct code path was guessed.
**Commit**: resolve through Git history for this path. **Author**: Codex.
**Validation**: The same frozen source checker changed from three passes/two failures to five passes/no failures; restoring either old profile link was rejected. Other original files, media, contracts and installed skill were unchanged.
**Limits**: The original profile URLs were valid pages but the wrong destination for these labels. This does not rerun the referenced product tests, validate historical clip counts, or certify a deployment.
