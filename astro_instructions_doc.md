# astro-claude-instructions.md

## Tech Stack Requirements

- **Astro (NOT React)** - Use .astro components only as the primary development approach
- **TypeScript** where applicable for type safety and better development experience
- **Tailwind CSS 4** (latest version) - DO NOT suggest old Tailwind configs or v3 syntax
- **Content Collections** for managing blog posts, pages, and any custom content types

## Key Guidelines

- **This is an ASTRO project** - No React components unless absolutely necessary for specific interactive features
- **Use Astro's component syntax** - All components should be `.astro` files following Astro conventions
- **Tailwind CSS 4 configuration** - When adding Tailwind, always use the latest v4 configuration syntax and features
- **Astro-first mindset** - Leverage Astro's built-in features and capabilities rather than external solutions

## Performance Focus

- **Prioritize fast loading times** - Choose solutions that minimize initial page load
- **Minimize bundle size** - Avoid unnecessary JavaScript and dependencies
- **Use Astro's partial hydration strategically** - Only hydrate components that truly need client-side interactivity
- **Use Astro's dev server** - Rely on Astro's built-in development tools, not external build processes

## SEO Preservation

- **Generate proper sitemaps** - Ensure all pages are discoverable by search engines
- **Maintain semantic HTML** - Use proper heading structure and meta tags
- **Optimize for Core Web Vitals** - Focus on performance metrics that impact search rankings

## What NOT to do

- **Don't suggest React solutions** - Unless there's a compelling reason that can't be solved with Astro
- **Don't give Tailwind v3 configuration** - Always use the latest v4 syntax and setup
- **Don't suggest complex build processes** - Keep the build pipeline simple and rely on Astro's defaults
- **Don't over-engineer** - Choose the simplest solution that meets the requirements

## Context Notes

When working on Astro projects:
1. Always check if a feature can be implemented with native Astro capabilities first
2. Use Content Collections for any structured content management needs
3. Leverage Astro's file-based routing system
4. Take advantage of Astro's zero-JS by default philosophy
5. Only add client-side JavaScript when necessary for user interactions

## Quick Reference

- **Component files**: Use `.astro` extension
- **Styling**: Tailwind CSS 4 utility classes
- **Content**: Astro Content Collections
- **Routing**: File-based routing in `src/pages/`
- **Assets**: Place in `src/assets/` or `public/` as appropriate