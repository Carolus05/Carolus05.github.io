# Your Photography Landing Page

## 1. Add your photos
Drop your compressed JPGs into the `images/` folder.

**Hero carousel:** the carousel shows a different crop depending on whether the site is opened on a computer or a phone, so name your photos in pairs:
- `hero-1.jpg`, `hero-2.jpg`, `hero-3.jpg`, `hero-4.jpg` — shown on computers/tablets. Landscape crops work best here (roughly 16:9 or 3:2).
- `hero-1-mobile.jpg`, `hero-2-mobile.jpg`, `hero-3-mobile.jpg`, `hero-4-mobile.jpg` — shown on phones. A taller, tighter crop of the same photo works best here (roughly 4:5 or 3:4), so the subject isn't cut off on a narrow screen.

You can absolutely reuse the same photo for both — just crop it differently, or even use the exact same file for both if you don't want to bother making two crops yet. The filenames just need to exist. This is set up in the `heroPhotosDesktop` / `heroPhotosMobile` lists near the top of the `<script>` section in `index.html`, if you want to rename things later.

**Portfolio link button:** the "A few favorites" grid has been replaced with a single button linking out to a separate site where your full portfolio lives. In `index.html`, search for `portfolio-btn` and update `href="https://your-portfolio-site.com"` with the real URL of that site.

**About section:** `portrait.jpg` — a photo of you.

## 2. Personalize the text
Open `index.html` and replace:
- `Your Name` in the footer and About section (the header/hero now just shows `photosbycarlo`, edit the `.logo` text directly in `index.html` if you want to change your account name)
- The About section bio paragraph — including `[your city/region]`
- `@yourhandle` and the Instagram link URL in the footer

## 3. Add your real contact info
In the Contact section of `index.html` (search for `contact-links`), update:
- The Instagram card: `href="https://instagram.com/photosbycarlo"` and the `@photosbycarlo` text
- The phone card: `href="tel:+10000000000"` (use your real number, digits only after `+`) and the displayed `(000) 000-0000` text

Both cards are tap-to-open on phones — Instagram opens the app/profile, and the phone number opens the dialer.

## 4. Preview locally
Just open `index.html` in your browser — no build step needed.

## 5. Deploy to GitHub Pages
1. Create a repo named `yourusername.github.io` on GitHub.
2. Copy `index.html`, `style.css`, and the `images/` folder into it.
3. Push/upload the files.
4. In the repo, go to Settings → Pages → set Source to the `main` branch, root folder.
5. Your site goes live at `https://yourusername.github.io` within a minute or two.
