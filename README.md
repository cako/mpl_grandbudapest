# mpl_grandbudapest
Matplotlib mpl style inspired by The Grand Budapest Hotel film by Wes Anderson

## Install
Copy the `grandbudapest.mplstyle` file to the `stylelib` under your Matplotlib configure directory. If none of this makes sense but you're on Linux, create `~/.config/matplotlib/stylelib` and place the mplstyle file in there. More information on installing and using style files can be found [here](https://matplotlib.org/users/style_sheets.html).

The style is designed to use with [FF DIN](https://www.fontshop.com/families/ff-din) font, which was the sans-serif font chosen for The Grand Budapest Hotel. Since FF DIN is an expensive font, I chose [Abel](https://fonts.google.com/specimen/Abel) as a free fallback. If none of these are found, the standard sans-serif is used.

A super quick way of installing a font is to copy it to your `~/.fonts/` folder and running `fc-cache -fv` to update the cache.

## Use
Once installed, add the following lines to your file.
```python
import matplotlib.pyplot as plt
plt.style.use('grandbudapest')
```

## Example
I shamelessly stole this example from [here](https://matplotlib.org/gallery/style_sheets/ggplot.html?highlight=ggplot%20style%20sheet).

![grandbudapest example](/grandbudapest.png?raw=true "Example")


