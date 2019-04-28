# Updating Demo Page (GH-Pages branch)

1. Rebase master to gh-pages

```bash
git checkout gh-pages // go to the gh-pages branch
git rebase master // bring gh-pages up to date with master
```

2. Delete nearly all files, leaving only those remaining to serve gh-pages:


- /css
- .gitignore
- CNAME
- demo.html
- README.md


3. Rename demo.html to index.html

4. Commit changes and push

```bash
git add .
git commit -m 'Some descriptive commit message'
git push origin gh-pages
```

---
I'm sure there's a better way to do this, but these steps work in the meantime
