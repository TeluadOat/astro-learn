---
title: Fourth Post
author: Olubodun Adeola Temidayo
pubDate: 2025-08-12
---

# My Fourth Blog Post

Published on: 2025-08-12

## What i have accomplished

1. **Using internal and external styles**:
I used the `<style>...</style>` method, embeded in the html head to style my sheet. Also to use external stylesheet, i created a styles folder in the src folder and then created a global.css file within which i apply the styles.

2. **Creating and using an Astro Component**: I created a new `.astro` components in `src/components/`. I created Navigation, Footer and Social component files. The file names starts with a capital Letter. Components can be imported and used inside other compnents using the `import fileName from "dirName/fileName"`.

3. **Using Astro Props**: An Astro Component's frontmatter can receive values as props using:  `const {value} = Astro.props;`.
The values can then be passed as props to an Astro component:  `<Component value="...">`