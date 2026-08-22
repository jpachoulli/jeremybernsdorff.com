# Employment Logo Sprite Setup

## File location

Copy the sprite sheet into:

`assets/images/employment_logos_sprite.png`

The Experience page is already wired to:

`assets/css/employment-logos.css`

## Default layout assumed by the CSS

The included CSS assumes the sprite is arranged:

| Row | Column 1 | Column 2 | Column 3 | Column 4 |
|---|---|---|---|---|
| 1 | TrueBlue | DISYS | Boeing | Dell EMC |
| 2 | TEKsystems | American Family | Autoliv | P&G |

Each source logo was previously described as normalized to a transparent 1200 × 600 canvas.

Under that layout, the full sprite would normally be 4800 × 1200 pixels.

## If your actual sprite order/layout differs

Do **not** rewrite the Experience page.

Open:

`assets/css/employment-logos.css`

and change only these classes:

- `.logo-trueblue`
- `.logo-disys`
- `.logo-boeing`
- `.logo-dellemc`
- `.logo-teksystems`
- `.logo-amfam`
- `.logo-autoliv`
- `.logo-pg`

If the sprite is not a 4×2 grid, also change:

`background-size: 400% 200%;`

Once the actual sprite sheet is available, its exact geometry can be mapped precisely.
