# New Meat Blog

Astro-powered editorial site for `newmeat.ch`.

## Commands

- `npm install`
- `npm run dev`
- `npm run build`

## Publishing

Weekly Clean Meat posts live in `src/content/blog/` as Markdown files.

Recommended workflow:

1. Generate or review the Saturday Clean Meat Weekly report in `memory/clean-meat/YYYY-MM-DD.md`.
2. Convert the generally relevant sections into a public blog post.
3. Use double quotes for YAML frontmatter strings that contain apostrophes such as `1'000`.
4. Run `npm run build`.
5. Commit and push.
