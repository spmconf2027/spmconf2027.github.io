# SPM 2027 website

Static website for the Symposium on Solid and Physical Modeling (SPM 2027),
June 21–25, 2027, Singapore, part of the [International Geometry Summit (IGS 2027)](https://igs2027singapore.github.io/).

Live site: https://spmconf2027.github.io/

## Editing

Plain HTML/CSS, no build step. Edit the `.html` files and push; GitHub Pages republishes automatically.

- `index.html`: Home (about, partner conferences, news, important dates)
- `cfp.html`: Call for Papers
- `organization.html`: Chairs and committees
- `attending.html`: Registration, venue, travel
- `assets/`: stylesheet, script, logo

The header and footer are repeated in every page. If you change the menu, update all four files.
The important-dates table appears on both `index.html` and `cfp.html`.

Preview locally: `python -m http.server` in this folder, then open http://localhost:8000.
