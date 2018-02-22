# localdev-light

Super-lightweight local development server

## What's it for?

In my last job I had to do updates and changes for a bunch of sites that did not have real (or at least updated) localdev support. It would all be hit-and-miss, hoping that something worked. So the easiest way to get stuff done would be to do a quick siterip and work based on that, before doing the validated changes in source code.

This package is pretty much just [Browsersync](https://browsersync.io/) set up to look at changes in the src folder. There's CORS and HTTPS turned on which you might need.

So in case you're where I was, just download your static assets to the src folder and start up **localdev-light** with `yarn start`.

## Documentation

Need to tweak this? Look at the [Browsersync documentation](https://browsersync.io/docs/command-line) where they go through how to make this do what you want.
