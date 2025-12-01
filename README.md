# Sri Lanka Flood Relief - Crisis Map

Real-time interactive map showing flood relief requests and volunteer contributions across Sri Lanka.

## Features
- 🗺️ Live crisis map with color-coded urgency markers
- 📊 Real-time statistics dashboard
- 🔍 Advanced filtering (urgency, location, establishment type)
- 📱 Mobile-responsive design
- 🔄 Auto-refresh every 2 minutes

## Map Legend
- 🔴 **Emergency** - Immediate action needed
- 🟠 **High Urgency**
- 🟡 **Medium Urgency**
- 🟢 **Low Urgency**
- 🔵 **Available Contribution**

## Local Development

```bash
python -m http.server 8000
```

Then visit: `http://localhost:8000`

## API Data Source

Data is fetched from: [FloodSupport.org Public API](https://aid.floodsupport.org/api-docs)

## License

MIT - Free to use for humanitarian purposes
