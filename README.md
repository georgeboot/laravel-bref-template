# laravel-bref-template

This package is a good starting point for deploying your full-featured Laravel app using bref.sh.

## How to use

- Copy the GitHub Action
- Copy `serverless.yml` file
- Install `bref/bref` and `bref/bref-laravel` (note https://github.com/brefphp/laravel-bridge/pull/31)
- Make sure you have `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` in your secrets.
- run `serverless deploy` (and use `serverless delete` to take down everything that was created)
