# Dr. Lori Keleher — Philosophy Portfolio Website

Personal academic portfolio website for Dr. Lori Keleher, Professor of Philosophy and Director of the Fellowships Office at New Mexico State University.

---

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | The main website — all HTML, CSS, and JS in one file |
| `Lori-1.png` | Professional headshot used in the hero section |
| `images.jpg` | Photo of Dr. Keleher with her books, used in the Books section |

> ⚠️ All three files must stay in the same folder together or the images will not show up on the live site.

---

## 🌐 Hosting

This site is hosted on **Netlify** and connected to this GitHub repository.

- Any time you push a change to GitHub, Netlify will automatically republish the site within ~30 seconds.
- The domain is managed through **GoDaddy** with nameservers pointed to Netlify.
- HTTPS is handled automatically by Netlify (free SSL certificate).

---

## ✏️ How to Update the Website

### Step 1 — Edit the file
Open `index.html` in any text editor (Notepad, TextEdit, VS Code, etc.) and make your changes.

Common things to update:
- **Publications** — search for `pub-item` to find the publications list
- **Teaching** — search for `course-item` to find the courses
- **Bio** — search for `about-text` to find the biography paragraphs
- **Contact info** — search for `contact-block` to find office and email info
- **CV link** — search for `Download CV` and replace `href="#"` with a link to your PDF

### Step 2 — Save and push to GitHub
Open your terminal, navigate to this folder, and run:

```bash
git add .
git commit -m "describe what you changed"
git push
```

Example commit messages:
```bash
git commit -m "added new publication"
git commit -m "updated office hours"
git commit -m "added cv link"
```

### Step 3 — Done!
Netlify detects the push and republishes automatically. The live site will update within about 30 seconds.

---

## 🖼️ How to Replace a Photo

1. Add the new photo file to this folder
2. Open `index.html` and search for the old filename (e.g. `Lori-1.png`)
3. Replace it with the new filename
4. Push to GitHub as described above

---

## 🔗 Important Links

- **Live site:** your-domain.com *(update this once the domain is connected)*
- **Netlify dashboard:** https://app.netlify.com
- **GitHub repo:** https://github.com/YOURUSERNAME/REPO-NAME *(update with real URL)*
- **Dr. Keleher's Academia.edu:** https://independent.academia.edu/LoriKeleher
- **NMSU Philosophy Dept:** https://philos.nmsu.edu

---

## 🛠️ Tech Stack

This is a plain static website — no frameworks, no dependencies, no build step required.

- Pure **HTML, CSS, and JavaScript** in a single file
- Google Fonts loaded via CDN (Cormorant Garamond + Jost)
- YouTube video embedded via iframe
- Scroll animations via the Intersection Observer API

---

## 📬 Contact

For questions about the website contact the site administrator.  
For questions about Dr. Keleher's work: **lkeleher@nmsu.edu**
