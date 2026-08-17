# Zhipeng Liu — personal homepage

Static site for GitHub Pages: https://liuzhipenggg.github.io/

## Preview

```bash
python3 -m http.server 8765
```

Then open http://127.0.0.1:8765

## Push

Create a **public** repository named `liuzhipenggg.github.io` (empty, no README), then:

```bash
cd /Users/galaxy/Projects/liuzhipenggg.github.io
git remote -v   # origin should be https://github.com/liuzhipenggg/liuzhipenggg.github.io.git
git push -u origin main
```

GitHub Pages for a `username.github.io` repo serves `main` from the root automatically. After the first push, wait a minute and open https://liuzhipenggg.github.io/
