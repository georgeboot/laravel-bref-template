# laravel-bref-template

This package is a good starting point for deploying your full-featured Laravel app using bref.sh.

## How to use

- Copy the GitHub Action
- Copy `serverless.yml` file
- Install `bref/bref` and `bref/bref-laravel` (note https://github.com/brefphp/laravel-bridge/pull/31)
- Make sure you have `AWS_ACCESS_KEY_ID` and `AWS_SECRET_ACCESS_KEY` in your GitHub Repo secrets.
- Walk through `.github/workflows/deploy.yml` and `serverless.yml`, look for references to `laravel-bref-template` and
  others, and replace them with actual values.
- For values referencing ssm, use Bref's dashboard (`vendor/bin/bref dashboard`) or use the AWS CLI / Console to create
  them.
- Run `serverless deploy` (and use `serverless delete` to take down everything that was created)
