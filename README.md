# template

Site that introduces the project templates: https://usausa.github.io/template/

GitHub Pages serves `docs/` on the `main` branch, so the page is what the browser gets; there is no build
step. `docs/index.html` holds the markup, the style and the cards, one card per template repository with
the headline and the detail of its GitHub description.

Each card carries one of two states:

| Badge | Meaning |
| --- | --- |
| ✅ Ready | Finished and documented |
| 🚧 In progress | Usable, still being worked on |

Flipping a card is one word, `ready` or `wip`, in its `<span class="status …">`, together with the label
next to it. Adding a template means adding a card to the group it belongs to.
