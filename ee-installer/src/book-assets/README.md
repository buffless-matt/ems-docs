# Book Assets

This directory contains extra files for modifying the look and functionality of
[mdbook](https://github.com/rust-lang/mdBook), the documentation software that's
used to generate Synapse's documentation website.

The configuration options in the `output.html` section of [book.toml](../../book.toml)
point to additional JS/CSS in this directory that are added on each page load. In
addition, the `theme` directory contains files that overwrite their counterparts in
each of the default themes included with mdbook.

Currently we use these files to generate [a floating Table of Contents page]
(<https://github.com/JorelAli/mdBook-pagetoc/>).

More information can be found in mdbook's official documentation for
[injecting page JS/CSS](https://rust-lang.github.io/mdBook/format/config.html)
and
[customising the default themes](https://rust-lang.github.io/mdBook/format/theme/index.html).
