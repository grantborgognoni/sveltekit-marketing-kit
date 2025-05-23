# SvelteKit Marketing Kit  
![Work in Progress][wip-badge]

> A SvelteKit starter template…

[wip-badge]: https://img.shields.io/badge/status-wip-yellow

> A SvelteKit starter template providing marketing focused UI components built on [shadcn-svelte](https://github.com/shadcn/shadcn-svelte). Ensure consistent typography, spacing, and layout across landing pages and promotional sites.

## The Problem It Solves

Building marketing pages with Shadcn Svelte often requires manual setup of containers, typography, spacing, and design tokens, leading to boilerplate code, inconsistent styles, and slower development cycles. This kit provides ready made marketing components with standardized styles.

---

## Features

* **Layout Components:** `Container`, `Section`, and `Grid` with preset padding and margin scales
* **Typography:** `Heading` (`H1`–`H4`), `Subheading`, and `Text` components matching marketing design tokens
* **Marketing Blocks:** `Hero`, `FeatureCard`, `TestimonialCard`, `CTAButton` components ready to drop in
* **Design Tokens:** Consistent color, spacing, and typography variables via Tailwind CSS config
* **Theming:** Light / dark mode support
* **Easy Customization:** Override tokens or extend components in your own project

---

## Usage

Import and use any component directly in your SvelteKit pages:

```svelte
<script lang="ts">
  import { Container, Hero, FeatureCard, CTAButton } from '$lib/components';
</script>

<Container>
  <Hero title="Welcome to Our Product" subtitle="Built for marketers" />
  <FeatureCard title="Fast Setup" description="Get your marketing pages up in minutes." />
  <CTAButton href="/signup">Get Started</CTAButton>
</Container>
```

Customize spacing, colors, or typography by editing the Tailwind config or extending component props.

---

## Contributing

Contributions, issues, and feature requests are welcome! Please open an issue or submit a PR on GitHub.

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
