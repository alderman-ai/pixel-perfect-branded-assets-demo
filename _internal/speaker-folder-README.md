# Speaker folder — what goes in here

Three things. The skill refuses (or asks about placeholders) until it has them.

| file | what |
|---|---|
| `intake.md` | the form — type only in its labelled fences (or give the answers in chat and the assistant types them); the assistant fills the frontmatter from the fences. Leave the frontmatter's geometry block alone: those numbers are the template's fixed constants |
| `company-logo.(png/jpg)` | the speaker's company logo — square, ideally 80×80+ |
| `speaker.(png/jpg/jpeg)` | the speaker photo — **roughly square** (sides within 25% of each other), any size |

## The speaker photo — what's accepted

**PNG/JPG/JPEG, any size, roughly square** (width and height within 25% of
each other). A selfie cropped by eye on a phone is fine. The generator
trims the longer side evenly to an exact square (a plain centre crop),
resizes it to the photo slot (**262×262** on the current template) and
archives that copy. It never pads or stretches a photo.

A photo further from square than that, or in another format, halts the
run with its measured size and one fix: crop it roughly square and
resend.

## If an image is missing

The run stops and asks: resubmit this folder with the image added, or render
now with a dashed placeholder outline (drawn inside the block, so the real
image pasted in later covers it exactly — the logo slot keeps the card's 8px
corner rounding).

## Text limits

name 30 · position/company 39 (including the ` / ` joiner) ·
description 115 · topic 26. The audience level is fixed (`For All
Levels`) and is not typed.
The description budget is enforced from the fence label; over it, the form is
rejected rather than truncated. Everything else ellipsises.

## Filled it in yourself?

Say "done". The assistant puts the frontmatter back to the template's
text if anything up there was changed (and tells you), then asks you in
chat for anything missing or over a limit, writes your answers into the
form, and renders. Type only in the fences; the frontmatter is its job.
