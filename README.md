# OmniLLM - Free AI Model Directory

Two stunning designs for a curated directory of completely free LLM models and API providers.

🌐 **Live Site**: https://leonmurrayaust.github.io/oceanrouter

## ✨ Two Design Options

### Design 1: Dark Glassmorphism (Default - index.html)
**Neon cyberpunk aesthetic with floating orbs**
- Animated gradient background with floating orbs
- Glass morphism cards with neon accents
- Hover glow effects and smooth transitions
- Modern Space Grotesk & Inter typography
- Best for: Tech-forward, modern feel

**Features:**
- 🔮 Animated gradient background
- 💫 Glass morphism UI elements
- 🎨 Neon blue/purple/pink accents
- ⚡ Smooth hover animations
- 📊 Live visitor counter
- 🔗 Short URL sharing (omnillm.ai)
- 🎯 Integrated ad spaces

### Design 2: Minimalist Editorial (design2.html)
**Clean, editorial aesthetic with warm tones**
- Cream & charcoal color palette
- Elegant serif headings (Playfair Display)
- Clean list-based model display
- Refined, magazine-like layout
- Best for: Professional, sophisticated feel

**Features:**
- 📖 Editorial typography
- 🎨 Warm cream & charcoal palette
- ✦ Subtle accent details
- 📋 List-view model display
- 🏷️ Clean card layouts

## 🚀 Switch Between Designs

To use Design 2 instead:
1. Rename `index.html` to `design1.html`
2. Rename `design2.html` to `index.html`
3. Commit and push

## ✨ New Features

### Visitor Counter
- Real-time visitor count display
- Animated "live" indicator
- Persists in localStorage

### Short URL System
- Easy-to-share: **omnillm.ai**
- One-click copy functionality
- Toast notifications on copy
- Redirect page included (`redirect.html`)

### Ad Integration
- Two strategically placed ad spaces
- Non-intrusive design
- Hover effects for engagement
- Easy to customize content

## 📁 Files

```
├── index.html          # Design 1: Dark Glassmorphism (default)
├── design1.html        # Design 1: Dark Glassmorphism (backup)
├── design2.html        # Design 2: Minimalist Editorial
├── redirect.html       # Short URL redirect page
└── README.md          # This file
```

## 🎨 Customization

### Colors (Design 1)
Edit CSS variables in `index.html`:
```css
:root {
    --neon-blue: #00d4ff;
    --neon-purple: #b829dd;
    --neon-pink: #ff006e;
}
```

### Colors (Design 2)
Edit CSS variables in `design2.html`:
```css
:root {
    --cream: #faf9f7;
    --charcoal: #1a1a1a;
    --accent: #2563eb;
}
```

### Ad Content
Replace ad content in the HTML:
```html
<div class="ad-content">
    Your Advertisement Here
</div>
```

## 📱 Models & Providers

### 12 Free Models
1. **Google Gemini 2.0 Flash** - 1,500 req/day
2. **Meta Llama 3.1 70B** - Rate limited free
3. **DeepSeek V3** - 50 req/day
4. **Meta Llama 3.1 8B** - Generous limits
5. **Qwen 2.5 72B** - Free tier
6. **NVIDIA Nemotron 70B** - Free via OpenRouter
7. **Mistral Small** - Free tier (experimental)
8. **Perplexity Sonar** - $5/month free
9. **Zephyr ORPO 141B** - Serverless free
10. **Gemma 2 27B** - Completely free
11. **Microsoft Phi-4** - Free playground
12. **Yi Large** - Free tier

### 12 Free API Providers
- **Google AI Studio** - 1,500 req/day
- **OpenRouter** - $0.05/day (never expires)
- **Groq** - Generous free tier
- **Together AI** - $5 free credit
- **Hugging Face** - Serverless free
- **Perplexity** - $5/month free
- **Mistral AI** - Free tier
- **DeepSeek** - 50 req/day
- **Novita AI** - Free GPU hours
- **Fireworks** - $1 free credit
- **DeepInfra** - Free tier
- **Replicate** - $5 free credit

## 🔧 Deployment

### GitHub Pages (Recommended)
1. Push code to GitHub repository
2. Go to Settings → Pages
3. Source: Deploy from a branch
4. Branch: main / (root)
5. Wait 2-3 minutes
6. Visit: `https://[username].github.io/[repo]`

### Custom Domain (Short URL)
To use `omnillm.ai` or similar:
1. Buy domain from Namecheap/Cloudflare
2. Create CNAME record pointing to `leonmurrayaust.github.io`
3. Add domain in GitHub Pages settings
4. Upload `redirect.html` to your domain root for instant redirect

### Netlify / Vercel
1. Connect your GitHub repo
2. Deploy automatically on push
3. Custom domain supported

## 🔒 Security

- API keys stored locally in browser (localStorage)
- Never sent to any third-party servers
- Direct connection to chosen provider only

## 📄 License

MIT - Use, modify, share freely!

---

**Made with 💙 for the AI community**