# HLTV Enhancements

## Firefox

Install from [Firefox Add-ons (AMO)](https://addons.mozilla.org/firefox/addon/hltv-enhancements/).

## Chromium browsers

For desktop browsers on Windows, macOS, and Linux. Requires Chromium engine
**148 or newer**; use an up-to-date browser.

1. Download [hltv_enhancements-2.3-chromium.zip](hltv_enhancements-2.3-chromium.zip).
   On GitHub's file page, click **Download raw file**.
2. Open your browser's extensions page using the address below.
3. Turn on **Developer mode**.
4. Drag the downloaded **ZIP file** from your file manager onto the extensions
   page. This is a drag-and-drop operation; **Load unpacked** is the separate
   folder-based method described below.
5. Reload any open [HLTV.org](https://www.hltv.org/) tabs.

| Browser | Extensions page |
| --- | --- |
| Google Chrome / Chromium | `chrome://extensions` |
| Microsoft Edge | `edge://extensions` |
| Brave | `brave://extensions` |
| Opera / Opera GX | `opera://extensions` |
| Vivaldi | `vivaldi://extensions` |

Type the address into the browser's address bar. Chromium supports ZIP
installation this way and extracts the files itself. Browser variants can
differ; if the ZIP is rejected or simply downloaded again, use the fallback.
Individual browser/OS combinations have not all been tested.

### Fallback: extract and load the folder

1. Extract the Chromium ZIP into a permanent folder, such as
   `Documents/HLTV-Enhancements`.
2. On the extensions page, with **Developer mode** enabled, click
   **Load unpacked**. Opera may label it **Load extension**.
3. Select the extracted folder containing `manifest.json`, then reload HLTV.org.

For this fallback, keep the extracted folder in the same location: the browser
reads the extension from it. Select the folder, not the ZIP or manifest file.

### Permanent installation and limitations

These are local Developer mode installations intended to remain installed
across browser restarts. Keep Developer mode and the extension enabled.
Developer-mode reminders may appear. ZIP installation uses a browser-managed
extracted copy; the fallback uses the folder you extracted yourself.

If a browser build, employer, or school policy blocks Developer mode or local
extensions, manual installation is unavailable there. A normal store-style
installation without Developer mode is not supplied. Mobile browsers are
outside this release's scope.

If the extension is installed but inactive on HLTV.org, open its **Details**,
allow site access on `https://www.hltv.org/*`, and reload the page.

### Updates

Manual installations do not receive automatic store updates. Export important
settings and user data from the extension before updating.

- **Installed from a ZIP:** install the newer ZIP using the same steps. A ZIP
  installation can receive a different extension identity; if a separate copy
  appears, import your exported settings/data into it before removing the old
  copy. Keep only one copy enabled on HLTV.org.
- **Loaded from a folder:** replace the files in the same folder, click
  **Reload** on the existing extension card, and reload HLTV.org. Keep the
  existing extension installed and the folder path unchanged.
