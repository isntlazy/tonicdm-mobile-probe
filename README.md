# tonicdm-mobile-probe

Throwaway Outlook add-in used to verify that an add-in renders in Outlook on iOS/Android,
and to report what the mobile host actually supports (requirement sets, `itemId` format,
available Office.js APIs).

Not a product. Safe to delete once the mobile spike is done.

- `index.html` — the task pane / probe UI
- `manifest.xml` — add-in only manifest with `<MobileFormFactor>`
- `function-file.html` — required by `MobileFormFactor`
