# Wedding Map - Buena Vista Guide

An interactive map showcasing favorite spots in Buena Vista, Colorado for wedding guests.

## Features

- 🗺️ Interactive Mapbox map with custom emoji markers
- 📍 25+ curated locations including restaurants, coffee shops, bars, and outdoor activities
- 💬 Detailed popups with notes, website links, and Google Maps directions
- ⭐ Favorite spots highlighted
- ✈️ Airport driving routes from Denver (US-285 & I-70/Leadville), Colorado Springs, and Gunnison
- 🥾 Bridge to Bridge Trail highlighted on the map (real GPS data)
- 📱 Fully responsive design

## Locations

The map includes downtown Buena Vista favorites and nearby attractions:
- **Food**: Wesley & Rose, Joyful Bakery, LoBäck's, Buena Viking, Simple Eatery, Crave BV, Terrace On Main, Buchi Cafe Cubano
- **Breakfast**: The Blend
- **Coffee & Drinks**: K's Dairy, Coyote Mezcalería, The Slammer, The Lariat, Eddyline Brewery
- **Lunch/Dinner out of town**: Outer Range Brewing Co. (Frisco)
- **Essentials**: Spark Provisions, Buena Vida Wine & Spirits, Parking
- **Outdoors**: Barbara Whipple Trailhead, Pickleball Courts, Surf Wave, Cottonwood Pass, Midland Tunnels
- **Wedding**: Ceremony location

## Deployment

This site is deployed on Netlify via GitHub.

### Netlify Deployment

1. Push to GitHub (already done!)
2. Go to [Netlify](https://www.netlify.com/)
3. Click "Add new site" → "Import an existing project"
4. Connect to GitHub and select `jhfish/wedding_map`
5. Netlify will auto-detect settings from `netlify.toml`
6. Click "Deploy"

## Local Development

```bash
# Start a local server
python3 -m http.server 8000

# Open in browser
open http://localhost:8000
```

## Technologies

- [Mapbox GL JS](https://www.mapbox.com/mapbox-gljs) - Interactive maps
- GeoJSON - Location data format
- Vanilla JavaScript - No frameworks needed
- HTML/CSS - Responsive design

## License

Personal use for wedding guests.
