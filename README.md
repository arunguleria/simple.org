# Simple.org

This repository houses the source code for the Simple app website.

## Development

We use [Middleman](https://middlemanapp.com/) to build the static pages which are hosted on [GitHub Pages](https://pages.github.com/).

To run the site on your own machine, simply clone the repo, install the packages necessary, and start up a Middleman server.

```
$ git clone git@github.com:resolvetosavelives/simple.org.git
$ cd simple.org
$ bundle install
$ middleman server
```

Now you should be able to go to http://localhost:4567 and see the site running locally.

## Deployment

After merging your commits to `master` and pulling the latest, run `rake publish`.

If try to deploy and get `error: src refspec gh-pages does not match any`, delete the `build` directory and try `rake publish` again.

If you continue to have issues deploying, email cvallejo@resolvetosavelives.org.