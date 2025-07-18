# HomesickAussie.com - GitHub Pages Site

A community platform for Australian expats worldwide, featuring market-specific advertorials that drive traffic to Chooki's Chicken Salt store.

## Project Structure

```
homesick-aussie-site/
├── index.html              # Homepage - community hub
├── usa/index.html          # US market advertorial
├── uk/index.html           # UK market advertorial  
├── canada/index.html       # Canada market advertorial
├── europe/index.html       # Europe market advertorial
├── newzealand/index.html   # New Zealand market advertorial
├── asia/index.html         # Asia-Pacific market advertorial
├── assets/
│   ├── css/style.css       # Main stylesheet
│   ├── images/             # Image assets
│   └── js/                 # JavaScript files
├── CNAME                   # Custom domain configuration
└── README.md               # This file
```

## Deployment Setup

### 1. GitHub Repository Setup

1. Create new repository called `homesick-aussie-site` on GitHub
2. Push this code to the repository
3. Go to Settings > Pages
4. Source: "Deploy from a branch"
5. Branch: `main` / `master`
6. Folder: `/ (root)`

### 2. Custom Domain Configuration

1. In your DNS provider, create these records for `homesickaussie.com`:
   ```
   Type: A
   Name: @
   Value: 185.199.108.153
   
   Type: A  
   Name: @
   Value: 185.199.109.153
   
   Type: A
   Name: @
   Value: 185.199.110.153
   
   Type: A
   Name: @
   Value: 185.199.111.153
   
       Type: CNAME
    Name: www
    Value: chookiman.github.io
   ```

2. In GitHub Pages settings, add custom domain: `homesickaussie.com`
3. Enable "Enforce HTTPS"

### 3. Traffic Flow

- **Facebook Ads** → Target homesick Aussie expats
- **HomesickAussie.com/[market]** → Editorial-style advertorials  
- **Chooki's Shopify Store** → Product purchase & fulfillment

### 4. Content Strategy

Each market page features:
- Authentic first-person expat stories
- Market-specific cultural pain points
- Emotional journey from disappointment to discovery
- Community recommendation feel (not direct advertising)
- Clear CTAs to Chooki's Shopify store

### 5. Brand Positioning

- **HomesickAussie** = Independent community platform
- **Chooki's** = Premium product brand
- Connection feels like genuine mate-to-mate recommendation

## Markets & Targeting

| Market | URL Path | Currency | Target Cities |
|--------|----------|----------|---------------|
| USA | `/usa/` | USD | NYC, LA, SF, Chicago, Boston |
| UK | `/uk/` | GBP | London, Manchester, Edinburgh |
| Canada | `/canada/` | CAD | Toronto, Vancouver, Montreal |
| Europe | `/europe/` | EUR | Amsterdam, Berlin, Dublin |
| New Zealand | `/newzealand/` | NZD | Auckland, Wellington |
| Asia | `/asia/` | USD | Seoul, Tokyo, Singapore |

## Development Notes

- Built with semantic HTML5 and vanilla CSS
- Mobile-responsive design
- Editorial styling (not e-commerce)
- Fast loading times for conversion optimization
- SEO optimized with proper meta tags
- Facebook Pixel and analytics ready

## Next Steps

1. Complete full advertorial content for each market
2. Add hero images for each story
3. Set up Facebook Pixel tracking
4. Configure Google Analytics
5. Test conversion funnel from Facebook → GitHub → Shopify

---

**Status:** Repository structure complete, ready for GitHub Pages deployment
**Domain:** homesickaussie.com (pending DNS configuration)
**Last Updated:** December 2024 