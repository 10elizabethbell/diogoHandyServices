# Diogo's Handy Services — handoff at ~60%

**Live:** https://10elizabethbell.github.io/diogoHandyServices/ · **Repo:** https://github.com/10elizabethbell/diogoHandyServices · **Built:** 2026-10-19 from Muse brief of 2026-10-19 (Facebook group "Businesses in Middlesex County" ad post)

## What's built
- One page (`index.html`, inline CSS/JS, images in `img/`), phone first.
- **World:** Diogo's own logo navy, painted as a wall. The hero is a canvas of a scuffed navy wall (hairline cracks, nail holes, a doorknob hole, rub marks low down). A paint roller with a gold grip works the wall like a person: a W, then straight fill strokes, with a turning nap cover and paint that thins as the roller runs dry. Drips run from a freshly loaded roller. When paint covers the doorknob hole, it turns into a knifed spackle patch under the coat ("Small repairs. A big difference." happening on screen). Between patches the roller parks for 4s while the old wall shows back through in uneven patches, then it starts a new patch.
- **Interaction:** mouse hover rolls on desktop (a resting cursor hands back to autoplay after 2.6s); finger drag rolls on phones in any direction on the open wall under the buttons. Drags that start on the headline or buttons scroll the page. Canvas rect is read every frame, pull-to-refresh is off, the canvas never rebuilds on same-size resizes. Tunables are named at the top of the wall script.
- **Carried down the page:** every section edge is a ragged roller edge with spatter, laid left to right by a small roller as it scrolls into view. The fresh coat's royal blue *is* the services band.
- **Sections:** header (logo, tap-to-call 908-764-8253 top right) → hero ("Small repairs. A big difference.", his "Fixing the little things that matter.", gold *Text me a photo* + outlined *Get a quote*) → *How can I help?* (his "Send pictures of your project to get started with a quote." + his 9 flyer services; each row opens a pre-filled text naming that job) → *How it works* (3 big-numeral steps) → *See my work* (big Facebook card "Click to see more of my work.") → *Get a quote* form (job chips that paint in when ticked, details, town, name → composes a text; on phones opens Messages, on computers shows the text with Copy) → close (logo, "Your home. My care.", "Reliable. Affordable. Done right.", area, text button) → footer (name, Clark NJ, phone, Facebook).
- **Contact wiring:** `sms:+19087648253?&body=…` (URL-encoded, verified decoded) and `tel:+19087648253`. No email anywhere (none exists).
- Favicon/home-screen icon: a redraw of the logo's roof + gold window (`img/mark.svg`). og image = logo on navy, 1200x630.

## Assumptions I made
- **Owner's name is Diogo**, from the business name (brief: inferred, unconfirmed). Copy says "Write my text to Diogo" and texts open "Hi Diogo!".
- **One-person business → "I/my"**, from his caption "Your home. My care." (the flyer says "How can WE help?").
- **Texting is the preferred channel**, from "Send pictures of your project to get started with a quote." Calling stays in the header.
- **Area:** "Based in Clark, serving Union County, NJ." Clark comes from the Facebook page title ("Clark NJ"); Union County from his caption. No town list (unconfirmed).
- **Colors** sampled from the logo: navy #0d2152, royal #1d46b3, logo blue #2a7bff, gold #ffc21a.
- **Slogan:** the brief's OCR "THE LITTLE THINGS AT MATTER" is "FIXING THE LITTLE THINGS THAT MATTER." on the flyer image (checked).
- Steps are paraphrased from his own process: "I send you a quote" / "Based on your pictures." (from "Send pictures of your project to get started with a quote.") and "Done right, with care for your home." (from "Done right" + "Your home. My care."). No turnaround, price or guarantee promises.
- Not flagged as a 40+ audience in the brief, so the signature motion is on. If Ellie reads his customers as older homeowners, `older-audience.md` says make the wall a still picture.

## Placeholders and gaps
- **No work photos on the page (top gap).** The before/after photos are in his group post but Facebook only exposes the flyer without a login (I stopped short of probing neighbouring photo IDs; that was blocked as scraping). *See my work* is a heading and the Facebook card. Ask Muse or the owner for 2–3 pairs; before/after sliders go there.
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

## Review status
- Impeccable modes run (read-only reviewers, fixes applied by me): critique, audit, harden, optimize, adapt, polish, layout, typeset, colorize, clarify, distill, quieter, bolder, animate, delight, overdrive; finish reviewer twice. Not run: live (needs you in the browser), onboard (no first-run flow), extract (one page, nothing to extract yet), shape/init (PRODUCT.md written up front).
- Finish review round 2 left four items, all fixed after it in one last batch but **not re-scored** (two-round budget): the wall must not read as a letter (now arrives mid-job with W + fills overlapped), the patch must read as filler (now hard-edged matte with knife drags), the parked roller must stay on the phone screen (strokes and park shortened), and proof of motion (two real canvas frames 2s apart now differ: `.impeccable/review/motion-pair.png`, `phone-pair.png`).
- Kept against reviewers: "Click to see more of my work." (your wording), How it works (cut was offered; kept minus invented lines), system font stack.
- Detector leftovers, ignored with reasons in `.impeccable/config.json`: navy text-shadow behind hero text (readability over the wall), full-bleed band "cramped padding", the caps tagline, Roboto in the system stack; one 1.22x line-height on a short label.
- Optimize idea not done: collapse the wall's mask/tmp canvases into one paint canvas (~40% less canvas memory). Phones already get DPR 1.25.

## Not verified
- Real-device touch on iPhone/Android and inside Facebook's in-app browser (tested with hit-tested simulated touches in headless Chrome at 360/390, mouse at 1440). Headless `shoot.sh` motion frames come out identical for this page; motion was proven with canvas grabs instead.
- Whether the 40% of the first phone screen that paints instead of scrolling annoys real visitors (house rule says it should paint).
- SMS handoff with body on real iOS and Android Messages apps.
- Canvas frame rate on old phones (DPR capped at 1.5; loop pauses off screen).
