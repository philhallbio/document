# gliff.ai DOCUMENT

[gliff.ai](https://gliff.ai)'s user documentation for the gliff.ai platform, a user-friendly browser interface for curating, annotating and collaborating with imaging data or machine learning.

Built using the [Just The Docs](https://pmarsceill.github.io/just-the-docs/) Jekyll template.

## To set-up locally

Setting up locally allows you to make changes and test them out before making a push and PR.

1. install [Ruby <2.7](https://www.ruby-lang.org/en/documentation/installation/)
2. install [bundler](https://bundler.io/) with `gem install bundler`
3. make bundle install everything locally (so no sudo required) with `bundle config set --local path 'vendor/bundle'`
4. install dependencies locally with `bundle install`
5. install npm dependencies for lint and format with `npm i`

## To update locally (do this regularly)

1. update dependencies with `bundle update` and `npm update`

## To run locally

1. run `bundle exec jekyll serve -H 127.0.0.1`
2. go to [http://127.0.0.1:4000/]
3. hit `ctrl`+`c` to stop the server

## To lint and format your changes

1. run `npm run lint`
2. run `npm run format`
