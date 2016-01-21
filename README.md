# Public Beta 11

After nearly 3,000 commits, nearly a year of development, and nearly a swimming pool’s worth of coffee, we’re finally here! Thank you for being willing to try, test, and experiment with pre-release software. You are a neat person.


## Answers to questions you probably have

### Where do I get the latest release?
Right here in Github. Head to the [Releases section](https://github.com/statamic/v2-beta/releases) and download the latest packaged zip file (not **Source Code**).

### Where are the docs?

Right here: <http://docs.talonsbeard.com>. Please don't share them publicly.

### Is the beta production ready?

Yup! Feel free to build and launch something. We’d love to see it! Just know that there’s a higher than normal chance of a bug or snag or something, and that during the beta there may be backwards incompatible changes that would require manual changes to your site, so keep that in mind.

### Where's the discussion happening?

On [Slack](http://slack.statamic.com)! If you're not in the `#beta` room you're missing out. On gifs.

### OMG something broke where do I submit a bug??

First, check to see if there's a similar issue filed already (open or closed). 

Next, make sure it's not a cache issue. Clear your cache using `php please cache:clear` or delete everything inside `local/cache` and `local/storage` and try again. If your issue goes away, let us know what happened so we can fine tune our cache invalidation. Otherwise, open an [Issue](https://github.com/statamic/v2-beta/issues/new) with as much detail as you can. PHP/Server environment, content types, YAML/template examples, etc.

## [The Community Wiki](https://github.com/statamic/v2-beta/wiki)

Feel free to use the Community Wiki to drop in notes for other beta users and for us to reference as we continue to write and refine the documentation. Anything is fair game.
