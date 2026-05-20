# Site Architecture Notes

## Assumption

The user wrote "SSO optimized"; this project assumes the intended goal is SEO optimized. If single sign-on is also needed later, treat that as a separate product requirement.

## Site Goals

- Minimal and fast.
- Easy to deploy.
- Easy to maintain.
- Easy to add Markdown or MDX content.
- Strong SEO foundations.
- Practical, readable, and credible for technical leaders.

## Candidate Stack Options

### Option A: Next.js + Docusaurus

Best when the site needs a custom landing/marketing layer and a documentation-style content library.

Pros:

- Strong React ecosystem.
- Flexible landing pages.
- Docusaurus gives strong docs UX quickly.
- Good for versioned guides and structured docs.

Cons:

- Two systems to maintain.
- More moving parts than needed for an early content site.

### Option B: Next.js + MDX

Best when the site should stay in one framework and needs custom UI plus content pages.

Pros:

- One app.
- Flexible design.
- Good SEO control.
- Easy to add custom interactive tools later.

Cons:

- More custom work for docs navigation, search, and content taxonomy.

### Option C: Astro + Starlight

Best when the priority is fast static content with a documentation-first UX.

Pros:

- Very fast static output.
- Content-first.
- Strong docs pattern with Starlight.
- Less client-side JavaScript by default.

Cons:

- Less aligned with a React/Next.js default if future app-like tools become central.

## Current Recommendation

Start with Next.js + MDX unless the documentation library becomes the dominant product from day one. It keeps the project lean, preserves design flexibility, and avoids running two site systems too early.

If the content grows into a large structured manual with many nested guides, reconsider Docusaurus or Starlight.
