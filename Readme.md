# Run locally the website
Cryptohub-web rely on [Gulp](http://gulpjs.com/)
to run the project locally, do the following

```bash
gulp serve
```

to run the project in a production environement, do the following

```bash
gulp serve:dist
```

# Submit a new version

```bash
gulp dist
guld build
git subtree push --prefix dist origin gh-pages
```


