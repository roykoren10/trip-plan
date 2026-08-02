# Sicily Trip Planner

An interactive Sicily itinerary for 26 August–5 September 2026, covering Palermo, Cefalù, San Vito lo Capo, and the return to Palermo.

## Features

- Interactive overview and daily maps
- Cursor-centered wheel and trackpad zoom
- Two-finger pinch zoom and map dragging
- Expandable daily itineraries and summaries
- Google Maps links for every place, route leg, and full day
- Editable hotel links saved privately in the browser
- Confirmed stays, flight times, and car-rental timing without private reservation details
- Timing alerts for late check-in and the final Palermo car return

## Run locally

From this directory, run:

```bash
python3 -m http.server 8766 --bind 127.0.0.1
```

Then open <http://127.0.0.1:8766/>.

The ready-to-open standalone page is `index.html`. The editable visualization fragment is in `src/`.

## Itinerary sources

The daily plan uses official regional guidance for [Palermo](https://www.visitsicily.info/en/localita/palermo/), [Cefalù](https://www.visitsicily.info/en/luogo/cefalu/), [the Zingaro Reserve](https://www.visitsicily.info/en/the-zingaro-reserve/), and [western Sicily](https://www.visitsicily.info/en/itinerario/scopello-san-vito-lo-capo-marsala-and-their-surroundings/).
