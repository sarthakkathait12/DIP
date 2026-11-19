# Digital Image Processing

Simple Python examples for image filtering and lossless compression.

- [Image filters](image_filters/): smoothing, sharpening, and edge detection.
- [Compression](compression/): Huffman and Arithmetic coding.

## Run

```bash
python -m pip install -r requirements.txt
python image_filters/apply_filters.py
```

Results are saved in `image_filters/output/`.

## Layout

- `image_filters/`: `apply_filters.py`, `smoothing.py`, `sharpening.py`, and `image_utils.py`.
- `compression/`: `huffman_coding.py` and `arithmetic_coding.py`.
- `assets/input.png`: shared sample image. Pass `--input path/to/image.jpg` to use another image.
- `requirements.txt`: filter dependencies.
