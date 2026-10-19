# ShannonSaves — handoff at ~60%

**Live:** https://10elizabethbell.github.io/shannonSaves/ · **Repo:** https://github.com/10elizabethbell/shannonSaves · **Built:** 2026-10-19 from Muse brief 2026-10-19 (Burlington County NJ group post, 2026-10-18)

## What's built
- One page, `index.html` (single file, ~65 KB including her portrait), phone first: header ($hannon$aves wordmark + `(609) 784-4976` tap-to-call top right) → hero → What I do + How it works → Hi, I'm Shannon (portrait, Facebook link) → Free quote form → close + footer.
- **World: afternoon sun in a clean room.** Her flyer's navy is the room, its cream ring is the window light, its lime is the lettering and buttons, its pale dots became dust motes. Navy "rooms" (hero, meet, close) carry the light; cream sections are the dust-free clean rooms.
- **Signature element:** a soft shaft of window light (four panes with the cross-bar shadow, landing as a bright window shape at the bottom of the hero) with dust drifting in it. Motes only light up inside the beam, like real dust. Finger or mouse stirs the air (a small fluid grid, so swirls trail and spread) and wipes the motes it passes out of the light; they drift back in over time (`DUST.REGROW`). With no input for 4.5s the room's own breeze wanders through it. The light slowly dims and brightens as if clouds pass. Text sits in a cleared pool; the beam is cut out behind it. All tunables are in `DUST` and `BEAMS` at the top of the script.
- **Contact:** header number is `tel:`. "Text me" and the close button open a text with a greeting. Each service row opens a text naming the service (on a computer it jumps to the form with that service ticked). The form (name, town, services required; home size, days, notes optional) composes one text to her, with a copy fallback and a "Rather talk? Call" link. Email is in the footer only.
- Favicon / home-screen icon: a lime `$` on navy, from her flyer's lettering (no logo file exists). `og.jpg` 1200x630 for the Facebook link preview.

## Assumptions I made
- **Shannon is the owner and works alone** → "I" voice. Inferred from the business name, her portrait on the flyer and the post coming from her profile. Brief says relationship unconfirmed.
- **Her portrait is used** (cropped from her own flyer, not upscaled: 254px source shown at 176/240px, so slightly soft on 3x phones). She put it on her public ad; still confirm she's happy with it on the site.
- **Headline "Peace of mind, time & money."** is her tagline. The promise line ("I clean your home the way I'd want my own cleaned: carefully, reliably, and with respect for everything in it.") and the meet-section paragraph are mine, built from her words "reliable and trustworthy". Confirm they sound like her.
- **How it works** steps ("I'll get back to you with a price before anything is booked") are inferred from "Free Quote".
- **Texting:** brief says texts are unknown. Text is the main handoff, so the header `tel:` link and the form's "Rather talk? Call" cover callers. Confirm her number takes texts.
- **Colors** sampled from the flyer: navy `#0e3b66`, lime `#a6ec6c`, cream `#f7f0d9`. Form focus is blue `#2b78d8` (lime doesn't show on cream).
- **Name casing:** "ShannonSaves", drawn as $hannon$aves like the flyer; screen readers hear "ShannonSaves".

## Placeholders and gaps
- No service area on the page (brief: don't publish one). The form asks the customer's town instead.
- No work photos, before/afters, reviews, prices, hours or years in business; the page says nothing about them.
- Facebook link goes to her personal profile (no business page exists).

## Questions for the owner
- Spelling: ShannonSaves, one word? OK to show the $ lettering?
- Does (609) 784-4976 take texts?
- Which towns does she cover? Hours?
- Any photos of homes she's cleaned or organized (before/after especially)? Any reviews from customers she could share?
- Does she want a business Facebook page linked instead of her personal one?
- Any first-time or recurring-customer offer?

## Ideas not built (yours to pick)
- **Runner-up world: the kitchen sink.** Lime dish-soap suds over warm water at the bottom of the hero, bubbles you swirl and pop. Close to Blessed's foam, which is why it lost.
- A visible microfiber cloth or feather duster following the finger, so wiping the dust reads even faster.
- Animated seams between navy and cream sections (e.g. the edge of the light spilling over the boundary).
- Before/after slider once she has photo pairs; a reviews strip once she has reviews.
- A "Bi-weekly" explainer (what's included each visit) if she shares a checklist.

## Not verified
- Real-device touch (simulated touch sweeps in headless Chrome wiped 60 of 420 motes in 2s; mouse 44), the SMS handoff on real iOS/Android, frame rate on old phones, Facebook in-app browser specifically.
