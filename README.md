# Lada Kovler Music Portfolio

A professional musician portfolio website built with Jekyll and the Minimal Mistakes theme, hosted on GitHub Pages.

## Overview

- **Site:** https://ladakovler.com
- **Builder:** Jekyll 4 + Minimal Mistakes Theme
- **Hosting:** GitHub Pages (free, automatic deployment)
- **Performance:** Fast static site (<1 second load time)
- **Features:** Responsive design, dark theme, music embeds, contact form, image gallery

## Quick Start

### Prerequisites

- Ruby 2.7 or higher
- Bundler (`gem install bundler`)
- Git

### Local Development

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ladakovler/ladakovler.com.git
   cd ladakovler.com
   ```

2. **Install dependencies:**
   ```bash
   bundle install
   ```

3. **Run the development server:**
   ```bash
   bundle exec jekyll serve
   ```

4. **View locally:**
   Open `http://localhost:4000` in your browser

## Project Structure

```
_config.yml           # Site configuration
index.md              # Home page
_pages/               # Main pages (about, music, videos, lessons, gallery, contact, news)
_posts/               # Blog posts
_includes/            # Reusable components (video embed, contact form, gallery)
_data/                # Navigation and data files
assets/
  css/
    custom.scss       # Custom dark theme styles
  images/             # All images (hero, avatar, lessons, gallery, etc.)
Gemfile               # Ruby dependencies
CNAME                 # Custom domain
README.md             # This file
```

## File Manifest & Content Placeholders

### Configuration Files

| File | Purpose | Status |
|------|---------|--------|
| `_config.yml` | Site settings, author info, social links | ✅ Ready |
| `CNAME` | Custom domain | ✅ Set to `ladakovler.com` |
| `Gemfile` | Dependencies | ✅ Ready |
| `.gitignore` | Git ignore rules | ✅ Ready |

### Pages (All in `_pages/`)

| File | URL | Status | Content |
|------|-----|--------|----------|
| `about.md` | `/bio/` | ✅ Ready | Bio text, portrait image (avatar.jpg) |
| `music.md` | `/music/` | ✅ Ready | Spotify tracks, YouTube embed (Samba Do Avião) |
| `videos.md` | `/videos/` | ✅ Ready | 6 YouTube videos embedded |
| `lessons.md` | `/lessons/` | ✅ Ready | 3 lesson categories, 4 lesson images |
| `gallery.md` | `/gallery/` | ✅ Ready | 6 gallery photos, responsive grid |
| `contact.md` | `/contact/` | ✅ Ready | Contact info, Formspree form, Google Maps |
| `news.md` | `/news/` | ✅ Ready | Blog feed |

### Blog Posts

| File | Purpose | Status |
|------|---------|--------|
| `_posts/2024-07-16-welcome-to-my-music-portfolio.md` | Welcome announcement | ✅ Ready |

### Navigation

| File | Purpose | Status |
|------|---------|--------|
| `_data/navigation.yml` | Main navigation menu | ✅ Ready |

### Includes (Components)

| File | Purpose | Status |
|------|---------|--------|
| `_includes/responsive-video.html` | YouTube video embed | ✅ Ready |
| `_includes/gallery-grid.html` | Gallery grid layout | ✅ Ready |
| `_includes/contact-form.html` | Formspree contact form | ✅ Ready |

### Styles

| File | Purpose | Status |
|------|---------|--------|
| `assets/css/custom.scss` | Custom dark theme (black bg, white text) | ✅ Ready |

## Image Assets Required

All images should be placed in `assets/images/`:

