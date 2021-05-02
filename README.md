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

- [`screenshots.sh`](/scripts/screenshots.sh)

    Generate the screenshots featured in this README.

## Installation

1. Fork the "Index" theme in Blot
2. Rename the fork to jot-prod
3. Fork the "Index" theme again
4. Rename the fork to jot-dev
5. Edit both themes locally from blot.im
6. Replace both directories with git clones of this theme
7. On the "development" theme use the "main" branch
8. On the "production" theme use the "release" branch
9. Activate the "Jot - Production" theme

Workflow
- Edit the development clone branch
- Preview in blot.im using the "Jot" theme to preview
- Commit to main

Releasing
- Merge main to release
- Git fetch/update the directory of the "Jot - Production" theme to the latest release branch
- Blot will immediately pick up the changes and apply to the production site

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

