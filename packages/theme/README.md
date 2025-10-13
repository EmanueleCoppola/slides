# Aurora Theme

Neon surfaces, glassmorphism, and Space Grotesk typography for [Slidev](https://github.com/slidevjs/slidev) presentations.

![Aurora Theme Preview](./media/preview-cover.png)

<!--
  Learn more about how to write a theme:
  https://sli.dev/guide/write-theme.html
--->

<!--
  run `npm run dev` to check out the slides for more details of how to start writing a theme
-->

<!--
  Put some screenshots here to demonstrate your theme

  Live demo: [...]
-->

## Install

Add the following frontmatter to your `slides.md`. Start Slidev then it will prompt you to install the theme automatically.

<pre><code>---
theme: <b>@theme/aurora</b>
title: Hello Aurora
---</code></pre>

Slides will inherit the neon glow, Space Grotesk typography, and layout defaults automatically.

Learn more about [how to use a theme](https://sli.dev/guide/theme-addon#use-theme).

## Layouts

This theme provides the following layouts:

- `cover` – hero slide with centered content and glow background.
- `intro` – vertical stack for learning objectives or overviews.
- `spotlight` – illuminated card floating on top of animated gradients.
- `split` – two-column layout with a dedicated `left` slot for media/quotes; collapses gracefully on smaller screens.

## Components

This theme provides the following components:

- `GlowCard` – optional wrapper to highlight key concepts (see `example.md`).

## Contributing

- `pnpm install`
- `npm run dev` to start theme preview of `example.md`
- Edit the `example.md` and style to see the changes
- `npm run export` to generate the preview PDF
- `npm run screenshot` to generate the preview PNG
