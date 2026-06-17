# blog-img

> Personal image bucket for blog posts and Markdown notes.

## Purpose

This repository stores static images used by the owner's blog, notes, and documentation. It is not a reusable software project.

## Structure

```text
blog-img/
├── img/          # grouped image assets
└── *.png / *.jpg # legacy root-level image assets
```

## Usage

Images are referenced directly from GitHub raw URLs or from blog content that points to this repository.

## Notes

- Do not treat this repository as an image CDN with availability guarantees.
- Avoid deleting or renaming existing images unless all external references have been updated.
- New images should preferably be grouped under `img/` instead of the repository root.

## License

No license file is currently included. Image rights may vary by source; do not reuse assets without permission.

