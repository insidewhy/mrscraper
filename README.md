# MrScraper

Scrapes [http://www.seetickets.com/search?s=comedy&c=76&q=&dst=&dend=&l](see ticket comedy list).

Retrieves:
  * Event name
  * Event link (to seetickets)
  * Event date (optional, some events cover many dates)
  * Artists as array.
  * Venue name.
  * Venue link.
  * Venue address fields (of which there can be up to 6, optional as some venues are virtual).

## Running

```
npm install
mrscraper.js --help

totoro@host mrscraper % mrscraper.js -h
Usage: node mrscraper.js [-v] [-h] [-t type]

Options:
  -h, --help     Show help
  -v, --verbose  Increase verbosity
  -t, --type     Event type to retrieve                      [default: "comedy"]
```
