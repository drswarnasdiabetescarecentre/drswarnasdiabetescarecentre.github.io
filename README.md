# Dr. Swarna's Diabetes Care Centre — Website

Official website for **Dr. Swarna's Diabetes Care Centre**, a specialist diabetology clinic in RA Puram, Chennai.

🌐 **Live site:** https://drswarnasdiabetescarecentre.github.io  
🏥 **Primary domain:** https://drswarnasdiabetescarecentre.com  
📞 **Contact:** 84383 25434

---

## About the clinic

Dr. Swarna's Diabetes Care Centre offers comprehensive diabetes management, neuropathy screening, fatty liver assessment, and personalised diet counselling. The clinic is run by a husband-wife team of specialist diabetologists based in RA Puram, Chennai.

**Doctors:**
- Dr. B. Parthasarathy — MD Physician (Russia), Consultant Diabetologist
- Dr. S. Swarna Pradha — MBBS, F. Diab, Consultant Diabetologist

**Clinic hours:** Monday – Saturday, 10 AM – 1 PM and 5 PM – 8 PM

---

## About this repository

This repository hosts the static website for the clinic. It is published automatically via **GitHub Pages** — any commit pushed to the `main` branch is reflected on the live site within a few minutes.

The site was initially built as a goodwill gesture by a patient after attending the Mega Diabetes & Fatty Liver Screening Camp on 24th May 2026.

---

## Project structure

```
/
├── index.html               # Main website (single page)
├── assets/
│   └── images/
│       ├── logo.png          # Clinic logo
│       ├── drswarna.png      # Dr. S. Swarna Pradha photo
│       ├── inauguration.png  # Clinic inauguration photo
│       ├── nameboard.png     # Clinic nameboard photo
│       └── megacamp.png      # Screening camp photo
└── README.md                 # This file
```

---

## How to make changes

### Option A — Edit directly on GitHub (easiest)
1. Open the file you want to change (e.g. `index.html`)
2. Click the ✏️ pencil icon (top right of the file view)
3. Make your edits
4. Scroll down, add a short note about what you changed, and click **Commit changes**
5. The live site updates automatically within 1–2 minutes

### Option B — Clone and edit locally
```bash
git clone https://github.com/drswarnasdiabetescarecentre/drswarnasdiabetescarecentre.github.io
cd drswarnasdiabetescarecentre.github.io
# make your changes
git add .
git commit -m "describe what you changed"
git push
```

---

## Common updates

### Adding or replacing a photo
Place the image file inside `assets/images/` and update the `src` attribute of the relevant `<img>` tag in `index.html`.

### Updating clinic hours
Search for `10 AM` in `index.html` — hours appear in two places (hero section and contact section).

### Adding a future screening camp
Find the `id="camp"` section in `index.html` and update the date, time, and test list.

### Updating the Calendly booking link
Search for `calendly.com/drswarnasdiabetescarecentre` and replace the URL if the Calendly account changes.

---

## Integrations

| Service | Purpose | Link |
|---|---|---|
| GitHub Pages | Free hosting & auto-publish | Automatic via this repo |
| Calendly | Online appointment booking | https://calendly.com/drswarnasdiabetescarecentre |
| WhatsApp Business | Patient messaging | https://wa.me/918438325434 |
| Google Maps | Clinic location embed | Sri Siddhi Flats, RA Puram |

---

## Pending items

- [ ] Add Dr. Parthasarathy's photo to the Doctors section
- [ ] Add Instagram profile link (once handle is created)
- [ ] Claim and verify Google Business Profile
- [ ] Add `<meta name="description">` tag for SEO

---

## Contributing

This site is maintained by the clinic team. For technical assistance, raise a GitHub Issue or contact the original contributor via the clinic's WhatsApp number.

---

*Built with plain HTML & CSS. No frameworks, no dependencies — easy for anyone to edit.*