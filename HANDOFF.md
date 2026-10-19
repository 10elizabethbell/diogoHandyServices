# Diogo's Handy Services — handoff at ~60%

**Live:** https://10elizabethbell.github.io/diogoHandyServices/ · **Repo:** https://github.com/10elizabethbell/diogoHandyServices · **Built:** 2026-10-19 from Muse brief of 2026-10-19 (Facebook group "Businesses in Middlesex County" ad post)

## What's built
- One page (`index.html`, inline CSS/JS, images in `img/`), phone first.
- **World:** Diogo's own logo navy, painted as a wall. The hero is a canvas of a scuffed navy wall (hairline cracks, nail holes, one drywall/doorknob hole, rub marks low down). A paint roller with a gold grip rolls a fresh royal-blue coat in W strokes by itself, drips run, and the visitor takes over: mouse hover rolls on desktop, finger drag rolls on phones (any direction, canvas rect read every frame, pull-to-refresh off). After 5s idle the fresh coat slowly fades back so there's always something to fix.
- **Carried down the page:** every section edge is a ragged roller edge with spatter, laid left to right by a small roller as it scrolls into view. The fresh coat's royal blue *is* the services band.
- **Sections:** header (logo, tap-to-call 908-764-8253 top right) → hero ("Small repairs. A big difference.", promise, gold *Text me a photo* + outlined *Ask for a price*) → *How can I help?* (his 9 flyer services; each row opens a pre-filled text naming that job) → *How it works* (3 big-numeral steps from his own "send pictures" process) → *Before & after* (his caption line + big Facebook button "Click to see more of my work.") → *Ask for a price* form (job chips, details, town, name → composes a text, opens Messages, shows the text with Copy + call fallback) → close (logo, "Your home. My care.", "Reliable. Affordable. Done right.", area, text button) → footer (name, Clark NJ, phone, Facebook).
- **Contact wiring:** `sms:+19087648253?&body=…` (URL-encoded, verified decoded) and `tel:+19087648253`. No email anywhere (none exists).
- Favicon/home-screen icon: a redraw of the logo's roof + gold window (`img/mark.svg`). og image = logo on navy, 1200x630.

## Assumptions I made
- **Owner's name is Diogo**, from the business name (brief: inferred, unconfirmed). Copy says "Write my text to Diogo" and texts open "Hi Diogo!".
- **One-person business → "I/my"**, from his caption "Your home. My care." (the flyer says "How can WE help?").
- **Texting is the preferred channel**, from "Send pictures of your project to get started with a quote." Calling stays in the header.
- **Area:** "Based in Clark, serving Union County, NJ." Clark comes from the Facebook page title ("Clark NJ"); Union County from his caption. No town list (unconfirmed).
- **Colors** sampled from the logo: navy #0d2152, royal #1d46b3, logo blue #2a7bff, gold #ffc21a.
- **Slogan:** the brief's OCR "THE LITTLE THINGS AT MATTER" is "FIXING THE LITTLE THINGS THAT MATTER." on the flyer image (checked).
- Step 2 "I send you a price" paraphrases his "Message or call for pricing" + "send pictures… to get started with a quote".
- Not flagged as a 40+ audience in the brief, so the signature motion is on. If Ellie reads his customers as older homeowners, `older-audience.md` says make the wall a still picture.

## Placeholders and gaps
- **No work photos on the page.** The before/after photos are in his group post but Facebook only exposes the flyer without a login. The *Before & after* section is a heading, his caption line and the Facebook button. Ask Muse or the owner for the pairs; the page is ready for before/after sliders there.
- No reviews, prices, hours, years in business, email, street address, insurance: none are mentioned on the page.
- Logo came from his Facebook profile image (black background keyed out). A transparent original from him would be crisper.

## Questions for the owner
- Can you send the before-and-after photos (and permission to post them)?
- Is it just you, and is "Diogo" how customers should address you?
- Which towns do you actually cover, and how far will you drive?
- Hours / how fast you usually reply to texts?
- Which jobs do you want more of (so they can go first in the list)?
- Do you want an email address on the site (footer only)?

## Ideas not built (yours to pick)
- **Runner-up world: drywall patch.** Same wall, but the finger is a putty knife that skims spackle over the holes and cracks, then they dry white. My top-ranked direction; the dice assigned the roller.
- Other candidates: a fridge to-do list of sticky notes you tick off ("Let's get it checked off your list"); a pegboard tool wall whose tools swing when you brush them; a spirit level whose bubble follows tilt.
- Before/after sliders (plain gold divider) once photos arrive, one under each matching service on phones.
- A self-hosted heavy block face to echo the logo lettering (craft floor asks for one; house style keeps the system stack).
- A small reward when a service row is tapped (a roller swipe of royal across the row).
- Swap the hero fresh-coat color for a lighter "after" color if Ellie wants a bigger before/after contrast.

## Not verified
- Real-device touch on iPhone/Android and inside Facebook's in-app browser (tested with simulated touch/mouse sweeps in headless Chrome at 360/390/430/1440).
- SMS handoff with body on real iOS and Android Messages apps.
- Canvas frame rate on old phones (DPR capped at 1.5; loop pauses off screen).
