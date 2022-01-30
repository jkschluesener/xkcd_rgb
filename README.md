# XKCD RGB Color Lookup for Matlab

A simple, self-contained matlab lookup function for the [XKCD color name survey](https://blog.xkcd.com/2010/05/03/color-survey-results/).

[Color Lookup Page](https://xkcd.com/color/rgb/)

Colors are returned as a RGB triplet scaled 0-1 as one would use in Matlab.

## Installation

Download / clone this repo, add it to your path with `addpath('<path_to_this_repo>')`

## Usage

```octave
linecolor = xkcd_rgb('butterscotch')
plt.plot(x, y, 'color', linecolor)

% or 
plt.plot(x, y, 'color', xkcd_rgb('butterscotch'))

% or
h = plot(x, y);
set(h, 'Color', xkcd_rgb('butterscotch'))
```
