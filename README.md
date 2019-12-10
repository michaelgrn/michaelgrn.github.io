# piretship.github.io

PIReT Web Site.  This is a Jekyll site.

We use the [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/) Jekyll theme.

## Adding Publications

To add a publication, add a new Markdown file in the `_pubs` directory.  Do **not** add it to `pubs`; this is for managing output.

The markdown file needs a couple of things.  For an example, see `ComplexRec18-literate.md`.

-   The frontmatter should contain the title, publication date, and project, like this:

        title: Paper Title
        date: 2018-08-15
        project: literate
        type: paper

    If the paper has a DOI or arXiv ID, include that in the header as well, as a `doi` or `arxiv` field.  The `type` should be one of:

    - paper
    - demo
    - thesis

-   The first paragraph of the file should be a citation, with two special pieces of formatting:

    - The *paper title* should be a link to the location `#`, e.g. `[My Paper Title](#)`.
    - The first line of the paragraph needs to be the text `{: .citation}` to mark it as a citation paragraph.
      This is a Kramdown [inline block attribute list](https://kramdown.gettalong.org/syntax.html#block-ials).
