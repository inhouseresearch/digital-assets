# In-house Research: Digital Assets

Public images and files used in In-house Research email templates and live online surveys, served through GitHub Pages.

**Base URL:** `https://inhouseresearch.github.io/digital-assets/`
Example: `https://inhouseresearch.github.io/digital-assets/client-logos/wain-homes-logo-colour-730w.png`

> Everything in this repo is public. Don't add anything confidential, respondent data, or files we don't have rights to use.

## Structure

| Folder | What goes in it |
|---|---|
| `inhouse/` | In-house Research brand assets (logos, email headers, signatures) |
| `client-logos/` | All client logos in one flat folder, with no subfolder per client |
| `surveys/` | Survey-specific media. Create a folder only when a survey needs its own assets, e.g. `surveys/medway-council-tsm-2026-27/` |
| `shared/` | Reusable survey components: buttons, rating scales, icons |
| `_retired/` | Assets no longer in use, kept for reference |

## Naming rules

- Lowercase letters, numbers and hyphens only. No spaces, underscores or capitals.
- Client logos follow `client-asset-variant-size.png`, e.g. `medway-council-logo-colour-400w.png`, `taylor-wimpey-logo-white-200w.png`
  - **client**: short name (`medway-council`, `wain-homes`)
  - **asset**: `logo`, `banner`, `header`…
  - **variant**: `colour`, `white`, `mono`, `stacked`, `horizontal`
  - **size**: width in pixels followed by `w` (`200w`, `400w`)
- Survey folders follow `client-survey-year`, e.g. `medway-council-tsm-2026-27`
- Shared assets describe what they are: `button-start-survey-blue.png`, `scale-smiley-5pt.png`

## Never overwrite a live file

Emails we've already sent and surveys that are running link straight to these URLs. If you replace a file, every one of those places changes. Browsers and email clients may also keep showing the old cached version.

To update an asset, upload it as a new version: `medway-council-logo-colour-400w-v2.png`. Then point new templates and surveys at the new file and leave the original where it is.

## Retiring assets

Move a file to `_retired/` only when you're sure no live survey or recent email template still uses it. **Moving a file breaks its URL**, so images in emails already sent will stop showing. If in doubt, leave it where it is.

## Adding an asset

1. Check `client-logos/` or `shared/` for something you can reuse.
2. Name the file using the rules above.
3. Prefer PNG, at the width it will actually display. Keep files under ~200 KB.
4. Commit to `main` with a short message, e.g. `Add Medway Council white logo 400w`.
5. Wait a minute or two for GitHub Pages to publish, then check the URL in a browser before using it.

## Contact
Tom Weston: tom.weston@inhouse.uk.net
