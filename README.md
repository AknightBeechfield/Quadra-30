# Quadra 30 Years Timeline

A self-contained, horizontally-scrolling "30 Years of Innovation" timeline
for Quadra®, built as a single HTML file ready to embed in Drupal (or any CMS).

## Files

- **`quadra-30-years-timeline.html`** — the standalone timeline. One file, no
  external CSS/JS dependencies. Fonts are embedded (base64). Era imagery loads
  from the Beechfield Media Hub.

## Features

- Filmstrip of four eras (1990s → today) with a navigable spine/progress track.
- Interaction: drag-to-pan, vertical-wheel → horizontal scroll, prev/next
  controls, and click-to-focus on panels or year ticks.
- Vanilla JavaScript, zero dependencies — drops straight into a page.

## Embedding in Drupal

The timeline lives entirely inside the `#quadra-timeline` markup plus the
`<style>` / `<script>` blocks in the HTML file.

1. Open `quadra-30-years-timeline.html`.
2. Copy the `<div id="quadra-timeline"></div>` element together with the
   `<style>` and `<script>` blocks into a **Full HTML** block, or paste the
   whole file into a Custom Block / WYSIWYG source view.
3. Save. No additional assets are required — fonts are inlined.

## Swapping era imagery

Each era's photo is referenced by an `image:` URL inside the `ERAS` array in
the `<script>` block. Replace those Media Hub URLs to point at different
assets.
