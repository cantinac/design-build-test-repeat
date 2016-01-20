# Design, Build, Test, Repeat Podcast

This is a [Jekyll](https://jekyllrb.com/) blog, that hosts the Design, Build, Test, Repeat podcast. Hosted by [Eric Bailey](https://twitter.com/ericwbailey) and [Mike Kivikoski](https://twitter.com/mkivikoski). Recorded, cut, and mixed by Jeremy Brody.

## Setup

### Clone repo.

```bash
$ git clone git@github.com:mkivikoski/design-build-test-repeat.git && cd design-build-test-repeat
```

### Install required gems:

```bash
$ bundle install
```

### Start server
```bash
$ jekyll serve
```

### Testing
Before pushing to github, test your code using:
```bash
$ rake test
```

## Process
- Create an Issue
- Create a `feature/` or `bug/` branch that corresponds with issue
- Work in that branch
- Before pushing, test your code.
- When work is ready, do a PR into `master`
- When PR is accepted, merge into `master`
- Merge `master` into branch `gh-pages` and push. 
- `gh-pages` is deployed to staging github site [http://mkivikoski.github.io/design-build-test-repeat/](http://mkivikoski.github.io/design-build-test-repeat/)