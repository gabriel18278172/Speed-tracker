# ⚡ Speed Tracker

A polished, real-time MPH/KPH speed tracker that runs entirely in your browser — no app install required. Open it on your phone while driving and it uses the device's GPS to display your precise speed.

## Features

| Feature | Details |
|---|---|
| **Live GPS Speed** | Uses `Geolocation.watchPosition` with `enableHighAccuracy: true` for GPS-grade accuracy |
| **Arc Speedometer** | Animated Canvas gauge that changes colour (green → cyan → orange → red) as speed increases |
| **MPH / KPH Toggle** | Switch units at any time; all stats update instantly |
| **Top Speed** | Highlights the peak speed reached during the session |
| **Trip Average** | Running average across all GPS readings since last reset |
| **Heading & Compass** | Shows bearing in degrees + compass direction (N, NE, SE, …) |
| **Altitude** | Current altitude in metres above sea level |
| **Speed History Sparkline** | 60-second rolling chart of speed history |
| **Accuracy Indicator** | Colour-coded GPS accuracy badge (±metres) |
| **Dark Theme** | Easy to read in a car, day or night |

## Usage

1. Open `index.html` in any modern mobile browser (Chrome, Safari, Firefox).
2. Tap **Enable GPS Tracking** when prompted for location permission.
3. Tap **Start Tracking** — the gauge will animate as you move.
4. Use **MPH / KPH** buttons to switch units.
5. Tap **Reset Stats** to clear trip data.
6. Tap **Stop Tracking** to pause.

> **Tip:** Add the page to your Home Screen for a full-screen, app-like experience on iOS and Android.

## Privacy

Your location data is processed entirely on-device. No data is ever transmitted to a server or stored anywhere.

## Browser Support

Any browser that supports the [Geolocation API](https://developer.mozilla.org/en-US/docs/Web/API/Geolocation_API) and `<canvas>` (Chrome, Edge, Firefox, Safari).
