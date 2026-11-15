COURT DROP v5.6 — Verified Courts & Photography

FILES
index.html : standalone, mobile-first website.
COURT_VERIFICATION_AUDIT_v5_6.csv : 547-record source/evidence checklist.
PHOTO_RIGHTS_v5_6.csv : credits for eight venue-specific Commons images and the CC0 generic photograph.

CHANGES
- 547 existing IDs / names retained; no new game or booking features.
- 64 San Francisco courts and 7 Hong Kong venues independently checked against official source listings.
- Court card identifies confirmed facts vs directory-linked / needs review.
- Two optional filters: confirmed-only (blind box and My Courts).
- Eight source-matched venue photographs with Creative Commons attribution; external photos with unverified reuse rights are withheld.
- Other courts use CC0 generic tennis photo with embedded original illustration if offline.
- Existing uploads, passport localStorage, indexedDB, journal, challenges and backups remain unchanged.

LICENSING / DATA LIMITATIONS
Verified venue photos load from Wikimedia Commons when online; licence, photographer and original source are visible in each card. Licence source links are listed in PHOTO_RIGHTS_v5_6.csv. Photos are NOT bundled into the ZIP; the site handles network failures gracefully. Licence availability can change; the listed terms were checked against Commons pages on 2026-11-15. 476 venues are still not individually checked, and unverified details may be inaccurate. For public publication perform a follow-up audit against fresh sources.

DEPLOY
Download and export a full passport backup in previous version first. Upload index.html to the same GitHub Pages address. No hosting dependency for app logic; user photographs and saved data live on the same browser and origin. 
