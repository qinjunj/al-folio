# Qinjun Jiang’s academic website

Built with [al-folio](https://github.com/alshedivat/al-folio). Migrated from [qinjunj.github.io](https://github.com/qinjunj/qinjunj.github.io).

## Preview locally

Use Ruby 3.3 or newer. This local checkout includes an isolated Ruby in `vendor/ruby`; new clones need Ruby installed.

For the prepared local checkout, run `./bin/preview`.

```sh
export PATH="$PWD/vendor/ruby/bin:$PATH"
bundle install
bundle exec jekyll serve --livereload --livereload-port 35730 --host 127.0.0.1 --port 4001
```

Open http://127.0.0.1:4001/al-folio/. Restart the server after editing `_config.yml`.

## Edit content

- Biography: `_pages/about.md`
- Publications: `_bibliography/papers.bib`
- CV: `_pages/cv.md` (the original CV text is preserved)
- Profile links: `_data/socials.yml`
- Photo: `assets/img/selfie.jpeg`
- Site settings: `_config.yml`

## Publish

In the repository’s **Settings → Pages**, select **GitHub Actions** as the source. Pushing to `main` builds and deploys https://qinjunj.github.io/al-folio/.

The original homepage remains at https://qinjunj.github.io/. To make this site the root homepage later, migrate it into the `qinjunj.github.io` repository and set `baseurl: ""`.
