# NetBar

A small macOS menu bar app that shows live download and upload rates.

## Build and run

Requires macOS 13 or later and Swift 5.9 or later.

```sh
swift run
```

The menu bar title refreshes once per second. Open it for separate upload and download rates. Traffic counters are read from macOS `netstat` for `en*` interfaces; rates start at zero until the first counter comparison is available.
