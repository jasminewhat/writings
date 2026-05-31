# 🍊 What? — A Poetry Archive

> *"A way to remember the moments you wanted to forget."*
> View it here: https://jasminewhat.github.io/writings/

Welcome to my personal poetry archive. This is a cleanly designed, single-page web application featuring an automated index layout styled in a warm, cohesive **Creamsicle & Dreamsicle** color palette. 

## ✨ Features
*   **Zero-Maintenance Table of Contents:** The sidebar index automatically reads your poetry entries, strips out the dates, and updates itself dynamically on page load.
*   **Smart Sorting:** Visitors can instantly toggle the archive between *Newest First* and *Oldest First*.
*   **Fluid Responsive Design:** Fully optimized for clean reading on both desktop displays and mobile devices.

---

## ✍️ How to Add a New Poem

To add a new entry to the archive, you do not need to touch the JavaScript or the sidebar HTML. Follow these simple steps:

1. Open `index.html` and scroll down to the `<div class="poems-list" id="poems-container">` section.
2. Copy and paste a blank poem template block (see below).
3. Update the unique `id` attribute (e.g., `id="poem-7"`).
4. Update the `data-date` attribute using the strict `YYYY-MM-DD` format (this controls the automatic sorting). 
5. Add your title, friendly date string, and your poem verses.

### Blank Template Block:

```html
<article class="poem" id="poem-UNIQUE_NUMBER" data-date="YYYY-MM-DD">
    <h2 class="poem-title">Poem Title Here</h2>
    <div class="poem-meta">Month DD, YYYY</div>
    <p class="poem-body">First line of the poem.
    Second line of the poem.
    
    New stanza line here.</p>
</article>
