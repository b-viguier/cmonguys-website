# C'Mon Guys website

[https://cmonguys.fr](https://cmonguys.fr)

## Development

```bash
docker run --rm -it -e JEKYLL_ROOTLESS=1 --volume="$PWD:/srv/jekyll" -p 4000:4000 -p 35729:35729 jekyll/jekyll jekyll serve --livereload
```

Then open `http://localhost:4000/`.