# Color Palette Extractor

Open an image, get its dominant colors back as a row of swatches with hex
codes. Click any swatch to copy its code to the clipboard.

## Setup

    pip install -r requirements.txt
    python main.py

The clustering (`palette_logic.py`) is a small hand-written k-means over a
downsampled copy of the image, so it stays fast even on large photos.
