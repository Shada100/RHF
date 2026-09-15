# RHF Guesthouse website

Design build for RHF Guesthouse.

## What is here

| File | What it is |
| --- | --- |
| `RHF Guesthouse Website.dc.html` | The website. Seven pages, one adaptive layout. This is the deliverable. |
| `RHF Guesthouse Laptop and Phone.dc.html` | Client review view: the same site running side by side in a browser window and a phone frame. |
| `support.js` | Runtime the two files above need. Must sit alongside them. |
| `browser-window.jsx`, `ios-frame.jsx` | The two device frames used by the review view only. |
| `assets/` | Logo, reversed logo, and five photographs. |
| `archive/` | The two earlier design directions and their print copies. Superseded, kept for the record. |

## Opening it

Open `RHF Guesthouse Website.dc.html` in a browser. No build step, no install, no server.
Everything it needs is in this folder.

## Pages

Home, Rooms, Facilities, Location, FAQs, Contact, and a Book now flow. The nav
switches between them in place.

## How it adapts

One layout, not two builds.

- Above 900px the six nav links sit inline in a 60px bar, Book now anchored right.
- Below 900px they move into a panel that opens from the right, with the current
  page marked and both phone numbers at the foot of it.
- Room cards go three across to one. The rate table scrolls sideways with its row
  labels held in place. The FAQs page drops its booking rail below the questions.
- Every tap target is 44px or larger.

## Rates

Shown VAT-inclusive everywhere, because that is the number a guest transfers.

| Room | A night | 500 to 700 ft² |
| --- | --- | --- |
| Business | N32,250 | 500 ft², double bed |
| Executive | N43,000 | 600 ft², queen bed, fridge |
| Luxury | N53,750 | 700 ft², king bed, living room suite, breakfast on arrival |

Payment is by bank transfer. There is no card payment. The account name is shown
at the point of transfer.

## Still awaiting client confirmation

These appear on the site as `[CLIENT TO CONFIRM]` rather than invented. Search the
file for that string to find every one.

- Check-in and check-out times, and whether early or late carries a charge
- Cancellation and refund terms
- Step-free access, ground-floor rooms, level-access shower
- Light and water: generator hours, inverter backup, borehole or tanker
- Weekly and monthly rates for long stays
- Distance to the Central Business District and the nearest hospital
- Bank account name

## Photographs still needed

Three slots carry a written brief instead of an image:

- The gate with its signage and Acropolis visible opposite. This is the frame that
  makes the written directions land.
- The kitchen in use.
- The mini-mart shelf, stocked.

The Facilities gallery currently reuses the Luxury room photograph as a stand-in.

`room-business.jpg` and `room-luxury.jpg` are only 640×480 and look soft at the
sizes the page asks of them. Worth reshooting with the other three.

## Writing conventions

Carried through every page and worth keeping to.

- No em dashes or en dashes as sentence punctuation. Use a comma, a colon, a full
  stop, or restructure. Hyphens inside compound words are fine.
- Numeric ranges read "120 to 180ms", not "120–180ms".
- Never "instant confirmation", "Pay now", "Checkout", "Submit" or "Learn more".
- No airport pickup is offered anywhere. Forty minutes from the airport is a
  directions problem, not a service.
- Prices always VAT-inclusive.

## Contact

+234 802 380 4982 · +234 701 311 2962 · rhfguesthouseltd@gmail.com
