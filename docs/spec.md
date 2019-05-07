# bagtent specification v0.0.0

## Core spec: the content/ directory

- All Markdown files in `content/` must have a lower-case, hyphenated UUID with the suffix ".md" as their filename.
- All links to other files within the repository must be defined as repository-local links (ie. not absolute URLs to the rendered page, unless you are specifically referencing a specific rendered instance of the file that should not vary across forks).
- Files other than Markdown under `content/` are not defined by this specification, but should aim to adhere as closely to the example set by `content/`.

## Supplemental specs

The name `assets` may be used for an arbitrarily-structured

The `aliases` directory may contain files by name containing UUIDs (If your content uses a lot of aliases, consider that the bagtent model may not be the right fit for your content.)
