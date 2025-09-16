# Federation

## Updating a WordPress Website from FAIR

The simplest form of participation in FAIR is to download and install the FAIR Plugin. Once installed and activated, you’ll have largely achieved technical independence from [WordPress.org](http://WordPress.org). The plugin does a few specific things to achieve this:

- Intercepts API requests for package (plugins, themes) information to the API at [WordPress.org](http://WordPress.org) and redirects them to the AspireCloud API server. Packages installed this way will be drawn from the AspirePress mirror of the WordPress repository.
- You will have your choice of Gravatar or locally-generated avatar images.
- The news feed in your admin dashboard will come from FAIR’s “Planet” instance, which aggregates RSS feeds from independent sources.
- The events feed in your admin dashboard will come from [The WP World](https://thewp.world/events/), which includes both WordPress and other related Open Source events.
- Certain features are replaced with functions within the plugin rather than on a third-party site, including avatars (optional), the “Browse Happy” (browser check) service, generation of salts, and others.
- Certain features such as PHP version checks and Twemoji are replaced with third-party APIs or services, such as [php.net](http://php.net). Pingomatic notifications are replaced with [indexnow.com](http://indexnow.com), which is not only an open standard, but is more effective than the Pingomatic service, which is outdated.

In general, making fewer API calls with each page load will have a performance benefit, even if a small one in many cases.

## Plugin or Theme Developers or Publishers

## Hosts, Agencies, & Bulk Site Maintainers

## Operating An Aggregator, Repository, or Labeling Service