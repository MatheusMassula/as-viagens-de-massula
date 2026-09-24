# Site images

The landing photos live here. The names the code looks for are in
`lib/features/landing/sections/` — each `ImageSlot` names its asset, and falls
back to the design's own placeholder text when the file is absent, so the site
stays presentable until every slot has a file.

| File | Where it appears |
| --- | --- |
| `hero_background.jpg` | Hero background |
| `me.jpeg` | Minha história mosaic — tall portrait |
| `dog.jpeg` | Minha história mosaic — dog |
| `road.jpeg` | Minha história mosaic — road detail |
| `brand-1.png` … `brand-4.png` | Partner logo strip (not yet exported) |

Product covers are **not** here — they come from the backend as `coverUrl`.
