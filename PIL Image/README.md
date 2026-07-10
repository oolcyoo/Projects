# ASCII Image Converter

A small Python script that converts an image into ASCII art. It uses Pillow to resize an image, convert it to grayscale, map pixels to characters, print the result, and save the output to `img.txt`.

## Run

```bash
python3 "from PIL import Image.py" path/to/image.jpg
```

A URL can also be passed instead of a local path:

```bash
python3 "from PIL import Image.py" https://example.com/image.jpg
```

## Notes

- Dependency: `Pillow`.
- The current script name came from the original upload and should be renamed in a future cleanup pass.
- The generated `img.txt` and downloaded `asciify.jpg` files are local outputs and should not be committed.
