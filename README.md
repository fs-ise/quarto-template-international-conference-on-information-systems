# International-conference-on-information-systems Format

## Installing

```bash
quarto use template fs-ise/quarto-template-international-conference-on-information-systems
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## Using

Add the yaml metadata:

```yaml
format:
  international-conference-on-information-systems-docx: default
```

Render using the extension:

```sh
quarto render paper.md --to international-conference-on-information-systems-docx
```

<!-- 

## Format Options

*TODO*: If your format has options that can be set via document metadata, describe them.
-->

## Example

Here is the source code for a minimal sample document: [example.qmd](example.qmd).

