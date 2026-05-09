# AA Seat View · URL Builder

A lightweight, single-file web tool that generates direct links to the [American Airlines interactive seat map](https://www.aa.com/seats/view) for any flight.

**[Go There →](https://panoramixservices.com/aaseats)**

---

## What it does

The AA seat map URL requires five parameters that aren't obvious to assemble by hand:

```
https://www.aa.com/seats/view?flightNumber=1038&departureMonth=5&departureDay=12&originAirport=ORD&destinationAirport=PHX
```

This tool gives you a form to fill in your flight details and builds that URL instantly — ready to copy or open in one click.

## Usage

1. Enter your **flight number**
2. Enter your **origin** and **destination** airport codes (e.g. `JFK`, `LAX`)
3. Pick your **departure date** from the calendar
4. Copy the generated URL or click **Open on AA.com**

## Tech

- Plain HTML, CSS, and JavaScript — no frameworks, no build tools
- Single self-contained file
- [Syne](https://fonts.google.com/specimen/Syne) + [DM Mono](https://fonts.google.com/specimen/DM+Mono) via Google Fonts (requires internet connection to load typefaces; layout works fine without them)

## Disclaimer

This tool is not affiliated with, endorsed by, or connected to American Airlines in any way. It simply constructs a URL using publicly available query parameters. All flight data and seat maps are owned by American Airlines.

## License

MIT
