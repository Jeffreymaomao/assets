# assets

```bash
git clone --depth=1 --filter=blob:none --sparse https://github.com/Jeffreymaomao/assets.git
cd assets

git sparse-checkout set <some_dir> another/path
git add path/to/subdir/somefile
git commit -m "Add my file into subdir"
git push origin HEAD:my-branch
```

How to use
```
https://cdn.jsdelivr.net/gh/Jeffreymaomao/assets/...
```