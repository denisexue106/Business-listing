# Listings, Reviews and Social · interactive prototype

A portfolio showcase of Listings Management, Reputation and Social, the screens a small business owner uses to keep their listings right on Google, Yelp, Apple Maps and every other site that shows them, answer reviews from every site in one place, and post and answer comments on Facebook, Instagram and Google.

The idea behind it: the listings screens sit on a layer between our UI and the listings vendor's API. The **Backend** switch in the top bar swaps Vendor A for Vendor B. Each vendor sends its own status values, the layer turns them into the same four statuses, and the owner sees the same screens either way.

## What you can do

### Listings

- **Fix listings that don't match.** Thryv AI drafts the corrections and you approve them before anything is sent. *(Concept)* With more than one listing to fix, it walks you through each one in turn. Sent fixes show as waiting until the site picks them up, then move to matching.
- **Connect** the sites that don't list you yet. You see the list first and can skip any site.
- **Edit your business profile.** Name, phone, address and categories save and go to every connected site. Required fields are checked, and closing with unsaved changes asks first.
- **Edit hours with a break** inside the day, and copy Monday to the rest of the week. Change your hours and Thryv AI offers to draft a post about them.
- **Write a description with Thryv AI**, with a few versions to choose from. *(Concept)*
- **Disable or disconnect** a listing. The dialog shows what each one does and which one can't be undone. Disabled listings get their own filter.
- Switch between three locations, search, and filter by status. Empty filters tell you why and how to get back.

### Reputation

- **See the whole picture first.** Overall rating with a star breakdown, review requests, and a card for each review site.
- **Work through reviews by site.** Tabs for Needs response, all sites and each site, with search, a date filter and a spreadsheet download.
- **Reply with a suggested draft.** Thryv AI suggests a reply that mentions what the customer wrote. Switch the tone between Friendly, Professional and Empathetic, regenerate it, or start from a template. *(Concept)* Answered reviews fold away and the next one opens.
- **Reply to many at once.** Check several reviews and Thryv AI drafts a reply for each. Edit or regenerate any of them, then publish. *(Concept)*
- Edit a reply you already sent, and add your own templates.

### Social

- **See every account** in one place, with reach, engagement, followers and comments waiting.
- **Fix a post that didn't go out.** Instagram skipped one because it had no image. Add one and it goes to Instagram only.
- **Create a post** for Facebook, Instagram, Google and Nextdoor, with a live preview for each one. Thryv AI drafts a caption from a topic and picks an image. *(Concept)* Post now, schedule it at the suggested best time, or save a draft.
- **Plan in a calendar**, or work from the list grouped by what needs you, what's coming up, drafts and published posts.
- **Answer comments.** Thryv AI drafts a reply for you to edit before you send. Hide a comment, with undo.
- Post now, duplicate or delete from any post, with undo after a delete.

### Thryv AI

- Opens with a short brief of what needs you on the screen you're on, and updates it as you act.
- Follows you between Listings, Reputation and Social, and between locations.
- Answers in plain words and takes you to the right place: fixes, connecting sites, lunch breaks, descriptions, posts, comments and review replies.
- On Reputation it starts with the negative reviews, thanks every happy customer in one go, and sums up what customers praise and complain about.
- Review replies can be rewritten shorter, warmer or more formal, and a posted reply can be undone.
- The content moves aside while the panel is open, so you can still see what it's talking about.

Demo deep links: `#issue`, `#fix`, `#ai`, `#reply`, `#hours`, `#desc`, `#off`, `#vendor`, `#gilbert`, `#social`, `#calendar`, `#compose`, `#comments`, `#reviews`, `#bulk`.

## Notes

- Demo data only. Ridgeline Roofing is a made up business, and the addresses, phone numbers, people and numbers are fictional.
- No listings vendor is named. Vendor A and Vendor B, and the status values they send, are illustrative.
- The AI is scripted. There's no model or API key behind it.
- Images are drawn in the page. There are no photos.
- Every change has motion, and it all respects reduced motion settings.
- Fonts are Inter, Inter Tight, Montserrat and Open Sans from Google Fonts.
- One standalone `index.html`. Open it in a browser, or serve the folder.

Designed by Denise Barrett. Case study at [dbyxdesign.com](https://dbyxdesign.com/case-business-listing.html).
