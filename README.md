# Pratishtha Digital Solutions — Website

Premium single-page website for **Pratishtha Digital Solutions** with full SEO + LLM/AI discoverability.

## Files to upload (same folder on hosting / public root)

| File | Purpose |
|------|---------|
| `index.html` | Main website (SEO + schema + multilingual) |
| `logo.png` | Brand logo (transparent background) |
| `founder.jpeg` | Founder photo |
| `favicon.png` | App / high-res icon |
| `favicon-32.png` | Browser favicon |
| `robots.txt` | Crawl rules + AI bot allow list |
| `sitemap.xml` | Google / Bing sitemap |
| `llms.txt` | Short AI-readable business summary |
| `llms-full.txt` | Full AI/LLM business profile |
| `ai.txt` | AI crawler preference hints |

## How to go live on pratishthadigital.com

1. Log in to your domain hosting / cPanel / Netlify / GitHub Pages / Hostinger etc.
2. Upload **all files above into the public root** (usually `public_html` or `www`).
3. Confirm these URLs work after deploy:
   - https://pratishthadigital.com/
   - https://pratishthadigital.com/robots.txt
   - https://pratishthadigital.com/sitemap.xml
   - https://pratishthadigital.com/llms.txt
4. In [Google Search Console](https://search.google.com/search-console): add property → submit `sitemap.xml`.
5. Hard-refresh the site (`Ctrl+F5`). Test WhatsApp, forms, EN/हिंदी/मराठी.

## SEO status (what is in the code)

### Already strong
- Title + meta description (service + India/Maharashtra intent)
- Expanded `keywords` meta (supplemental only — Google mostly ignores this; real ranking comes from content)
- Canonical URL, robots, hreflang (en/hi/mr)
- Open Graph + Twitter cards
- JSON-LD `@graph`: Organization, LocalBusiness/ProfessionalService, WebSite, WebPage, Person (founder), FAQPage, BreadcrumbList
- Visible keyword-rich footer SEO block
- Semantic sections, FAQ, service headings, founder entity
- Image alts with brand/person names

### LLM / AI search optimization
- `llms.txt` + `llms-full.txt` (standard pattern for AI assistants)
- `ai.txt` + robots allow for major AI crawlers
- Entity-rich schema (`knowsAbout`, `sameAs`, contact points, offer catalog)
- Speakable hints on hero/about/services
- Clear facts so ChatGPT / Perplexity / Gemini can cite accurate business info

### Important truth about keywords
The old `meta name="keywords"` list alone does **not** rank a site. What matters:
1. On-page content matching search intent (services, city, problems)
2. Structured data (schema)
3. Google Business Profile + reviews + citations
4. Page speed, mobile UX, internal links
5. Backlinks and real brand mentions

## Local preview

```bash
cd pratishtha-website
python3 -m http.server 8080
```

Visit `http://localhost:8080`.

## Brand

- Colors: Dark navy, orange–gold gradient, white  
- Tagline: **Building Reputation. Creating Impact.**  
- Business WhatsApp: +91 94202 50546  
- Founder: +91 70584 84880  
- Email: pratishthadigitalofficial@gmail.com  
