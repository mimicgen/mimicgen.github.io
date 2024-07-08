# MimicGen Website

Website for [MimicGen](https://mimicgen.github.io/).

## Updating docs folder using sphinx-generated docs

First, generate docs using the Makefile in `mimicgen/docs`, which should result in the folder `mimicgen/docs/_build/html`.  Copy the contents of this folder into `mimicgen.github.io/docs`, then, rename `docs/_static` to `docs/static` and update all html references in the `docs` folder to point to `static` instead of `_static`. Do the same for `_images` , and `_sources`. You may also need to copy additional images from `mimicgen/docs/images` into that folder as well, and remove an existing `_images` folder.
