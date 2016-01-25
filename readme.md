# Design, Build, Test, Repeat Podcast

This is a [Jekyll](https://jekyllrb.com/) blog, that hosts the Design, Build, Test, Repeat podcast. Hosted by [Eric Bailey](https://twitter.com/ericwbailey) and [Mike Kivikoski](https://twitter.com/mkivikoski). Recorded, cut, and mixed by Jeremy Brody.

## Setup

### Clone repo.

```bash
$ git clone git@github.com:cantinac/design-build-test-repeat.git && cd design-build-test-repeat
```

### Install required gems:

```bash
$ bundle install
```

### Start server
```bash
$ jekyll serve
```

## Testing
Before pushing to github, test your code using:
```bash
$ rake test
```

## Process for adding new podcast
- Create branch `feature/episode-<##>-<episode-name>` 
- Create a new post `.md` file  in `/_posts` called `<year>-<month>-<day>-episode-<##>-<episode_name>.md`
- Paste in the Soundcloud iframe, changing the height to `250`
- Add _In this Episode:_ description
- Add show note links
- For a template guide, here is [Episode 00](http://dbtr.fm/2016/01/20/episode-00-introductions.html)
- Before pushing, test your code.
- Create a PR, and wait for a LGTM or thumbsup
- When PR is accepted, merge into `master`
- Master is auto deployed to [http://dbtr.fm](http://dbtr.fm) (may take a few minutes)
- Delete your branch

## Process for contributing
- Create an Issue
- Create a `feature/` or `bug/` branch that corresponds with issue
- Work in that branch
- Before pushing, test your code.
- Create a PR, and wait for a LGTM or thumbsup
- When PR is accepted, merge into `master`
- Master is auto deployed to [http://dbtr.fm](http://dbtr.fm) (may take a few minutes)
- Delete your branch