# sriharshakaramchati.github.io

Personal site of Sriharsha Karamchati: a minimal dev-notebook. Work at Reclaim
Protocol / Popcorn, the project archive, writing and talks, a decade of
one-liners (monologues), a creative playground, and a support page for
children's cancer care.

## Structure

Plain static HTML + one stylesheet. No build step, no dependencies.

- `index.html` - home: whoami terminal, thesis, verified claims (each with a
  proof link), directory listing
- `work.html` - Reclaim Protocol, Popcorn, the verifiable-AI stack
- `projects.html` - tools and experiments archive
- `writing.html` - talks, threads, essays, videos
- `monologues.html` - one-liners since 2017, public subset of the Monologues
  chat. Newest last; (t) = translated from Telugu
- `playground.html` - creative side quests (Sanatana Power, Learn AI with TFI,
  monologues-to-songs)
- `support.html` - donations to a children's cancer fund. DISABLED ("opening
  soon") until the fund's official name, legal recipient, payment rail,
  receipts/refunds, donor-data handling, and hospital-approved wording are
  confirmed. Do not add any payment collection before that.
- `style.css` - all styling (dark default, light via prefers-color-scheme)

## Design

Terminal/notebook aesthetic: monospace everywhere, single accent color,
shell prompts as section markers, log-style entries. Keep it plain.

## Deploy

GitHub Pages: Settings -> Pages -> serve from the default branch, root.
Works as-is at https://sriharshakaramchati.github.io and behind a custom
domain later via a `CNAME` file.

## Edit

Content edits are plain HTML. Keep the support page free of payment links
until the fund setup is officially approved. Only add monologues entries the
site owner wrote and approved for publication.
