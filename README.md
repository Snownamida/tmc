**English** | [中文](README.zh-CN.md)

# The Thursday Murder Club (Book 4) — Character Map (Bilingual · Spoiler-Free)

An interactive character map for *The Last Devil to Die*, the fourth book in Richard Osman's *The Thursday Murder Club* series. Bilingual (English + Chinese) labels, **no core spoilers for Book 4**, perfect for quick reference while reading.

**Live site: <https://tmc.snownamida.top/>**

![Character map screenshot](docs/screenshot.png)

## Features

- **Five color-coded factions**: the core four, police & allies, antiques & art world, the drug ring, and the retirement village
- **Interactive network graph**: drag nodes to arrange the layout, scroll / pinch to zoom and pan
- **Character detail cards**: click a node for a bilingual (English + Chinese) background bio
- **Relationship labels**: edges are annotated with the relationship between characters (old friends, married couple, boss & subordinate, …)
- **Mobile-friendly**: browses smoothly on phones too

## Local development

A pure static single-page file, no build step required:

```bash
# Open it locally with either method
open index.html
# or
python3 -m http.server 8000
```

Tech stack: [vis-network](https://visjs.github.io/vis-network/docs/network/) (loaded via CDN).

Deployment: GitHub Pages + a custom domain (see `CNAME`).

## Related projects

- [The Murder of Roger Ackroyd character map (spoiler-free)](https://roger-ackroyd-map.vercel.app/) — Agatha Christie's *The Murder of Roger Ackroyd*

## Support

If this little tool helped your reading, feel free to [☕ buy me a coffee](https://ko-fi.com/snownamida).

## License

[MIT](LICENSE) © Snownamida
