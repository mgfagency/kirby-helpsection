# Kirby 3 Help Section

![Kirby Version](https://img.shields.io/badge/kirby-3.0.1-cca000.svg?style=for-the-badge) ![Kirby 3 Pluginkit](https://img.shields.io/badge/Pluginkit-YES-cca000.svg?style=for-the-badge)

Adds a panel view to display help for users. The help pages are generated by a predefined content folder.

## Commerical usage and support

This plugin is free under the MIT license. If you use it in a commercial project or want to support the development please consider to

- [https://www.paypal.me/christianzehetner/2](make a donation) ☕ or
- [https://a.paddle.com/v2/click/1129/39016?link=1170](buy a Kirby license using this affiliate link) ️️️⭐

## Installation

### Download

Download and copy this repository to `/site/plugins/kirby-helpsection`.

### Git submodule

```
git submodule add https://github.com/mgfagency/kirby-helpsection.git site/plugins/kirby-helpsection
```

### Composer

```
composer require mgfagency/kirby-helpsection
```

## Options

All options require `mgfagency.helpsection.` as prefix.

**contentfolder**

- default: `helpsection`
- contents of this folder is loaded into the help view of the panel

## Setup

Add documentation pages to the specified content folder.

```
content
  helpsection
    doc.txt
    01-intro
      doc.txt
      image.png
    02-section-two
      doc.txt
```

## Disclaimer

This plugin is provided "as is" with no guarantee. Use it at your own risk and always test it yourself before using it in a production environment.

## License

[LICENSE.md](MIT)

## Credits

- [Bastian Allgeier for the kirby reference page](https://github.com/bastianallgeier)
