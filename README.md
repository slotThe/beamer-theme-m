# Beamer Theme M

A thin wrapper around Matthias Vogelgesang's [metropolis] beamer theme (formerly called /m/).
The light list of additions/changes in comparison to the original theme is:

  - A muted white background;
    people will usually not even notice this in a slide presentation,
    yet this is much easier on everyone's eyes.

  - The option to specify an additional, smaller, subtitle.

  - A QR code on the opening page.

  - White-on-black standout fames instead of green-on-white ones.
    Speaking from experience,
    the quick contrast change sometimes makes it very difficult to actually read the standout slides.

To use, simply `\usetheme{m}`.

For an example, see `./example.tex`.

## License

The theme itself is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
This means that if you change the theme and re-distribute it,
you *must* retain the copyright notice header and license it under the same CC-BY-SA license.
This does not affect the presentation that you create with the theme.

[metropolis]: https://github.com/matze/mtheme
