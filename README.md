# Wedding Map - Buena Vista Guide

An interactive map showcasing favorite spots in Buena Vista, Colorado for wedding guests.

## Features

- 🗺️ Interactive Mapbox map with custom emoji markers
- 📍 19 curated locations including restaurants, coffee shops, bars, and outdoor activities
- 🎨 Color-coded categories (Food, Coffee, Drinks, Essentials, Hiking, etc.)
- 💬 Detailed popups with notes, website links, and Google Maps directions
- ⭐ Favorite spots highlighted
- 📱 Fully responsive design

## Locations

The map includes downtown Buena Vista favorites and nearby attractions:
- **Food & Coffee**: Wesley & Rose, Joyful Bakery, LoBäck's, Buena Viking, K's Dairy, Eddyline Brewery
- **Drinks**: Coyote Mezcalería, The Slammer, The Lariat
- **Essentials**: Spark Provisions, Buena Vida Wine & Spirits
- **Outdoors**: Barbara Whipple Trailhead, Pickleball Courts, Surf Wave
- **Scenic**: Midland Tunnels, Cottonwood Pass
- **Wedding**: Ceremony location

## Deployment

This site is ready to deploy on:
- **Netlify**: Connect your GitHub repo and deploy
- **Vercel**: Import from GitHub
- **GitHub Pages**: Enable in repository settings

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
