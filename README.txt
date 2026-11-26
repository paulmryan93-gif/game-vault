GAME VAULT 6.0 — initial upgrade
1. Export a JSON backup in your existing app before upgrading.
2. Upload index.html, ultimate.js, sw.js, manifest.webmanifest, icon-192.png and icon-512.png to the existing game-vault repository root. Do not replace the Cloudflare Worker.
3. Wait for GitHub Pages deployment. Close and reopen the app; if stale, refresh in Safari. Do not delete website data.
4. Open Settings, enter keys and enable remembering if desired. Sync library. Check Match Centre.
5. Hunt: create manual counters. Scan: check title or barcode; unknown codes can be linked manually. Camera fallback needs online CDN access and has not been tested on iPhone.
Existing storage keys retained. Backups include games, manual showcase, title history and counters, not API keys. Saved keys are unencrypted local storage. Keep backups private.
Limitations: initial release, no live price lookup, online barcode product identification, individual achievement fetching/rarity, automatic grind unlock verification, screenshot attachments, session timers, full annual recap or verified warning feeds. Lifetime score is title-history sum, not official profile score. Matching remains conservative. Browser and live API testing not performed.
