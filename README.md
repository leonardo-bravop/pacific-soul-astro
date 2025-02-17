# Pacific Soul - Copy Project

This project involves building a copy of the [Pacific Soul Website](https://llosaedificaciones.com/proyecto-pacific-soul) using **Astro**.

## Project Overview

The goal is to replicate the design, layout, and structure of the Pacific Soul project page while using Astro to create a fast, modern, and SEO-friendly site. This will involve setting up the page structure, creating components, and incorporating the same look and feel as the original.

### Technologies Used:
- **Astro**: A static site generator that allows you to create modern websites using components from frameworks like React, Vue, and Svelte, while keeping the build output minimal and optimized.
- **Tailwind CSS**: A utility-first CSS framework that will allow for quick and flexible styling of the page components.
- **HTML/CSS**: To match the design and layout of the Pacific Soul website.
- **JavaScript**: For any required interactive elements.
- **External Assets**: Images and fonts from the original website (or appropriate substitutes).

## Installation

To get started, clone this repository to your local machine:

```bash
git clone https://github.com/leonardo-bravop/pacific-soul-astro
cd pacific-soul-copy
```

Install the necessary dependencies:

```bash
npm install
```

## Development

To run the development server and view your work in progress:

```bash
npm run dev
```

Visit [http://localhost:4321](http://localhost:4321) in your browser to see the live site *

* The default development port for an Astro project is **`4321`**.

You can change the port by setting it in your `astro.config.mjs`:
```js
import { defineConfig } from 'astro/config';

export default defineConfig({
  server: {
    port: 3000
  }
});
```