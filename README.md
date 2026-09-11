# Doke Surita — Portfolio


<img width="1902" height="982" alt="image" src="https://github.com/user-attachments/assets/7a26fb64-e790-4e8c-99e8-f54130841c24" /> <img width="1919" height="990" alt="image" src="https://github.com/user-attachments/assets/330f353c-e9b1-42e2-9f85-82e675a26f35" />




A single-page, interactive portfolio built as a moodboard-style polaroid board — floating objects (laptop, brain, résumé, phone) that open into detail panels for Works, Skills, Experience, and Contact, plus a pull-cord dark mode toggle.

🔗 **Live site:** https://my-portfolio-ashen-six-52.vercel.app/

## Features

- **Interactive floating board** — clickable objects (laptop, brain, résumé, phone, and a polaroid photo) that bob and twist gently, grow on hover, and open into detail modals
- **Pull-cord dark/light mode** — drag the cord to toggle theme; swing direction and amplitude respond to how you pull it; preference is remembered between visits
- **Popup modals** for About Me, My Works, Experience, Skills, and Contact, with image galleries and a full-size lightbox viewer
- **"My Arsenal"** — an auto-scrolling marquee of tech stack logos in their real brand colors
- **Fully responsive** — a custom floating layout on desktop/tablet collapses into an organized grid on mobile
- **No build step** — plain HTML, CSS, and JavaScript in a single file; works with just a static file server

## Tech Stack

- HTML5 / CSS3 / vanilla JavaScript (no framework, no bundler)
- [Phosphor Icons](https://phosphoricons.com/) for UI icons
- [Simple Icons](https://simpleicons.org/) for brand/tech logos
- Google Fonts: Poppins, Bricolage Grotesque, Caveat

## Project Structure

```
├── index.html              # everything — markup, styles, and script
├── myportpic.jpg            # profile photo (polaroid)
├── laptop.png                # floating object — My Works
├── brain.png                  # floating object — Skills
├── phone.png                   # floating object — Contact
├── resume.webp                  # floating object — Experience
├── appbookingsys.png             # Appointment Booking project screenshot
├── accenture.jpg, valor.png, lra.png   # experience logos
├── grad1.jpg, grad2.jpg, grad3.jpg      # Education gallery
├── piano.jpg, gym.jpg, gym1.jpg,
│   billiards.jpg, billiard1.jpg,
│   bike.jpg, travel.jpg                  # Hobbies gallery
```

> All image filenames are referenced directly in `index.html` — if you rename or swap any image, update the matching `src` in the code.

## Running Locally

1. Clone or download this repository.
2. Open the folder in VS Code.
3. Install the **Live Server** extension (if you haven't already).
4. Right-click `index.html` → **Open with Live Server**.

No `npm install`, no build step — it's ready to go.

## Deployment

This is a static site, so it deploys as-is to any static host:

- **GitHub Pages** — Settings → Pages → Deploy from branch → `main` / root
- **Vercel** — import this repo, framework preset "Other," no build command
- **Netlify** — drag-and-drop the folder, or connect the repo

## Contact

- Email: [dokesurita@gmail.com](mailto:dokesurita@gmail.com)
- LinkedIn: [linkedin.com/in/doke-surita-598132249](https://linkedin.com/in/doke-surita-598132249)
