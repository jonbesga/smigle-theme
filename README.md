# smigle-hugo-theme

A minimalist theme for the static site generator [Hugo][hugo].

### Screenshots

![smigle screenshot-1][screenshot-1]

### Features
- No JavaScript
- No Google spyware or tracking of any kind
- No other external dependencies or comment sections
- Only one local font ([Iosevka][font])

### Run example site

```bash
hugo new site mysite -f yaml
cd mysite
git init
git submodule add https://gitlab.com/ian-s-mcb/smigle-hugo-theme themes/smigle
cd themes/smigle/exampleSite
hugo server
```

### Contributing
Have you found a bug or got an idea for a new feature? Feel free to use
the [issue tracker][issue-tracker] to let me know. Or make directly a
[merge request][merge-request].

### Acknowledgements

This theme was created from scratch and influenced by the following two
Hugo themes:

- [colorchestra's smol][smol-colorchestra]
- [Sumner Evans's smol][smol-sumner]

[hugo]: https://gohugo.io/
[screenshot-1]: /images/screenshot.png
[font]: https://github.com/be5invis/iosevka
[issue-tracker]: https://gitlab.com/ian-s-mcb/smigle-hugo-theme/-/issues
[merge-request]: https://gitlab.com/ian-s-mcb/smigle-hugo-theme/-/merge_requests
[smol-sumner]: https://github.com/sumnerevans/smol
[smol-colorchestra]: https://github.com/colorchestra/smol
