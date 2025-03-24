NGC 4603 (spiral galaxy located in the constellation Centaurus) - Color Composite Image

This project creates a color composite image of the spiral galaxy NGC 4603, located in the constellation Centaurus, using astronomical data from Hubble Space Telescope observations.

## Data Source

FITS FILE IS BIGGER THAN 25Mb SO PLEASE DOWNLOAD IT FROM THE WEBSITE LINK BELOW.

The FITS files used in this project were obtained from the Hubble Legacy Archive:

Link: https://archive.stsci.edu/prepds/sgal/datalist.html

- h_n4603_f555_mosaic.fits (V-band, visible light)
- h_n4603_f814_mosaic (2).fits (I-band, infrared light)

## How It Works

This Python script reads the FITS files for V-band and I-band images, processes them, and generates a color composite image.

Normalization adjusts brightness and contrast using the normalize() function. You can tweak the stretch and Q parameters for different appearances.

Since there is no blue-band data, the script synthesizes a blue channel by averaging the red and green channels.

The script then combines the red, green, and synthetic blue channels into an RGB image, and displays and saves the RGB image using Matplotlib.

## Example Output

The output is a PNG file named my_image.png, which visualizes NGC 4603 as a color composite.


Disclaimer: The work presented here is not entirely done by me from scratch. It have been completed with the help of online resources, \\
AI assistants, professors, and reference materials from other platforms working in the field of astrophysics.

