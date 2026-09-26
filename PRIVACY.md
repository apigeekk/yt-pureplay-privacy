# Privacy Policy — YT PurePlay

**Last updated:** 2026-09-25

YT PurePlay is a browser extension that stops YouTube from forcing videos into
Mix playlists and optionally hides distractions such as autoplay, Shorts, end
screens and recommendations.

## Summary

YT PurePlay collects no personal data and sends nothing anywhere. It has no
servers, analytics, tracking or ads. Everything it stores stays in your
browser. Settings sync between your own signed-in browsers through your
browser's built-in sync, like any other extension setting.

## What the extension stores

All data is kept with the browser's `chrome.storage` API.

| Data | Where | Synced to your other devices? |
|---|---|---|
| Your settings (which playlists to block, focus toggles, pause state) | `storage.sync` | Yes, via your browser's own sync |
| Channel whitelist (channel IDs/handles and names you chose) | `storage.sync` | Yes, via your browser's own sync |
| Redirect counter and "review prompt dismissed" flag | `storage.local` | No |
| Recent video → channel lookups (max 500, used for the whitelist) | `storage.local` | No |
| Tabs where you allowed playlists | `storage.session` | No. Cleared when the browser closes |

None of this is sent to the developer or to any third party.

## What the extension reads from YouTube

On YouTube pages only, the extension reads the page URL (to decide whether to
remove playlist parameters) and the channel name/handle shown on the page (for
the whitelist). This is processed locally and never transmitted.

## Links that leave the extension

If you click "Buy me a coffee" or "Rate it", the donation page (Ko-fi) or the
Chrome Web Store page opens in a normal browser tab. That site's own privacy
policy applies. The extension sends it nothing.

## Permissions

- **storage**: save the data in the table above
- **alarms**: resume automatically after a timed pause
- **activeTab**: read the current tab's URL when you use "Copy clean URL" or "Whitelist current channel"
- **declarativeNetRequestWithHostAccess**: rewrite Mix/Shorts URLs on youtube.com before they load
- **youtube.com host access**: run the extension on YouTube pages

## Data deletion

Uninstalling the extension deletes all local and session data immediately.
Synced settings are removed by your browser according to its sync settings.
You can also use "Reset to defaults" in the popup at any time.

## Children

The extension collects no data from anyone, including children under 13.

## Changes

Changes to this policy update the date above. The full history is in this
repository's git log.

## Contact

Questions: **llms.baar@gmail.com**
