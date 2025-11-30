# Sri Lanka Flood Relief - Crisis Map

Real-time interactive map showing flood relief requests and volunteer contributions across Sri Lanka.

## Features
- 🗺️ Live crisis map with color-coded urgency markers
- 📊 Real-time statistics dashboard
- 🔍 Advanced filtering (urgency, location, establishment type)
- 📱 Mobile-responsive design
- 🔄 Auto-refresh every 2 minutes

## Deploy to Vercel

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https://github.com/yourusername/flood-relief-map)

### Quick Deploy Steps:

1. **Install Vercel CLI** (if not already installed):
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**:
   ```bash
   vercel login
   ```

3. **Deploy from this directory**:
   ```bash
   vercel
   ```

4. **Follow the prompts**:
   - Link to existing project? → No
   - Project name → flood-relief-map (or your choice)
   - Directory → ./
   - Override settings? → No

5. **Your site will be live!** Vercel will give you a URL like:
   `https://flood-relief-map.vercel.app`

### Alternative: Deploy via Vercel Dashboard

1. Go to [vercel.com](https://vercel.com) and sign up/login
2. Click "Add New" → "Project"
3. Import this folder or create a GitHub repo and import from there
4. Click "Deploy" - that's it!

## Local Development

```bash
python -m http.server 8000
```

Then visit: `http://localhost:8000`

## API Data Source

Data is fetched from: [FloodSupport.org Public API](https://aid.floodsupport.org/api-docs)

## License

MIT - Free to use for humanitarian purposes
