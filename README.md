This is a simple non-linear regression model using lmfit, to process beam profiles.
The code determines the percentage of each TEM mode, based on intensity in a beam profile by fitting the image into the superposition of mathematical models of a few TEM modes.

Caution:
Works best with Greyscale images, and is also tuned to work with jet colormaps by reverting it back to greyscale. Using other colormaps instead of these two may result in unexpected results.
