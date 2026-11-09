# Branding Center

An interactive HTML prototype of Branding Center, the brand definition in
Settings that every email, landing page and popup reads from. Built at Keap,
acquired by Thryv. All data is demo data for a made up florist, Harbor Bloom.

Open `index.html` in a browser. No build step, no dependencies.

## The flow

1. **Settings.** Branding Center lives in Settings, as one source of truth.
2. **Thryv AI setup (concept).** Type a website and Thryv AI finds the logos,
   colors and fonts, fills the Branding tab as it goes, and drafts the style
   guide. It can also start from the Style guide tab, where the preview
   changes step by step.
3. **One decision is yours.** The website logo differs from the business
   profile logo, so the owner picks the primary. Only one logo is primary.
4. **See it spread.** Changing the primary logo updates every surface that
   reads it: the landing page and email builders (both made by a third party),
   the popup builder and shared content. Nothing is copied.
5. **Inside the builders.** The logo block follows the primary logo, button
   styles come from the style guide, and brand colors sit in the color picker.
   The email builder blocks custom fonts, because most inboxes cannot show them.

It also covers logo upload and its errors, logo settings, delete with a
placeholder fallback, the color picker with a duplicate check, the 8 logo and
18 color limits, and Synced block.

## Deep links

`#brand`, `#review`, `#built`, `#style`, `#style-setup`, `#lp`, `#email`,
`#spread`

## Notes

The brand face used in the product is not web hosted, so the interface falls
back to Figtree. The builders keep their own vendor UI.
