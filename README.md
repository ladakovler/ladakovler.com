# Lada Kovler Music Portfolio

A Jekyll + Minimal Mistakes personal musician portfolio hosted on GitHub Pages.

## Tech Stack

- **Generator:** Jekyll 4
- **Theme:** Minimal Mistakes (remote theme)
- **Hosting:** GitHub Pages
- **Embeds:** Spotify, SoundCloud, YouTube
- **Contact Form:** Formspree
- **CSS:** Minimal Mistakes theme (no custom CSS needed)

## Local Development

### Prerequisites

- Ruby 2.7+
- Bundler

### Setup

```bash
git clone https://github.com/ladakovler/ladakovler.com.git
cd ladakovler.com
bundle install
bundle exec jekyll serve
```

Visit `http://localhost:4000` in your browser.

## Project Structure

```
_pages/         # Main pages (About, Music, Videos, Lessons, Gallery, Contact, News)
_posts/         # Blog posts (News/updates)
_data/          # Navigation configuration
assets/
  images/       # Profile photo, gallery images, etc.
_config.yml     # Site-wide configuration
Gemfile         # Ruby dependencies
```

## Getting Started

1. **Update `_config.yml`:**
   - Change `title`, `subtitle`, `description`, `url`
   - Add your email and social links
   - Update author name and bio

2. **Add Avatar:**
   - Add a photo to `assets/images/avatar.jpg`

3. **Customize Pages:**
   - Edit `_pages/*.md` files with your content
   - Replace `[Placeholders]` with real info

4. **Add Embeds:**
   - **Spotify:** Get your artist/track ID from a Spotify link
   - **SoundCloud:** Grab embed code from your profile
   - **YouTube:** Get video ID from the URL

5. **Set Up Contact Form:**
   - Go to [formspree.io](https://formspree.io)
   - Create a form and get your form ID
   - Replace `YOUR_FORM_ID` in `_pages/contact.md`

6. **Add Images:**
   - Optimize images and place in `assets/images/gallery/`
   - Reference in `_pages/gallery.md`

## Deployment

GitHub Pages automatically builds from the `main` branch.

1. Push changes to GitHub:
   ```bash
   git add .
   git commit -m "Update content"
   git push
   ```

2. Enable GitHub Pages:
   - Go to repository Settings → Pages
   - Source: `Deploy from a branch`
   - Branch: `main` / `root`

3. Your site will be live at `https://ladakovler.com` (or `https://ladakovler.github.io/ladakovler.com`)

## Optional: Custom Domain

1. Buy a domain (e.g., via GoDaddy, Namecheap, etc.)
2. Update DNS records to point to GitHub Pages
3. Add domain to repository Settings → Pages → Custom domain
4. Update `url` in `_config.yml`

## Tips for Best Performance

- **Images:** Optimize with TinyPNG, aim for <100KB per image
- **Audio/Video:** Embed from streaming platforms (Spotify, YouTube, SoundCloud)—don't host audio files on GitHub
- **Blog Posts:** Name files `YYYY-MM-DD-title.md` in `_posts/`
- **Minimal CSS:** The theme is already optimized; avoid custom styles

## Resources

- [Jekyll Docs](https://jekyllrb.com/docs/)
- [Minimal Mistakes Theme](https://mmistakes.github.io/minimal-mistakes/)
- [GitHub Pages](https://pages.github.com/)
- [Formspree Docs](https://formspree.io/docs/)

---

Built with ❤️ by [Copilot](https://github.com/features/copilot)
