# glossary-pb: Personal Glossary for glossary2

My personal glossary of terms and definitions, for use with the
[glossary2](https://github.com/petzi53/glossary2) R package (a
fork of [glossary](https://github.com/debruine/glossary) by Lisa DeBruine).

The glossary itself lives in [`glossary.yml`](glossary.yml) — a plain YAML mapping of
term to definition. Definitions may contain markdown.

This page is published via GitHub Pages at <https://petzi53.github.io/glossary-pb>.

## Usage

### Load directly from GitHub (no local installation)

```r
library(glossary2)
glossary_load_all("https://raw.githubusercontent.com/petzi53/glossary-pb/main/glossary.yml")
## example of a configuration (my preference)
glossary::glossary_popup("hover")

# In R Markdown/Quarto: `r glossary("your_term")`
```

### Or clone and load locally

```bash
git clone https://github.com/petzi53/glossary-pb.git
```

```r
library(glossary2)
glossary_load_all("path/to/glossary-pb/glossary.yml")
```

## Contributing

Issues and suggestions are welcome — please open an issue or submit a PR.

## License

CC BY 4.0 (consistent with glossary2).

## See Also

- [glossary2](https://github.com/petzi53/glossary2) — the package that loads this glossary
- [glossary2 documentation](https://www.peter-baumgartner.net/glossary2/)
