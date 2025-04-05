# Heroku ZSign Buildpack

This is a custom Heroku buildpack to compile and install [zsign](https://github.com/zhlynn/zsign), including `minizip`, into your app’s slug.

## Usage

1. Add this buildpack **before** your main app buildpack:
```bash
heroku buildpacks:add --index 1 https://github.com/your-username/heroku-zsign-buildpack.git
