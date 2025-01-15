# Watermark Embedding Tool

This project embeds an **invisible text watermark** into an image by modifying the least significant bit (LSB) of the blue channel in the image's pixel data. The watermark text is repeated in a grid pattern, making it invisible to the naked eye but retrievable for verification purposes.

## Features

- Invisible watermarking using Least Significant Bit (LSB) encoding.
- Customizable watermark text.
- Automatic font size adjustment based on the image dimensions.
- Outputs a watermarked image while preserving the original image.

## Requirements

Ensure you have Python 3.7+ installed along with the following Python libraries:

- **Pillow**: For image manipulation.
- **NumPy**: For efficient array-based operations.

Install the required dependencies using the following command:

```bash
pip install -r requirements.txt
