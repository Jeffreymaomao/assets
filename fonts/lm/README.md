# Latin Roman

Latin Roman (lm) fonts is downloaded from [CTAN](https://ctan.org/tex-archive/fonts/lm).

- `opentype`: original files
- `woff2`: converted files
- `woff`: converted files

```bash
mkdir -p woff2
for f in opentype/*.otf; do
  woff2_compress "$f"
  mv "${f%.otf}.woff2" woff2/
done
```
