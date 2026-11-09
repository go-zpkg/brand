# go-zpkg brand

Logos and icons for the [go-zpkg](https://github.com/go-zpkg) organization.

<img src="avatar/go-zpkg.png" width="160" alt="go-zpkg">

`logo.svg` is the source mark — a white isometric package on the amber
`#F59E0B → #B45309` gradient, a sibling of the go-* family marks. Amber is
this organization's established identity, and the gradient stops are
load-bearing: the landing kit reads the brand colours out of them, so changing
a stop restyles the published site.

## Formats

- **SVG** — `svg/color`, `svg/white` (white glyph, transparent), `svg/black`
  (black glyph, transparent)
- **PNG** 16→1024 px, 3 variants — `png/<variant>/<size>/`
- **JPG** (color, white background) — `jpg/<size>/`
- **ICO** (Windows favicon, multi-res 16→256) — `ico/go-zpkg.ico`
- **ICNS** (macOS) — `icns/go-zpkg.icns`
- **GitHub avatar** 512 px — `avatar/go-zpkg.png`
- **Social preview** 1280×640 (org profile / repo banner) — `social/go-zpkg.png`

The mark is theme-safe: a white glyph on the amber badge, never a white
background.

## The `go-pkgx.*` files are still here, on purpose

This organization was `go-pkgx`. Repositories followed the transfer; the asset
FILENAMES did not, because a filename is referenced by whoever links to it.
Every asset now exists under `go-zpkg.*`, and the `go-pkgx.*` ones were kept
rather than renamed:

- a README banner, a site favicon or an `<img>` in any repository that points
  at `go-pkgx.png` keeps working — a rename would have turned each of those
  into a broken image, and the ones outside this organization cannot be found
  by searching it;
- GitHub's code search does not index this repository (a literal sentence from
  this README returns nothing), so "nobody references them" was not a claim
  that could be checked, only assumed.

`go-zpkg.*` is the canonical set. The old names are frozen — they are not
regenerated, so they will drift from the mark if it ever changes, and anything
still pointing at them should move.

## License

BSD-3-Clause © the go-zpkg/brand authors.
