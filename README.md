# akhilanjr.github.io

Personal site built with Jekyll and the Minimal Mistakes theme. Every push to
`master` rebuilds and republishes the site (~2 min; watch the **Actions** tab).

## Where to edit what

| What you see on the site            | File to edit                         |
|-------------------------------------|--------------------------------------|
| Home page text (Work at J-PAL, etc.) | `index.md`                           |
| Text under your photo (sidebar)      | `_config.yml` → `author:` → `bio:`   |
| Name, email, sidebar/footer links    | `_config.yml` → `author:` / `footer:`|
| Menu at the top                      | `_data/navigation.yml`               |
| CV                                   | `cv/cv.tex` (compiled to PDF automatically) |
| Fonts, sizes, styling                | `assets/css/main.scss`               |

Pages are Markdown: `## Heading`, `**bold**`, `*italic*`, `[link text](https://...)`.

You can edit any file directly on github.com (open the file → pencil icon →
**Commit changes**), or locally and commit/push with GitHub Desktop.

## Adding photos

1. Make a folder inside `assets/photography/`, e.g. `assets/photography/2025-kodaikanal/`.
   Each folder becomes its own section on the Photography page. Dashes and
   underscores show as spaces; starting the name with a year sorts newest first.
2. Put `.jpg`, `.png` or `.webp` files in it. Resize them first (about 2000 px
   on the long edge, under ~1 MB each) so the page loads fast and the repo stays small.
3. Commit and push. The new section appears after the build finishes.

To remove a photo or album, delete the file or folder and push.

## Adding paintings

1. Put paintings in `assets/paintings/`, named in the order you want them
   shown: `1.jpg`, `2.jpg`, `3.jpg` … (10 comes after 9). To insert one later,
   renumber the files after it.
2. To title or describe a painting, add a `.txt` file with the same number
   (`3.jpg` → `3.txt`):

   ```
   Title of the painting
   Watercolour on paper, 30 x 40 cm, 2025

   The story of the painting. Blank lines separate paragraphs.
   ```

   - Title + description: shown large, with the text beside it.
   - Title only (just the first line): stays in the gallery; the title shows
     when the painting is opened.
   - No `.txt`: shown in the gallery with no title.
3. Commit and push.
