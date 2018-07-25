# My Macros

As with all (La)TeX users, over time I've gathered a fair number of macros that I tend to use in most of my documents.
Most are the of the standard `\newcommand{\R}{\mathbb{R}}` variety but a couple are a little more complicated.
As one or two of these more complicated ones are relevant to the issues raised in [MyClass](https://github.com/loopspace/myclass), I'm putting them up here.


Most of its behaviour is controlled by options.
In summary:

debug
: Turns on a logging message (currently used with figures)

track
: Make this package visible to the `cmdtrack` package (if used)

diff
: Load of basic shortcuts for derivatives

bb
: Shortcuts for common blackboard bold letters

geom
: Load of basic shortcuts for geometry

nothm
: Don't define any theorem environments (useful if my standard definitions clash with some other package)

fig
: Some basic commands for including figures.
In particular, figures are assumed to be in a subdirectory called (imaginatively) `figures`.
There's a command `\myfig` which will first look for a `pstex_t` file to input (from my `xfig` days) and if that isn't found it does an `includegraphics` (without the extension) instead.

wallpaper
: Sometimes I just get fed up with white backgrounds.

final
: Passed on to a subpackage

collaborate
: Passed on to a subpackage

lecture
: Adds a lecture title page to each lecture in a beamer presentation

all
: Not really all, actually: chcl,diff,abbrev,bb,geom,amsthm,fig


