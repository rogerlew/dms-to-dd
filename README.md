# dms-to-dd

A tiny JavaScript-based web utility to convert DMS (degrees, minutes, seconds) coordinates to decimal degrees. Paste strings like `72d19'40.96"W, 37d49' 4.29"S` and get back clean decimal coordinates.

**Live Demo:** [https://rogerlew.github.io/dms-to-dd](https://rogerlew.github.io/dms-to-dd)

## Features

- Accepts DMS with or without spaces (e.g., `37d49'4.29"S` or `37d49' 4.29"S`)
- Parses common directional suffixes (N, S, E, W)
- Automatically converts both lat and lon
- Lightweight and runs entirely in the browser

## Usage

1. Paste your DMS string into the text area.
2. View the converted decimal degrees below.

## Development

To run locally:

```bash
python -m http.server 8000
```

Then open [http://localhost:8000](http://localhost:8000) in your browser.

## License & Attribution

This project is released into the [public domain](https://creativecommons.org/publicdomain/zero/1.0/) under the [CC0 1.0 Universal License](https://creativecommons.org/publicdomain/zero/1.0/). You are free to copy, modify, distribute, and use it without restriction.

Vibe-coded in literally 5 minutes with [ChatGPT](https://chatgpt.com/share/67f59523-1688-8009-aea9-75db3b01da42)

## Disclaimer

This tool is provided "as-is" with no warranties or guarantees. It is intended for informal or educational use. Do not rely on it for navigation, mission-critical calculations, or life-and-death situations. Always verify coordinates with trusted GIS tools or libraries.

---

© rogerlew no rights reserved.
