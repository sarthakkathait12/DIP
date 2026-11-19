# Image Compression

Two lossless compression scripts using only Python's standard library.

- `huffman_coding.py`: frequency-based prefix coding.
- `arithmetic_coding.py`: adaptive integer arithmetic coding.

## Run

From the repository root:

```bash
python compression/huffman_coding.py encode assets/input.png output/image.huf
python compression/huffman_coding.py decode output/image.huf output/huffman-restored.png

python compression/arithmetic_coding.py encode assets/input.png output/image.ari
python compression/arithmetic_coding.py decode output/image.ari output/arithmetic-restored.png
```

Both methods restore the exact original file. PNG/JPEG files are already compressed,
so the encoded file may be larger. Use these educational scripts with trusted files.

`examples/` contains sample archives and verified round-trip results.