| Image Path | Recommended Size | Format | Status |
|------------|------------------|--------|--------|
| `hero.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |
| `avatar.jpg` | 400×400px | JPG | ⚠️ Placeholder needed |
| `lessons-01.jpg` | 600×400px | JPG | ⚠️ Placeholder needed |
| `lessons-02.jpg` | 600×400px | JPG | ⚠️ Placeholder needed |
| `lessons-03.jpg` | 600×400px | JPG | ⚠️ Placeholder needed |
| `lessons-04.jpg` | 600×400px | JPG | ⚠️ Placeholder needed |
| `gallery/gallery-01.jpg` | 1200×800px | JPG | ⚠️ Placeholder needed |
| `gallery/gallery-02.jpg` | 1200×800px | JPG | ⚠️ Placeholder needed |
| `gallery/gallery-03.jpg` | 1200×800px | JPG | ⚠️ Placeholder needed |
| `gallery/gallery-04.jpg` | 1200×800px | JPG | ⚠️ Placeholder needed |
| `gallery/gallery-05.jpg` | 1200×800px | JPG | ⚠️ Placeholder needed |
| `gallery/gallery-06.jpg` | 1200×800px | JPG | ⚠️ Placeholder needed |
| `bio-header.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |
| `music-header.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |
| `videos-header.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |
| `lessons-header.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |
| `gallery-header.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |
| `contact-header.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |
| `news-header.jpg` | 1600×600px | JPG | ⚠️ Placeholder needed |

## Embedded Content

### Music (Spotify Tracks)
✅ **Embedded in `_pages/music.md`:**
- Waiting for My Miracle: https://open.spotify.com/track/7IZHrG6dNhXYVmyclWQKS3
- Nabludai: https://open.spotify.com/track/2BNeoV5zfUOSWV0Q1GGNCY
- Ravno: https://open.spotify.com/track/6G2ml2m32B29VEhXrcbkFU
- Samba Do Avião (YouTube): https://youtu.be/_ZbcywLttlA

### Videos (YouTube Embeds)
✅ **Embedded in `_pages/videos.md`:**
- JMRJOxy8_6M
- H3295ZtPGbs
- IhC1qB4Kxj4
- KWVe8Z85zq8
- 3XvryV0zQMU
- ZcuLZYakbr8

### Contact Form
✅ **Embedded in `_pages/contact.md`:**
- Formspree: https://formspree.io/f/mzdnvaan

### Google Maps
✅ **Embedded in `_pages/contact.md`:**
- Miami Beach, 41st St area

## Deployment

### Deploy to GitHub Pages

1. **Verify all content is ready** (images, text, embeds)
2. **Commit changes:**
   ```bash
   git add .
   git commit -m "Complete portfolio site setup"
   ```
3. **Push to GitHub:**
   ```bash
   git push origin main
   ```
4. **GitHub Pages builds automatically** (1-2 minutes)
5. **View live site:** https://ladakovler.com

### Enable GitHub Pages

If not already enabled:
1. Go to repository **Settings → Pages**
2. Set Source to "Deploy from a branch"
3. Select Branch: `main` / Folder: `/ (root)`
4. Save

## Image Optimization Guide

### Before Upload

Optimize all images for web performance:

**Option 1: Online Tools**
- [TinyPNG](https://tinypng.com) — Automatic compression
- [ImageOptim](https://imageoptim.com) — macOS tool

**Option 2: Command Line (ImageMagick)**
```bash
# Install ImageMagick
brew install imagemagick

# Resize and compress
convert input.jpg -resize 1600x600 -quality 85 output.jpg
```

### Image Guidelines

| Image Type | Dimensions | Max Size | Quality |
|------------|------------|----------|----------|
| Hero/Headers | 1600×600px | 150KB | 85% quality |
| Avatar/Portrait | 400×400px | 80KB | 85% quality |
| Lesson Cards | 600×400px | 100KB | 85% quality |
| Gallery | 1200×800px | 120KB | 85% quality |

## Customization

### Update Site Colors

Edit `assets/css/custom.scss`:

```scss
// Dark theme colors
$background-color: #000000;
$text-color: #ffffff;
$primary-color: #e74c3c;      // Red accent
$accent-color: #3498db;       // Blue accent
```

### Update Social Links

Edit `_config.yml` author section:

```yaml
author:
  links:
    - label: "Instagram"
      url: "https://www.instagram.com/lada_kovler"
    # Add more as needed
```

### Update Contact Information

Edit `_pages/contact.md`:

```markdown
📧 Email: kovler20@gmail.com
📱 Phone: 646-884-0064
📍 Location: Miami Beach, FL
```

## Content Checklist

### Before Publishing

- [ ] All header images added (hero.jpg, bio-header.jpg, etc.)
- [ ] Avatar photo added (avatar.jpg)
- [ ] All 4 lesson images added (lessons-01.jpg - 04.jpg)
- [ ] All 6 gallery images added (gallery/gallery-01.jpg - 06.jpg)
- [ ] Bio page reviewed and personalized
- [ ] Music embeds verified (Spotify links working)
- [ ] Videos playing correctly
- [ ] Contact form tested (Formspree working)
- [ ] Google Maps location verified
- [ ] Social media links updated
- [ ] Phone and email verified

## Troubleshooting

### Site not deploying?
1. Check **Actions** tab for build errors
2. Verify `_config.yml` YAML syntax (use [YAML Linter](https://www.yamllint.com/))
3. Check file names for typos
4. Ensure GitHub Pages is enabled

### Images not showing?
1. Verify file paths match exactly: `assets/images/filename.jpg`
2. Check file exists in repository
3. Clear browser cache (Ctrl+Shift+Del)
4. Wait 5 minutes for GitHub Pages to rebuild

### Embeds not working?
1. Verify YouTube video IDs are correct
2. Check Spotify track URLs are valid
3. Test Formspree form at https://formspree.io
4. Verify Google Maps iframe code

### Local server won't start?
```bash
# Clear cache
rm -rf .jekyll-cache _site

# Update gems
bundle update

# Try again
bundle exec jekyll serve
```

## Resources

- [Jekyll Documentation](https://jekyllrb.com/docs/)
- [Minimal Mistakes Theme](https://mmistakes.github.io/minimal-mistakes/)
- [GitHub Pages Help](https://docs.github.com/en/pages)
- [Markdown Guide](https://www.markdownguide.org/)
- [Formspree Docs](https://formspree.io/docs)

## Support

For questions or issues:
1. Review the troubleshooting section above
2. Check Jekyll and theme documentation
3. Search [GitHub Issues](https://github.com/mmistakes/minimal-mistakes/issues)
4. Post on [Jekyll Talk](https://talk.jekyllrb.com/)

---

**Status:** Ready for review and image uploads ✅

**Last Updated:** July 16, 2024

**Next Steps:**
1. Upload hero, avatar, and gallery images
2. Review all page content
3. Test locally with `bundle exec jekyll serve`
4. Push to GitHub when ready
