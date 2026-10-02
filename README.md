# for you 🌸

A fully automatic, no-buttons, mobile-first "I like you" page. Baby pink theme,
inspired by https://github.com/Chychyndr/i-love-you but rebuilt from scratch.
No backend — it's one `index.html` file.

## What happens when she opens it (all by itself, nothing to tap)
1. Soft pink petals start gently falling in the background right away.
2. A cute greeting fades in: "a little something, for you… 🌷"
3. A bouquet of flowers blooms open, tied with a bow, gently floating.
4. Your message types out underneath, letter by letter.
5. "I like you. always & always" glows in softly at the end.
6. Petals keep drifting forever — it's a page meant to just sit and be watched.

Total time to the ending: about 7 seconds. No buttons, no taps needed.

## How to open it
Double-click `index.html`, or open it in any browser. Works offline.
Best viewed on a phone, in portrait.

## How to send it to her
- Easiest: send her the `index.html` file directly (WhatsApp, email, AirDrop).
  She just opens it.
- To share as a link instead: drag the folder onto https://app.netlify.com/drop,
  or host free on GitHub Pages (`.nojekyll` is already included for that).

## How to edit it
Everything lives in `index.html`, in plain text:
- **The message** — search for `const MESSAGE =` near the bottom.
- **The greeting line** — search for `class="greet"` in the HTML.
- **The ending line** — search for `class="ending"`, edit the text inside `.big`.
- **Flower colors** — search for `const flowers = [` and change the hex colors.
- **Falling petal emoji** — search for `const EMOJI =`.
- **Timing** — each section has an `animation ... forwards <seconds>s` in the
  `<style>` block, or a `setTimeout(..., <ms>)` in the script. Increase the
  number to make it appear later.

## Credit
Loosely inspired by the romantic-reveal-page idea in Chychyndr/i-love-you
(MIT licensed, see LICENSE). The bouquet, layout, animation and all code here
are newly written for this version.
