# Timewize Landing Page

Landing page for Timewize - Time tracking software for freelancers and consultants.

## 🚀 Live Site
- Production: https://timewize.io

## 📁 Structure

```
timewize-website/
├── public_html/          # Production-ready files
│   ├── index.html        # Main landing page (SEO optimized)
│   ├── sitemap.xml       # Search engine sitemap
│   ├── robots.txt        # Search engine directives
│   └── assets/           # Images, CSS, JS
└── README.md
```

## 🎯 SEO Features

- ✅ Pain-focused page title: "Stop Losing $15k/Year on Unbilled Hours"
- ✅ Google Analytics tracking (G-F3JCHQ47NZ)
- ✅ Open Graph tags (Facebook/LinkedIn)
- ✅ Twitter Card tags
- ✅ Schema.org structured data
- ✅ Optimized meta description
- ✅ Sitemap for search engines

## 📊 Analytics

**Google Analytics:** G-F3JCHQ47NZ
- Dashboard: https://analytics.google.com

## 🚀 Deployment

Files in `/public_html/` are production-ready.

To deploy:
```bash
# Upload public_html contents to your web server
rsync -avz public_html/ user@server:/var/www/timewize.io/
```

## 📝 Recent Changes

- **2024-12-30:** SEO optimization deployed
  - Updated page title and meta tags
  - Added Google Analytics
  - Created sitemap.xml
  - Updated robots.txt

## 🎨 TODO

- [ ] Create social share images (og-image.jpg, twitter-card.jpg)
- [ ] Submit to Google Search Console
- [ ] Update React app content
- [ ] Test social share cards

## 📚 Documentation

See `/ai-workspace/` for:
- `TIMEWIZE_SEO_ACTION_PLAN.md` - Complete SEO strategy
- `SOCIAL_SHARE_IMAGES_GUIDE.md` - Image creation guide
- `DEPLOYMENT_COMPLETE.md` - Deployment summary
