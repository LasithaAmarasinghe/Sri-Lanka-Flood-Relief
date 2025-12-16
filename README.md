# Sri Lanka Flood Relief - Crisis Map

Real-time interactive map showing flood relief requests and volunteer contributions across Sri Lanka.

<p align="center">
  <img src="https://github.com/LasithaAmarasinghe/Sri-Lanka-Flood-Relief/blob/main/flood.gif" alt="Demo GIF" />
</p>

## Features
 🗺️ Live crisis map with color-coded urgency markers <br>
 📊 Real-time statistics dashboard <br>
 🔍 Advanced filtering (urgency, location, establishment type) <br>
 📱 Mobile-responsive design <br>
 🔄 Auto-refresh every 2 minutes <br>

## Map Legend
 🔴 **Emergency** - Immediate action needed <br>
 🟠 **High Urgency** <br>
 🟡 **Medium Urgency** <br>
 🟢 **Low Urgency** <br>
 🔵 **Available Contribution** <br>
 

## Local Development

```bash
python -m http.server 8000
```

Then visit: `http://localhost:8000`

## API Data Source

Data is fetched from: [FloodSupport.org Public API](https://aid.floodsupport.org/api-docs)

## License

MIT - Free to use for humanitarian purposes
