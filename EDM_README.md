# Haberfield Dental — October Invisalign Smile Event EDMs

Two production-ready HTML emails for the practice patient database,
styled to match offer.haberfielddentists.com.au.

## Files
1. haberfield-edm1-its-back.html
   - Announcement: "It's back." (by overwhelming demand angle)
   - Suggested send: week of 8 September 2026
   - Subject options:
     - It's back. The Invisalign Smile Event returns 16-30 October
     - You asked, it's back. $2,000 in Invisalign inclusions
     - Back by demand: our Invisalign Smile Event returns for two weeks only
   - Preheader: Back for two weeks only, 16 to 30 October. Book your free
     consult and claim up to $2,000 in inclusions.

2. haberfield-edm2-now-open.html
   - Event open reminder: "It's on."
   - Suggested send: Thursday 16 October 2026 (event open day)
   - Subject options:
     - It's on. The Invisalign Smile Event is now open
     - Doors open today: $2,000 in inclusions, two weeks only
     - Your free consult window is now open (closes 30 October)
   - Preheader: The doors are open. Book your free consult before 30 October
     and claim up to $2,000 in inclusions.

## Technical notes
- 620px table layout, inline styles, Outlook VML button fallbacks,
  mobile stacking under 640px, hidden preheaders.
- Fonts: Montserrat / Plus Jakarta Sans via Google Fonts import where
  supported, Helvetica/Arial fallbacks elsewhere (Gmail, Outlook).
- Merge tags are Mailchimp format: *|FNAME|* and *|UNSUB|*.
  Swap if sending from a different platform.
- Images are hosted:
  - Logo: https://offer.haberfielddentists.com.au/assets/logo.png
    (resolves once the October landing site is deployed)
  - Hero + Dr Matt photos: hosted S3 URLs, already live.
- All CTAs point to https://offer.haberfielddentists.com.au
- Legal footer uses the approved wording: consultation "recommended",
  inclusions for consults booked 16-30 October who proceed.
