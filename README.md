# Listings Management · interactive prototype

A portfolio showcase of Listings Management, the screens a small business owner uses to keep their listings right on Google, Yelp, Apple Maps and every other site that shows them.

The idea behind it: the screens sit on a layer between our UI and the listings vendor's API. The **Backend** switch in the top bar swaps Vendor A for Vendor B. Each vendor sends its own status values, the layer turns them into the same four statuses, and the owner sees the same screens either way.

## What you can do

- **Fix a listing that doesn't match.** Open Apple Maps, see which fields differ, and let Thryv AI draft the corrections. You approve them before anything is sent. *(Concept)*
- **Ask Thryv AI** what to fix first, which listings have issues, or for a reply to your worst recent review.
- **Disable or disconnect** a listing. The dialog shows what each one does and which one can't be undone.
- **Edit hours with a break** inside the day, instead of splitting the day into two blocks.
- **Write a description with Thryv AI.** *(Concept)*
- **Connect** the sites that don't list you yet, switch between three locations, and filter by status.

Demo deep links: `#issue`, `#fix`, `#ai`, `#reply`, `#hours`, `#desc`, `#off`, `#vendor`, `#gilbert`.

## Notes

- Demo data only. Ridgeline Roofing is a made up business, and the addresses and phone numbers are fictional.
- No listings vendor is named. Vendor A and Vendor B, and the status values they send, are illustrative.
- The AI is scripted. There's no model or API key behind it.
- Fonts are Inter, Inter Tight, Montserrat and Open Sans from Google Fonts.
- One standalone `index.html`. Open it in a browser, or serve the folder.

Designed by Denise Barrett. Case study at [dbyxdesign.com](https://dbyxdesign.com/case-business-listing.html).
