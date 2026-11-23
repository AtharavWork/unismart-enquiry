# UniSmart Admits enquiry form

Public link: https://atharavwork.github.io/unismart-enquiry/?src=<channel>
(channel = instagram, linkedin, facebook, website, qr, whatsapp, google, youtube, referral, event)

Event sign-ups (staff phone at seminars): `?src=event&staff=<Name>` gives a "Save & next person" button and a counter.

## Files
- `index.html`: the page (logo is embedded).
- `assets/style.css`: look and feel (brand red #AC070D, Manrope).
- `assets/app.js`: behaviour. Saves the number the moment it is complete, keeps unsent saves on the phone until
  they go out, one row per visit / per different number, spam guard, event mode, optional GPS area.

The Google Apps Script that writes to the Enquiry Log sheet (repeat numbers greyed with "Repeat of row X",
fakes marked Check, bot trap marked Spam) lives in the Apps Script project "UniSmart Enquiry Page"; a copy is kept
in the private project folder, not here, so the sheet details stay private.

## Changing it
- Page: edit the files here; GitHub Pages republishes in about a minute.
- Script: paste the new code into the Apps Script project, save, then
  Deploy > Manage deployments > pencil > Version: New version > Deploy (the link stays the same).
