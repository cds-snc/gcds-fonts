# 📝 Summary | Résumé

_TODO:_
- Provide a concise summary of the change(s).
- Explain why this change is needed (motivation/context). Provide enough context for anyone reviewing this PR now or in the future.
- Include screenshots or previews where applicable (e.g., icon set diffs, specimen screenshots).
- If applicable, include specifications, design references, or related documentation.
- If this change impacts consumers, call it out explicitly (paths, filenames, font-family names, icon names/mappings, CDN URLs).

## 🧩 Related Issues | Cartes liées

_TODO: Link to related issue(s) that this PR addresses or fixes, e.g. "Closes #124", "Fixes #456"._

- Issue #
- Zenhub issue:


## 🧪 Test instructions | Instructions pour tester la modification

_TODO: Replace the instructions below as needed. Describe any steps required to verify the changes work as expected._

### Build / packaging validation
- [ ] Install dependencies (if applicable): `npm ci`
- [ ] Run build/package step (if applicable): `npm run build`
- [ ] Confirm the expected artifacts are produced (fonts/icons in expected formats and folders)

### Consumer validation (pick what applies)
- [ ] Verify import/usage from NPM works in a sample project (font-face loads, icons render)
- [ ] Verify assets served via CDN load successfully (no 404s, correct MIME types)
- [ ] Verify cache behaviour is acceptable (new assets accessible after deployment/invalidation)

### Visual sanity checks (where applicable)
- [ ] Verify the updated font renders correctly (weight/style/characters as expected)
- [ ] Verify icons render correctly and mappings match expected glyphs (if applicable)
- [ ] Verify file sizes are reasonable (no unexpected bloat)


## ✍️ Author checklist | Liste de vérification de l'auteur

**Choose one (SemVer / release type):**
- [ ] This PR is a patch (use `fix:`) — typo fixes, metadata fixes, new files that do not change existing consumer-facing behaviour.
- [ ] This PR introduces a minor change (use `feat:`) — additive changes (new font family, new icons, new weights/styles) without breaking existing usage.
- [ ] This PR introduces breaking changes (use `feat!:`) — removing/renaming fonts/icons, changing paths/filenames, changing `font-family` names, changing icon names/mappings, or anything that breaks existing consumers.
- [ ] This PR does not introduce changes that need to be published (use `chore:`, `docs:`, `ci:`).

---

**Breaking / impact flag:**
- [ ] This PR does not remove, rename, or change consumer-facing assets (paths, filenames, font-family names, icon names/mappings).
- [ ] If it does, migration guidance (and/or redirects/compat shims where possible) is documented under **Impact/Risks**.

---

**Ready for review (all items must be checked):**
- [ ] I have verified the folder and naming conventions are followed (e.g., `icons/`, `lato/`, etc.).
- [ ] I have verified required formats are present and correct (as applicable: `woff2`, `woff`, `ttf`, `eot`, `svg`).
- [ ] I have verified `font-family` names and metadata are correct and consistent (where applicable).
- [ ] I have verified icon names/mappings are correct and stable (where applicable).
- [ ] I have verified assets load correctly from the intended delivery path (NPM and/or CDN).
- [ ] I have confirmed licensing/attribution requirements are satisfied (if applicable).
- [ ] I have added or updated documentation as needed.
- [ ] I have ensured test instructions are clear and reproducible.

## 🧐 Reviewer checklist | Liste de vérification du réviseur

**Developer checklist (if applicable)**

For complex PRs, in lieu of a simple approval or "LGTM" ✅, include the following with your approval:

- [ ] I have verified the artifacts and structure match repo conventions (folders, filenames, formats).
- [ ] I have verified the build/package output (if applicable) looks correct and complete.
- [ ] I have verified consumer-facing paths/names/mappings remain stable (or are clearly documented as breaking).
- [ ] I have reviewed changes for maintainability and potential issues (size, duplication, incorrect formats).

---

**Design checklist (if applicable)**

For designers, include the following with your approval:

- [ ] I have verified the font/icon visuals match the intended source and specs.
- [ ] I have verified icons map to the expected glyphs and naming is consistent (if applicable).
- [ ] Any design inconsistencies have been raised in Slack or tracked via an issue.

---

**Content / Documentation checklist (if applicable)**

For documentation reviewers, include the following with your approval:

- [ ] I understand the context and intent of the change.
- [ ] I have reviewed usage guidance and examples for clarity.
- [ ] I have verified English and French documentation for accuracy and parity (if applicable).
- [ ] Links and references are correct and functional.

## ⚠️ Impact/Risks | Risques

_Optional: Highlight any potential implications, risks, or important notes for reviewers or maintainers (e.g., breaking path/name changes, icon mapping changes, CDN cache implications, package size impacts, licensing changes, dependency updates, etc.)._
_Highlight any deprecations or migration guidance here._
