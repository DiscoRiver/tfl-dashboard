# London Rail Pulse

A single-page dashboard of live London rail disruptions and station crowding, drawn on a map that runs from Reading to Shenfield.

- **Line status** for the Tube, Elizabeth line, DLR, London Overground, Trams, Great Western Railway and South Western Railway. Refreshes every 60 seconds.
- **Station crowding** at 24 busy Tube stations, shown as busyness compared with a typical day at that time. Refreshes every 5 minutes.
- **Route geometry** comes from TfL's route sequences and is cached in the browser for a day.

The page calls the [TfL Unified API](https://api.tfl.gov.uk) straight from the browser. It needs no build step and no server. You can add an optional TfL app key in the page footer to get a higher rate limit. The key is stored only in your browser.

## Publishing

Settings → Pages → Deploy from a branch → `main` / root.

Powered by TfL Open Data. Basemap © OpenStreetMap contributors © CARTO.
