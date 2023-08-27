# PGM XML Documentation

Documentation for the XML format [PGM](https://github.com/OvercastNetwork/ProjectAres/) uses to define map specific features.
Pages are hosted using Jekyll and Github Pages.

> [!WARNING]
> This repository is no longer maintained as it was intended for 2012-2017 version of ProjectAres (PGM).
> Please visit its modern replacement at [PGMDev/Website](https://github.com/PGMDev/Website).

### Editing Notes

1. Pages are formatted in Markdown and may contain HTML.
   * HTML should only be used where absolutely needed.
3. Markdown is parsed with [kramdown](https://kramdown.gettalong.org/), which has an [enhanced syntax](https://kramdown.gettalong.org/syntax.html).
4. Care should be taken when removing trailing whitespace since Markdown uses two spaces to create a newline.

### Pull Requests

Pull requests should have the following things:

1. The commits should have a descriptive message and which is not in the past tense.
   * For example:  
     `Describe the XYZ module with more detail.` or `Add detailed description for XYZ.` is good, but: `Added XYZ.` isn't.
2. Content should be grammatically correct and the spelling should be US English, e.g. `Color` not `Colour`.


## Previewing your changes

1. Install Ruby ([macOS](https://gorails.com/setup/osx/10.11-el-capitan), Windows, [Ubuntu](https://gorails.com/setup/ubuntu/15.10))
      * We don't need Rails, so just install Ruby
3. Install the [Bundler](http://bundler.io) gem.
2. Run `bundle install` from the source root.
3. Run `bundle exec jekyll serve` or `jekyll serve`
4. Load `localhost:4000` in your browser.
