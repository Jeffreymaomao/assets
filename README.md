# assets

### Clone repository

```bash
git clone --depth=1 --filter=blob:none --sparse https://github.com/Jeffreymaomao/assets.git
cd assets
```

### Fetch specific directory

```bash
git sparse-checkout set folder1 folder2 ...
```

### Add specific directory

```bash
git sparse-checkout add folder3
```

```bash
git sparse-checkout set <some_dir> another/path
git add path/to/subdir/somefile
git commit -m "Add my file into subdir"
git push origin HEAD:my-branch
```

How to use
```
https://cdn.jsdelivr.net/gh/Jeffreymaomao/assets/...
```