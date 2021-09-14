
> Open this page at [https://jwunderl.github.io/arcade-block-icons/](https://jwunderl.github.io/arcade-block-icons/)


Using FontAwesome icons converted to pngs with https://fa2png.app/ .


## To update

1. `pxt target arcade` at top level
2. `rm -rf node_modules/pxt-common-packages` to clear common packages (sometimes gets mixed up with icons)
3. Add icon under `jres/icons/` as `{icon-name}-icon.png`
4. Add entry to icons.ts as `"{icon-name}": {},`
5. At top level run `pxt buildjres`
6. `git tag v0.0.*` where star is current version +1
7. `git push --tags`

## Use as Extension

This repository can be added as an **extension** in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **New Project**
* click on **Extensions** under the gearwheel menu
* search for **https://github.com/jwunderl/arcade-block-icons** and import

## Edit this project ![Build status badge](https://github.com/jwunderl/arcade-block-icons/workflows/MakeCode/badge.svg)

To edit this repository in MakeCode.

* open [https://arcade.makecode.com/](https://arcade.makecode.com/)
* click on **Import** then click on **Import URL**
* paste **https://github.com/jwunderl/arcade-block-icons** and click import

## Blocks preview

This image shows the blocks code from the last commit in master.
This image may take a few minutes to refresh.

![A rendered view of the blocks](https://github.com/jwunderl/arcade-block-icons/raw/master/.github/makecode/blocks.png)
#### Metadata (used for search, rendering)

* for PXT/arcade
<script src="https://makecode.com/gh-pages-embed.js"></script><script>makeCodeRender("{{ site.makecode.home_url }}", "{{ site.github.owner_name }}/{{ site.github.repository_name }}");</script>
