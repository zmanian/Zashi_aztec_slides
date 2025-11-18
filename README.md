# Zashi - End User Zcash Wallet Presentation

A comprehensive reveal.js slide deck covering Zashi wallet usage and Zcash privacy features, enhanced with detailed speaker notes and technical accuracy.

## 📋 Contents

### 1. Getting Started
- **Address Types**: T-addresses (transparent, 35 chars) vs U-addresses (unified, 141-213 chars)
- Understanding Orchard, Sapling, and transparent pools
- Auto-shielding after 10 confirmations
- **Viewing Keys**: IVK vs FVK, introduced via ZIP 310 (Sapling 2018)
- Compliance without backdoors

### 2. Using Zashi
- **NEAR Intents Integration**: $3B monthly volume, $5.3B all-time, 1000+ assets
- **Zashi Swap Deposit**: No-KYC on-ramp (0.2-0.5% fees), $6.4M daily via Zashi
- **CrossPay**: Pay anyone in any cryptocurrency from shielded ZEC
- **Flexa Integration**: Spend at thousands of retail locations (1-2% fees)
- Traditional CEX vs decentralized swaps comparison

### 3. Advanced Topics
- **Lightwalletd**: 90%+ bandwidth savings vs full node
- RPC server selection (self-hosted, trusted community, public)
- Network-layer privacy: CVE-2019-16930 and IP metadata risks
- **Arti**: Native Rust Tor implementation ($670K Zcash Community Grant)
- Complete privacy stack: Cryptographic + Compliance + Network + Infrastructure layers

## 🚀 How to View

### Option 1: Open Locally
Simply open `index.html` in your web browser:
```bash
open index.html
# or
firefox index.html
# or
google-chrome index.html
```

### Option 2: Serve with Local Server
For best results, serve with a local HTTP server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Then visit: http://localhost:8000
```

**Using Node.js:**
```bash
npx http-server
```

**Using PHP:**
```bash
php -S localhost:8000
```

## 🎮 Controls

- **Arrow Keys** / **Space**: Navigate slides
- **F**: Fullscreen mode
- **S**: Speaker notes view (detailed notes for each slide!)
- **O** / **Esc**: Overview mode
- **B** / **.**: Blackout mode

## ✨ Enhanced Features

### Speaker Notes
Every slide includes comprehensive speaker notes with:
- Technical details and context
- Real-world use cases and examples
- Key statistics and data points
- Implementation guidance
- Privacy considerations

Press **S** during the presentation to view speaker notes in a separate window.

### Technical Accuracy
- ZIP 310 references for viewing keys
- CVE-2019-16930 vulnerability context
- Accurate fee comparisons (0.2-0.5% for NEAR Intents swaps)
- Real market data (ZEC: ↑560% in 30 days, ↑980% YoY)
- Lightwalletd bandwidth statistics (90%+ savings)

### Visual Enhancements
- Zcash brand colors (#f4b728 yellow, #231f20 black)
- Statistical highlight boxes
- Technical detail badges
- Comprehensive comparison tables
- Professional gradient backgrounds

## 🎨 Features

- Responsive design
- Dark theme optimized for presentations
- Clear visual hierarchy
- Code examples for RPC testing
- Quick reference slide
- Resource links

## 📱 Mobile Friendly

The presentation works on mobile devices - just swipe to navigate!

## 🔗 Reveal.js

This presentation uses [reveal.js](https://revealjs.com/) - a powerful HTML presentation framework.

## 📝 Customization

To customize the presentation:

1. Edit `index.html`
2. Modify the `<style>` section for custom styling
3. Add/remove slides by editing `<section>` elements
4. Change theme by modifying the theme CSS link

## 🌐 Deployment

To deploy online:

- **GitHub Pages**: Push to GitHub and enable Pages
- **Netlify**: Drag and drop the file
- **Vercel**: Deploy with `vercel --prod`

## 📊 Key Statistics Covered

- **$5.3B**: NEAR Intents all-time volume
- **$3B**: NEAR Intents monthly swap volume (30-day)
- **$6.4M**: Daily Zashi volume via NEAR Intents
- **1000+**: Cryptocurrencies supported in swaps
- **0.2-0.5%**: CrossPay swap fees
- **90%+**: Bandwidth savings via lightwalletd
- **$670K**: Zcash Community Grant funding for Arti (Rust Tor)
- **10 confirmations**: Auto-shielding threshold in Zashi
- **$526M**: Daily ZEC volume on Binance

## 🎯 Presentation Highlights

### Compelling One-Liners
- "Privacy requires both cryptographic shielding AND network obfuscation"
- "Zashi completes Zcash's privacy promise with defense-in-depth architecture"
- "CrossPay breaks the surveillance chain—recipient has no link to your wallet"
- "Think of u-addresses as a universal travel adapter for cryptocurrency"
- "Viewing keys bridge privacy and compliance without backdoors"

### Technical Terms Explained
- **T-addresses**: Transparent (like Bitcoin), 35 characters
- **U-addresses**: Unified (bundles Orchard + Sapling + transparent), 141-213 characters
- **Lightwalletd**: Bandwidth-efficient RPC service (90%+ savings)
- **Arti**: Pure Rust Tor implementation for mobile
- **ZIP 310**: Zcash Improvement Proposal introducing viewing keys

## 📄 License

Feel free to use and modify for your presentations! Based on Claude research and Zcash/ECC official documentation.
