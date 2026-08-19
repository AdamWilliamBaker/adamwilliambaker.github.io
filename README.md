# Academic website

This is a Quarto website designed to be hosted free on GitHub Pages at
`https://adamwilliambaker.github.io`.

## Personalize it

Replace every placeholder in `_quarto.yml`, `index.qmd`, `research.qmd`, and `about.qmd`. Add a headshot only if you want one; the layout does not depend on it.

## Preview it

Run `quarto preview` from this directory.

## Write from Obsidian

Open this directory, or just the `notes` directory, as an Obsidian vault. Publishable notes should use standard Markdown links and YAML properties. Quarto-specific files can use `.qmd`; plain notes can use `.md` because Quarto renders both.

Obsidian-only features such as `[[wiki links]]`, transclusions, and plugin syntax may need conversion before publishing. The least-friction approach is to use normal Markdown links in public notes.

## Publish it

The repository for this site will be named `adamwilliambaker.github.io`. The
included GitHub Action renders and publishes the site after every push to `main`.
Once the first publish completes, select the `gh-pages` branch under the
repository's Pages settings if GitHub does not do so automatically.

You can later buy a custom domain such as `adamwilliam-baker.com` or
`adamwbaker.com`; hosting will remain free. Add a file named `CNAME` beside
`_quarto.yml` containing only that domain, then configure it in GitHub Pages and
at your registrar.
