---
title: Project 1 – Blog Design Process
description: Concept, inspiration, and design development for my blog
date: 2026-04-01
---

## Concept

This blog is designed as an editorial-style space rather than a traditional blog. Instead of following a standard layout, the design focuses on typography, spacing, and composition to create a more visual and curated experience. The goal was to move away from a default template and create something that feels more intentional and designed.

---

## Inspiration

The visual direction of this project was inspired by editorial layouts, gallery catalogs, and experimental typography.

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 12px; max-width: 600px;">

## Inspiration

The visual direction of this project was inspired by editorial layouts, gallery catalogs, and experimental typography.

<img src="/img/inspo1.png" alt="editorial layout inspiration" class="post-image">
<img src="/img/inspo2.png" alt="typography inspiration" class="post-image">
<img src="/img/inspo3.png" alt="minimal layout inspiration" class="post-image">
<img src="/img/inspo4.png" alt="text and image composition inspiration" class="post-image">
<img src="/img/inspo5.png" alt="color and layout inspiration" class="post-image">

Some of the key ideas I pulled from these references:
- large, bold typography
- strong use of negative space
- minimal but intentional color palettes
- asymmetrical layouts
- image and text relationships

---

## Sitemap

The structure of the site is simple and focused:

- Home
- Blog Posts
  - Individual Post Pages
- About
- 404 Page

---

## Wireframes

### Homepage

The homepage was designed to feel less like a list and more like a layout:

- navigation at the top
- large title / heading
- grid of posts
- spacing used to create visual balance

### Post Page

The post page is more structured:

- large title at the top
- smaller metadata (date)
- readable text layout
- consistent spacing

---

## Sketches

My sketches focused on layout and structure rather than detail. I experimented with how to arrange posts and text in a way that felt less rigid than a traditional blog. The goal was to create something that felt more like a designed page than a simple list of content.

---

## Design Decisions

The final design uses a black background to create strong contrast and make the content stand out. Accent colors were limited to a muted yellow and blue to keep the palette minimal but intentional.

Typography plays a major role in the design. Larger headings create hierarchy, while body text remains readable and clean. Spacing is used to separate sections and give the layout room to breathe.

The layout uses a grid system for posts, but offsets were added to break uniformity and make the design feel more dynamic. The navigation was simplified into a dropdown menu to keep the interface minimal and not distract from the content.

---

## Technical Implementation

This project was built using Eleventy and customized by editing the layout and styling files.

- `home.njk` was updated to change the homepage structure
- `style.css` was used for global styling (colors, layout, typography)
- `index.css` was used for homepage-specific styling
- the navigation menu was changed using the `<details>` element to create a dropdown without JavaScript
credit: https://dev.to/ayushn21/details-summary-tags-html-s-best-kept-secret-4ak4?utm_

Through these changes, the default template was transformed into a more custom and visually distinct design.

---

## Process Reflection

Throughout this project, I focused on experimenting with layout and design rather than just functionality. Working directly in the code allowed me to test different ideas quickly and see how small changes affected the overall composition.

One of the biggest challenges was breaking away from the default blog structure while still keeping the site readable and usable. Overall, the process helped me better understand how layout, typography, and spacing can shape the user experience.