# szurubooru

Szurubooru is an image board engine inspired by services such as Danbooru,
Gelbooru and Moebooru dedicated for small and medium communities. Its name [has
its roots in Polish language and has onomatopeic meaning of scraping or
scrubbing](https://sjp.pwn.pl/sjp/;2527372). It is pronounced as *shoorubooru*.

## Features

- Post content: images (JPG, PNG, GIF, animated GIF), videos (MP4, WEBM), Flash animations
- Ability to retrieve web video content using [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- Post comments
- Post notes / annotations, including arbitrary polygons
- Rich JSON REST API ([see documentation](doc/API.md))
- Token based authentication for clients
- Rich search system
- Rich privilege system
- Autocomplete in search and while editing tags
- Tag categories
- Tag suggestions
- Tag implications (adding a tag automatically adds another)
- Tag aliases
- Pools and pool categories
- Duplicate detection
- Post rating and favoriting; comment rating
- Polished UI
- Browser configurable endless paging
- Browser configurable backdrop grid for transparent images


## Installation

It is recommended that you use Docker for deployment.
[See installation instructions.](doc/INSTALL.md)

More installation resources, as well as related projects can be found on the
[GitHub project Wiki](https://github.com/rr-/szurubooru/wiki)

## Screenshots

Post list:

![Screenshot 2024-07-21 at 14-14-27 Senryuubooru – Listing posts](https://github.com/user-attachments/assets/75f00d77-3791-4b6c-8a76-3fad44580622)

Post view:

![Screenshot 2024-07-21 at 14-19-06 Senryuubooru – Post #543](https://github.com/user-attachments/assets/1a55a5c9-530c-4ee4-89a5-0153a56ecbf3)

## License

[GPLv3](LICENSE.md).
