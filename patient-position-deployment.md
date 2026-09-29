# Patient position guide deployment

- Repository: `jinsul-lab/support`
- Stable public URL: https://jinsul-lab.github.io/support/patient-position.html
- Entry point: `patient-position.html` on `main`.
- Hosting: existing GitHub Pages, publish from `main` at repository root.
- Assets: `position-assets/` (24 generated illustrations; reused across 88 regional variants).
- Current release: `1.1.0` (2026-09-29).

## Future updates

Replace `patient-position.html` and changed assets in this same location, commit and push to `main`, then verify the GitHub Pages build and the stable public URL. Do not create dated/versioned page URLs or change the repository/Pages location.

Update the `application-version` meta tag, `APP_VERSION`, visible footer and current release above together. Image URLs include APP_VERSION to refresh cached images when a new release ships. Preserve `jw365-position-studio-v4` local storage keys unless an explicit schema migration is supplied; app releases alone must not reset saved settings.

Saved targets, markers and notes live in the visitor's browser, not in GitHub. Use JSON export/import when moving from the local-file version or to another device/browser. The static site does not synchronize clinical settings between computers.

Publish only the HTML and generated assets. Do not upload the original patient-photo PDF, source photos, local exported configurations, or scratch files. Existing calendar and other support tools must remain unchanged.

The illustrations are preparation aids and broad surface-region examples, not verified needle-entry maps or patient-specific anatomy. PDF-sourced hospital poses and additional review poses are distinguished in the UI.

Release 1.1.0: Patient injection positioning title, editable hospital collaboration with JINSUL, self-hosted Paperlogy fonts with OFL license, configurable A4 education printing, fixed copyright year 2020.
