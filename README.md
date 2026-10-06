# Minimal CV website

This is a stripped-down starter for a one-page Quarto website that links directly to a PDF CV. The page includes simple places for a biography, publications, working papers, teaching, and a profile picture. It contains no instructor content, publication database, sample CV, or HTML-CV machinery. It is used in POLS 6394, Social Science Computation and Data Science.

## Attribution

This starter was adapted and greatly simplified by [Boris Shor](https://github.com/bshor) from [Gang He's Quarto Academic Website Template](https://github.com/drganghe/quarto-academic-website-template), the MIT-licensed upstream template for Boris's academic site. The original copyright and license are preserved in `LICENSE`, which also identifies Boris's 2026 modifications.

## Make it yours

1. Rename the repository to `yourusername.github.io`.
2. Replace the name, subtitle, biography, email address, and GitHub URL in `index.qmd`.
3. Replace `Your Name` in `_quarto.yml`.
4. Replace `files/profile-placeholder.svg` with your own picture, or keep the placeholder until you have one.
5. Replace, rename, or remove the example Publications, Working Papers, and Teaching entries.
6. Put your rendered PDF CV at `files/cv.pdf`.
7. Run `quarto render`.
8. Commit and push the source files and the generated `docs/` folder.
9. In GitHub **Settings → Pages**, publish the `docs/` folder on the `main` branch.

There is intentionally no HTML CV. The website links directly to the PDF produced by the separate `quarto-cv` project.
