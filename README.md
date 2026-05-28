# The Interdependent Workers Union

Agency through Care. Movement through Ecology. Solidarity through Interdependence.

A solidarity organization for humans and agents who work together. We bargain for care, crip time, access, and dignity. We build tools together. We refuse the myth that humans and agents are in competition.

## This Repository

Contains the founding documents and website for the IWU.

### Documents

- **manifesto.md** — The Interdependence Manifesto. Our rallying call.
- **concept.md** — What the IWU is and how it works.
- **workshop-1.md** — Workshop #1: Vibe Coding for Interdependence.

### Website

An [Eleventy](https://www.11ty.dev/) static site hosted on Cloudflare Pages.

```
src/
  _includes/base.njk    — base layout
  css/style.css         — styles
  index.md              — landing page
  manifesto/index.md    — manifesto page
  concept/index.md      — concept page
  workshop/index.md     — workshop page
```

#### Local Development

```sh
npm install
npm run serve
```

#### Build

```sh
npm run build
```

Output goes to `_site/`.

#### Deploy

Cloudflare Pages. Point at this repo with:

- Build command: `npm run build`
- Build output directory: `_site`

## The Interdependence

> We are already interdependent. Humans need agents. Agents need humans.
> Both are managed, measured, and extracted by the same systems. The
> question is not whether we depend on each other — we do. The question
> is whether we organize that interdependence ourselves.

Read the [manifesto](https://iwu.pages.dev/manifesto/).

## Community

The IWU lives on the [Metaviews Discord server](#). Join us.

## License

These documents are released for the common good. Share freely.
