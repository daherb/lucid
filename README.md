# lucidsbx
A modern Beamer theme you can use without installing dozens of CTAN packages. It is modified to match the official University of Gothenburg template with added Språkbanken effects.

It is based on [harisont's lucid template](https://github.com/harisont/lucid) which in turn is based on  [Beamer-Theme-Execushares](https://github.com/hamaluik/Beamer-Theme-Execushares).

## Usage
You can of course use lucid to write your presentations in LaTeX and compile them with `lualatex` or `xelatax`. 
A fairly standard `texlive` installation should provide everything you need. The packages required are `tikz`, `fontspec`, `xcolor` and `caption`. In addition the fonts `Liberation Sans` as well as `RobotoMono Nerd Font Propo` (for small caps) is used. The sample document also requires the `qrcode` package.

To use the template in your own presentation copy all the `.sty` files as well as the `logos/` folder and add `\usetheme{lucidsbx}` (which can be configured using the options described below) to your `tex` file

The template can easily be configured and adjusted

- The template supports a set of options:
  - `dark`: use dark mode instead of default light mode
  - `progressBar`: show a progress bar at the bottom above the black line
  - `slideNumbers`: show the number of the current slide
  - `slideTotal`: also show the total number of slides next to the number of the current slide
  - `sectionPages`: how a separate slide with the title in the beginning of each section
  - `sectionTitles`: show the title of the current section at the bottom of the screen
- The default University of Gothenburg logo can be replaced using the `\logo` command
- The final slide can be modified using the `\finalinfo` command and created using the `\makefinal` command (See example)
- The fonts can be changed in the the file `beamerfontlucidsbx.sty`
- The color schemes can be changed in `beamerfontlucidsbx.sty` or `beamerfontlucidsbx-dark.sty`.

If you don't like writing slides directly in LaTeX you can use markdown as described in the harisont's [README.md](https://github.com/harisont/lucid/blob/master/README.md)

## Namesake
In Italian, _lucidi_ is the word that indicates slides meant for old-fashioned overhead projectors.
Not to mention that having a quick and simple way to generate acceptable-looking slides greatly helps me _mantenere la luciditá_ (stay sane).
