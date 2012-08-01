# YRS 2012 - website for Cloud Foundry

This is a trivial app serving static content using the Sinatra framework in Ruby. It is being used to provide basic information for the [Young Rewired State](http://youngrewiredstate.org) event and is [online](http://yrs2012.cloudfoundry.com) for reference.

## Overview

This simple app uses:

- Ruby
- [Sinatra](http://www.sinatrarb.com/)
- [Twitter Bootstrap](http://twitter.github.com) for visual sugar
- [Font Awesome](http://fortawesome.github.com/Font-Awesome) for nice iconography
- [Gravatar](http://gravatar.com) for avatar icons
- [IconDock Vector Social Media Icons](http://icondock.com/free/vector-social-media-icons)

## Deployment

What are all these files?

Nothing, really. No, really. Everything in the ``public`` folder is there as a placeholder. All you need to get going is the web.rb file, and optionally the Gemfile. Put your own static web content (with an index.html file, and maybe a 404.html file) in the ``public`` folder, and either:

 * run ``ruby web.rb`` from the root directory; or
 * deploy to Cloud Foundry as a Sinatra application

 … and you are good to go.

Optionally, fiddle with the settings in the top of the web.rb file to tweak how things work.
