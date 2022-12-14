# Hydra!

Marketing site template for Hugo. Browse through a [live demo](https://sage-turtle.cloudvent.net/).
Increase the web presence of your brand with this configurable theme.

![Hydra template screenshot](static/image/_screenshot.png)

Hydra was made by [CloudCannon](https://cloudcannon.com/), a Jamstack platform for the whole team.

[![Deploy to CloudCannon](https://buttons.cloudcannon.com/deploy.svg)](https://app.cloudcannon.com/register#sites/connect/github/CloudCannon/hydra-hugo-template)

## Features

* Contact form
* Pre-built pages
* Pre-styled components
* Blog with pagination and category pages
* Disqus comments for posts
* Author system
* Configurable footer
* Optimised for editing in [CloudCannon](https://cloudcannon.com/)
* RSS/Atom feed
* SEO tags
* Google Analytics

## Setup

1. Add your site and author details in `config.toml`.
2. Add your Google Analytics and Disqus keys to `config.toml`.
3. Get a workflow going to see your site's output (with [CloudCannon](https://app.cloudcannon.com/) or Hugo locally).

## Develop

Hydra was built with [Hugo](https://gohugo.io/) version `0.76.5`, but should support newer versions as well.

Run the standalone executable `hugo` to serve the site locally:

~~~bash
$ hugo server
~~~

## Editing

Hydra is set up for adding, updating and removing pages, authors, posts, company details and footer elements in [CloudCannon](https://app.cloudcannon.com/).

### Posts

* Add, update or remove a post in the *posts* section.
* The **author** field links to the **authors** data.
* Change the defaults when new posts are created in `archetypes/posts.md` or `posts/_defaults.md`.

### Contact Form

* Preconfigured to work with [CloudCannon](https://app.cloudcannon.com/), but easily changed to another provider (e.g. [FormSpree](https://formspree.io/)).
* Sends email to the address listed in company details.

### Staff

* Reused around the site to save multiple editing locations.

### Footer

* Set how this displays with each page front matter in `menu.footer`.

