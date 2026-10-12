# SignupForm

The "Join Our Mailing List" form: email and postal code on a dark ground, a teal Subscribe button and Manrope consent text.

**Consumer provides:** a `form.vt-signup` with a `vt-title` heading, `input.vt-field` elements each with a label (visually hidden is fine), a `button.vt-submit`, and a `p.vt-fine` consent line. Handle submission yourself.

- Fields are transparent with a 3px `jadestone` underline and white text; there are no boxed inputs.
- The submit is uppercase `button-submit`, `jadestone` fill, `radius-25`, 18px × 50px padding. The live site sets it in Roboto; this system uses Poppins.
- Ask only for email and postal code. The consent line is `fine-print` and starts "By providing your email address, you agree to receive…".
