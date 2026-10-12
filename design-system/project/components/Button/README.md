# Button

Vertui's three button styles: the gradient pill for page-level actions, the teal CTA for lead capture, and the legacy outline pill on product cards.

**Consumer provides:** an `<a>` or `<button>` with `vt-btn` plus one modifier, the label text, and for the primary pill the trailing arrow SVG with class `vt-arrow`.

| Modifier | Use for | Spec |
| --- | --- | --- |
| `vt-btn--primary` | "Learn More", "Shop Now" at the end of a section | `button-lg` type, 18px × `space-32` padding, 2px `new-yellow` border, `radius-pill`, 284deg gradient `midsummer-field` → `poisonous-ice-cream`, white label, trailing arrow at `space-10` |
| `vt-btn--cta` | Header "Contact a Specialist", popup triggers | `button-cta` type, `space-16` × `space-20` padding, `jadestone` fill, `radius-12` |
| `vt-btn--cta vt-btn--hero` | The larger CTA in a hero row | 16px, `space-20` × 28px padding |
| `vt-btn--outline` | "Learn More" on product cards | `button-sm` uppercase, `sage` text and 2px border on white, `radius-pill` |

- Every style hovers to the same 284deg `sun` → `sky` gradient with white text. The primary pill also lifts 3px and takes `shadow-glow`.
- One primary pill per section, centred or aligned with the section's copy. Don't place two primaries side by side; pair a primary with a CTA.
- Labels are capitalised verbs: "Learn More", "Shop Now", "Join the Waitlist", "Contact a Specialist".
- On phones (≤500px) button rows stack full width with `space-12` between them.

**Accessibility:** white on the primary gradient measures 2.04:1 to 1.45:1, white on `jadestone` 2.99:1, `sage` on white 3.04:1. These are the live site's values and are kept exact here. For new work, either set the primary label in `blue-lobelia` (6.24:1 on `midsummer-field`) or raise the CTA label to 19px bold, where 3:1 passes.
