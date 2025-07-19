# TorrentSearch

CLI tool to fetch, search, and display torrent information with colored output.

## Features

- **Home**: List torrents by category (TV Shows, Movies, Music, Games, Applications, Other, Top Torrents Last Week).
- **Search**: Search torrents by keyword.
- **Details**: Show detailed info and related torrents for a selected torrent.
- **Magnet Copy**: Copy magnet link to clipboard.
- **Colored Output**: Beautiful terminal tables and colors.

## Usage

```bash
> ts.exe
```

### Interactive Commands

- Enter a number (e.g. `1`, `2`, ...) to select and show details for a torrent.
- `[d]n` or `n[d]`: Show details for torrent number `n`.
- `[m]n` or `n[m]`: Copy magnet link of torrent number `n` to clipboard.
- `[r]n` or `n[r]`: Show related torrents for number `n` (when in related view).
- `s` or `search`: Search torrents.
- `h` or `home`: Back to home page.
- `q`, `quit`, `x`, or `exit`: Quit the program.
- `[N]n`: Set list length (default = 3).
- Any other input: Will be treated as a search query.

**In related torrents view:**
- Enter `[r]n` or `n[r]` to select a related torrent.
- Enter `m` to copy the magnet link of the current torrent.
- Enter `[m]n` or `n[m]` to copy the magnet link of a related torrent.
- Enter `h` to return to home.
- Enter `s` to search.

## Example Output

```
TV shows
  00. Star Trek Strange New Worlds S03E01 1080p WEB H264 SuccessfulCrab EZTV [2.62 GB]|[6536]|[399]
Movies
  01. ... 
```

## Author

[Hadi Cahyadi](mailto:cumulus13@gmail.com)

## Coffee

[![Buy Me a Coffee](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/cumulus13)

[![Donate via Ko-fi](https://ko-fi.com/img/githubbutton_sm.svg)](https://ko-fi.com/cumulus13)

[Support me on Patreon](https://www.patreon.com/cumulus13)