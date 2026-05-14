# Brookside Group of Schools — Website

Official website for the **Brookside Group of Schools**, Piet Retief, Mpumalanga, South Africa.

> *Excellentia · Fides · Ductus*
> Nurturing Excellence, Inspiring Faith, Shaping Tomorrow's Leaders.

---

## Project Structure

```
brookside-website/
├── index.html                    # Main school website
├── payment-arrangement.html      # Payment arrangement form (Finance)
├── assets/
│   ├── brookside-logo.png        # Official school crest / logo
│   ├── logo.png                  # Favicon
│   ├── brookside-campus.png      # Hero image
│   └── brookside-campus1 (2).png # Additional campus image
└── css/
    └── styles.css                # Global styles
```

---

## Pages

### `index.html` — Main Website
The school's public-facing homepage. Includes:
- Announcement banner
- Sticky navigation with desktop and mobile menus
- Hero section with campus imagery
- Phase quick-links (Daycare, Foundation, Intermediate, Senior, FET)
- Footer with contact details, quick links, and prospective campuses

**Built with:** Tailwind CSS (CDN), Google Fonts (Cinzel), Font Awesome

### `payment-arrangement.html` — Payment Arrangement Form
An official administrative form for **change of payment date** requests. Accessible via the **Finance** link in the navigation bar and footer.

Features:
- Brookside letterhead with official school crest
- Auto-generated reference number and today's date
- Student information fields
- Mid-year enrolment toggle with pro-rata support
- Fee structure inputs
- Payment schedule switcher (15th vs 25th payer)
- Live payment schedule table with installment breakdown
- Signature and stamp section
- Print / Save as PDF button

**Built with:** Tabler Icons (CDN), Tailwind CSS (CDN), vanilla JavaScript

---

## Contact

| | |
|---|---|
| **Address** | 5 De Wet Street, Piet Retief, Mpumalanga, 2380 |
| **Phone** | (087) 527-0655 |
| **WhatsApp** | (064) 507-0294 |
| **Email** | admin@brookside.africa |
| **Website** | www.brookside.africa |
| **Reg. No.** | 2022/371683/07 |

---

## Development

This is a static HTML/CSS website — no build step required. Open `index.html` in a browser or serve with any static file server:

```bash
# Python
python -m http.server 8000

# Node (npx)
npx serve .
```

---

© 2025 Brookside Group (PTY) LTD · Reg. No. 2021/871093/07
