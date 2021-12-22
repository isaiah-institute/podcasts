Isaiah Institute Podcasts
=========================

Layout
------

- `_config.yml`: Site-wide configuration settings
- `*.xml`: Each podcast has its own XML file at the root level, which contains podcast-specific configuration.
- `_posts/`: Holds individual podcast episodes. Each subdirectory holds podcast expisode files. Episodes are assigned to each podcast by _tag_, not by virtue of the directory it resides in.
- `assets/`: Contains podcast images.
- `_includes/podcast.xml`: This template contains the structure for the podcast feed XML.

Publishing changes
------------------

This podcast / site is built with Jekyll and is published via GitHub pages shortly after changes are pushed. See the [settings page](settings/) under GitHub Pages for status and configuration.

- "Your site is ready to be published" (blue) = updates pending
- "Your site is published" (green) = changes are live

Publishing a new podcast
------------------------

See the [Publishing a new podcast](https://github.com/isaiah-institute/podcasts/wiki/Publishing-a-new-podcast) wiki page.

Testing changes locally
-----------------------

1. [Install Jekyll](https://jekyllrb.com/docs/installation/)
2. Run `jekyll build`
3. Examine the resulting podcast XML file under `_site/`.
