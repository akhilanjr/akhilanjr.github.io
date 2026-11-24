# akhilanjr.github.io

Personal site built with Jekyll and the Minimal Mistakes theme.

## Updating the CV
1. Edit `cv/cv.tex` (Awesome-CV template; the build fetches `awesome-cv.cls` automatically). Any text editor works, or edit directly on github.com.
2. Commit and push.
3. GitHub Actions compiles the LaTeX with LuaLaTeX and republishes the site (~2 min).
   The PDF lives at `/assets/files/Akhilan_J_R_CV.pdf` and is shown on `/cv/`.

If a build fails, check the **Actions** tab — a LaTeX error will be in the
"Compile CV with LuaLaTeX" step log.
