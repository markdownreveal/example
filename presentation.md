% Simple presentations with Markdownreveal
% Miguel Sánchez de León Peque
% 2017-12-17


# Make presentations with joy!

## Tired?

![](./video/out.ogv){width=80% height=400}

## Markdownreveal

![](./figures/logo.svg){width=20%}

[https://github.com/markdownreveal/markdownreveal](https://github.com/markdownreveal/markdownreveal)

## Testimonials

> **I used to cry when I had to open my office suite... Now I don't cry anymore!**
>
> — *Mx. Trustworthy*


# How do I start?

## Requirements

- Python 3.5+
- Pandoc

> *Optionally Docker (for exporting to PDF)

## Usage

```bash
# Install
pip install markdownreveal

# Run
markdownreveal presentation.md

# Run (shorter)
mdr presentation.md
```

## Equations too!

$$
f(x) = \int_{-\infty}^\infty h(\xi)\,e^{2 \pi i \xi x} \,d\xi
$$

Also inline $c = \sqrt{a^2 + b^2}$...

## And emojis! :smile:

Markdownreveal... :heart_eyes:

## Subcommands

- Upload to GitHub pages
- Generate PDF
- Create a ZIP file

```bash
markdownreveal --help
```

## Custom styles

- YAML files
- Create your own style repository!
- Corporate look

## More!

- [Official documentation](https://markdownreveal.readthedocs.org)
- [Source code repository](https://github.com/markdownreveal/markdownreveal)
- [Example repository](https://github.com/markdownreveal/example)
