# Firefox Browser Extension for Nextcloud Bookmarks

This is a Firefox extension for [Nextcloud Bookmarks](https://github.com/nextcloud/bookmarks), a bookmark application for Nextcloud. It allows you to add, search, and delete your Nextcloud Bookmarks, but does not synchronize your browser bookmarks with Nextcloud Bookmarks.

## Available Features

* Add new bookmarks
* List latest bookmarks
* Search bookmarks by title and description
* Search bookmarks by tag or by a tag combinations (like 'tag1 AND tag2 AND tag3' and 'tag1 OR tag2 OR tag3')
* Delete bookmarks
* Choose to display the bookmark form or the search form

## Missing features

* Cannot search for a bookmark starting from a URL (API lacks the method)
* Cannot retrieve the list of already set tags (API lacks the method)
* Cannot edit bookmarks
* No translations / localization

# Help needed

I'd love to have any kind of feedback on this extension. If you are a developer have a look at the code and please open issues or send greatly appreciated PRs. If you are not a developer please open issues and tell me what's not working for you. Thank you!

# Installation

## Server side

Ensure server running >= Nextcloud 12.04

## Client side (browser)

Install extension from Mozilla Extensions page, or load as a temporary add-on

> **Don't forget to configure the addon settings:**
* URL of your Nextcloud server
* Nextcloud username
* Nextcloud password

# Privacy Policy

This extension communicates ONLY with your Nextcloud server; there is no tracking of any kind, and no third parties involved.
