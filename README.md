# MrScraper

Scrapes event data from [http://www.seetickets.com](seetickets).

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
% sudo npm install -g mrscraper
% mrscraper.js --help

Usage: node mrscraper.js [-v] [-h] [-t type]

Options:
  -h, --help     Show help
  -v, --verbose  Increase verbosity
  -t, --type     Event type to retrieve                      [default: "comedy"]
```
