# [Blot][blot] Theme: Jot

This is the [theme][blog] for [Blot]. It's a fork of [Paul Esch-Laurent's blot theme][paul-theme].

## Features (from Paul's original theme)

- Light and dark theme(!!)
- Navigational keyboard shortcuts (<kbd>h</kbd>, <kbd>j</kbd>, <kbd>k</kbd>, and <kbd>l</kbd>)
- Hash `id`s for each header
- `is-active` class for active menu links
- Outlined footnotes & refs when `:target`ed
- Canonicalized URLs (`/` is canonical of `/page/1`)
- OpenGraph image `<meta>` from thumbnails
- Display last-modified date in entries
- [instant.page] for just-in-time preloading
- `/tags` page to list all tags
- Non-permalink RSS `<guid>`s
- [CSS hyphenation](http://clagnut.com/blog/2395)
- [Deploy script](/scripts/deploy.sh)

## Modifications

- None (yet)

## Screenshots

![Index Light](/screenshots/index-light.png)

![Index Dark](/screenshots/index-dark.png)

![Post Light](/screenshots/post-light.png)

![Post Dark](/screenshots/post-dark.png)

## [Scripts](/scripts)

- [`deploy.sh`](/scripts/deploy.sh)

    In Blot themes are edited in local directories and changes are immediately
    live on the site. To separate development from production this theme has a
    [`deploy.sh`](/scripts/deploy.sh) script to copy files from the development
    directory (an available but not active theme) to the production directory
    (an available and active theme). Once copied to the production folder the
    changes are live.

    This approach allows using Blot's template preview function to preview the
    development theme before copying the changes to the production theme.

- [`screenshots.sh`](/scripts/screenshots.sh)

    Generate the screenshots featured in this README.

## Installation

1. Fork the "Index" theme in Blot
2. Rename the fork to jot-prod
3. Fork the "Index" theme again
4. Rename the fork to jot-dev
5. Edit both themes locally
6. Replace the local version of the dev theme with this git project
7. Update the deploy script to know the correct production theme directory e.g. `../jot-prod`
8. Run the deploy script to update the production theme
9. Activate the jot-prod theme

## License

[Blot], including the base Index theme, is licensed by
[David Merfield][david] under [CC0].

Jot, the theme this was forked from, is licensed under [pinjasaur.mit] by [Paul Esch-Laurent][Pinjasaur].

Modifications by myself, [Stephen Ball][sdball], are licensed under [sdball.mit].

[blog]: https://www.rakeroutes.com
[Blot]: https://blot.im
[CC0]: https://github.com/davidmerfield/Blot/blob/master/LICENSE
[david]: https://github.com/davidmerfield
[sdball]: https://github.com/sdball
[pinjasaur.mit]: https://pinjasaur.mit-license.org
[sdball.mit]: https://sdball.mit-license.org
[instant.page]: https://instant.page
[paul-theme]: https://github.com/Pinjasaur/blot-theme-jot
[Pinjasaur]: https://github.com/Pinjasaur

