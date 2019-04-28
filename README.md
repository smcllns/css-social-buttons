# Updating Demo Page
(https://smcllns.github.io/css-social-buttons/)

1. Update zocial files or demo page (`index.html`) in `master`


2. Copy latest zocial css and demo page to `gh-pages`

```bash
git checkout gh-pages // go to the gh-pages branch
git checkout master css // copy css folder from master to gh-pages
git checkout master index.html // copy index.html from master to gh-pages
```

3. Commit changes and push

```bash
git add .
git commit -m 'Some descriptive commit message'
git push origin gh-pages
```
