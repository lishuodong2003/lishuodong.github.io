# Lishuo Dong's personal homepage

This repository contains the source files for Lishuo Dong's academic homepage.

## Edit your information

- Site title, contact details, and navigation: `_config.yml`
- English homepage: `index.md`
- Chinese homepage: `cn.md`
- Research page: `publications.md`
- Honors page: `awards.md`
- Profile photo: `assets/images/profile.png`
- Visual styling: `assets/css/custom.css`

## Preview locally

Install Ruby and Bundler, then run:

```bash
bundle install
bundle exec jekyll serve
```

The site is published at `https://lishuodong2003.github.io/`. Keep `baseurl` empty in `_config.yml` so page links and static assets resolve from that root address.
