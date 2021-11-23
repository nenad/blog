# blog

## Dev mode

Make sure your working directory is the root of the blog and run:

```shell
docker run --rm -e JEKYLL_UID=$UID -e JEKYLL_GID=$GID -it -p 4000:4000 --volume $(pwd):/srv/jekyll jekyll/jekyll jekyll serve
```

## TODO

- [ ] Set up GitHub pages for this site
- [ ] Set up blog.nenad.dev to point to this published blog
- [ ] Have a dark theme
- [ ] Make content!
