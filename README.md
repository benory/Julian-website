# Julian Ory

A minimal Jekyll website displaying a single photograph.

## Local preview

```sh
bundle install
bundle exec jekyll serve
```

Open http://localhost:4000.

## Build

```sh
bundle exec jekyll build
```

Publish the generated `_site` directory through your hosting provider.
For hosting under a subdirectory, set `baseurl` in `_config.yml`.

## Photograph

Only the resized JPEG in `assets/images/julian.jpg` is used by the site.
It was oriented before conversion and stripped of embedded metadata,
including EXIF, GPS, timestamps, device information, and profiles.
The original HEIC is not included in the repository.

When replacing the photograph, strip metadata from the replacement before
committing it. The page uses no analytics, external fonts, or third-party scripts.
