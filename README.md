# M5Dex Elite Marketing Suite

A professional web3 marketing template generator with 200+ customizable presets for DeFi protocols, bridges, and blockchain projects.

## Features

✨ **200+ Professional Templates** - DeFi, Cross-Chain, Technical, Growth, Roadmap, Tokenomics & Security categories
🎨 **Elite Design System** - Gold & matte black luxury aesthetic with advanced animations
🤖 **AI-Powered Copy** - Generate headlines using Google Gemini API
📊 **Data Visualizations** - Bar charts, metrics, roadmaps, and flow diagrams
💾 **4K Export** - Download high-resolution marketing assets as PNG
🔍 **Smart Search** - Filter by category and keyword across all templates

## Tech Stack

- **Frontend**: HTML5, CSS3, Tailwind CSS
- **JavaScript**: Vanilla JS (no dependencies)
- **Export**: html2canvas for 4K rendering
- **AI**: Google Gemini API (2.5 Flash model)
- **Hosting**: Vercel

## Getting Started

### Prerequisites

- Node.js 16+
- GitHub account
- Vercel account (free)
- Google Gemini API key (optional, for AI features)

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/shriyashsoni/m5dex.git
   cd m5dex
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Setup environment variables**
   ```bash
   cp .env.local.example .env.local
   # Edit .env.local and add your Google Gemini API key
   ```

4. **Run locally**
   ```bash
   npm run dev
   # Or open index.html directly in your browser
   ```

### Deploy to Vercel

#### Option 1: Using Vercel CLI

```bash
npm install -g vercel
vercel login
vercel
```

#### Option 2: Using GitHub Integration (Recommended)

1. Go to [vercel.com](https://vercel.com)
2. Sign in with GitHub
3. Click "Add New..." → "Project"
4. Select the `shriyashsoni/m5dex` repository
5. Configure environment variables:
   - Add `VITE_GEMINI_API_KEY` with your API key
6. Click "Deploy"

**Your site will be live at:** `https://m5dex.vercel.app`

## Configuration

### API Key Setup

1. Get a free API key from [Google AI Studio](https://ai.google.dev)
2. Add to Vercel environment variables:
   - Go to Project Settings → Environment Variables
   - Add key: `VITE_GEMINI_API_KEY`
   - Add your API key as the value

### Customization

Edit `index.html` to:
- Modify the template library (lines 86-210)
- Update brand colors in CSS variables (lines 11-16)
- Add new template categories
- Customize animations and styling

## Usage

### Selecting Templates
- Browse all 200+ templates in the grid
- Filter by category (DeFi, Cross-Chain, Technical, etc.)
- Search by keyword

### Customizing Copy
1. Select a template
2. Enter a topic in the AI input (e.g., "Bridge rewards", "Audit completion")
3. Click "AI Remix ✨" to generate new copy
4. Edit manually if needed

### Exporting
- Click "Export 4K High-Res" to download as PNG
- Images render at 4K quality for high-resolution print/social

## Template Categories

- **DeFi Protocol** - Liquidity, Yield, Aggregation
- **Cross-Chain** - Connectivity, Wormhole Integration
- **Technical** - Throughput, Stack, Performance
- **Growth** - Volume Milestones, Metrics
- **Roadmap** - Timeline, Phases
- **Tokenomics** - Token distribution, economy
- **Security** - Audits, Safety features

## File Structure

```
m5dex/
├── index.html              # Main application
├── package.json            # Project metadata
├── vercel.json            # Vercel configuration
├── .env.local.example     # Environment variables template
├── .gitignore             # Git ignore rules
└── README.md              # This file
```

## API Reference

### Google Gemini API
- **Endpoint**: `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent`
- **Request Format**: JSON with topic and system instructions
- **Response Format**: JSON with generated headline and subheadline
- **Rate Limits**: Check [Google AI documentation](https://ai.google.dev/docs/rate-limits)

## Troubleshooting

### "API Offline" Error
- Check your API key is valid
- Verify VITE_GEMINI_API_KEY environment variable is set
- Check API quota hasn't been exceeded

### Export/Download Issues
- Clear browser cache
- Use Chrome/Firefox (best compatibility)
- Check browser console for errors (F12)

### Template Grid Not Loading
- Ensure JavaScript is enabled
- Check browser console for errors
- Try clearing localStorage

## Performance Tips

- Templates load instantly (client-side only)
- AI generation takes 2-5 seconds
- 4K export rendering takes 10-30 seconds
- Optimize images before uploading to social media

## Contributing

Found a bug? Want to add templates?
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit changes (`git commit -m 'Add amazing feature'`)
4. Push to branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see LICENSE file for details.

## Support

For issues and questions:
- GitHub Issues: [m5dex/issues](https://github.com/shriyashsoni/m5dex/issues)
- Email: support@m5dex.com

## Roadmap

- [ ] Save/bookmark favorite templates
- [ ] Multi-language support
- [ ] Premium template packs
- [ ] Team collaboration features
- [ ] Advanced analytics
- [ ] Mobile app

---

**Made with ✨ for Web3 Marketing Excellence**