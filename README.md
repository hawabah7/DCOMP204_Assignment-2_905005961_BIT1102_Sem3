# CampusNest Freetown

A responsive, multi-page website concept that helps students in Freetown find, compare and view safe rooms near their campus.

> **Note:** This is a student project for **DCOMP 204 (Assignment 2)**. All listings, prices, phone numbers and emails are illustrative. No real bookings are taken and no form data is sent anywhere.

**Author:** Hawa Bah, B.I.T 1102

---

## Pages

| Page | File | What it does |
| --- | --- | --- |
| Home | `index.html` | Hero search (campus, budget, room type), sample rooms, how it works, FAQs |
| Find a Room | `find-a-room.html` | Room cards, compare up to 3 rooms, cost comparison table |
| Services | `services.html` | Accommodation search, roommate matching, accompanied viewings, landlord support, anti-scam notice |
| About | `about.html` | Mission, story and the three-step verification standard |
| Contact | `contact.html` | Contact form (demo only), contact details, safety notice |

## Features

- **Responsive, mobile-first layout** with breakpoints at 700px (tablet) and 1000px (desktop)
- **Mobile navigation menu** with a toggle button and `aria-expanded` support
- **Room comparison tray** that limits selection to 3 rooms and shows a live count
- **Contact form** with a friendly confirmation message (nothing is submitted)
- **Accessibility touches:** semantic HTML, `aria-current` on the active page, labelled form fields, visible focus outlines
- **Safety messaging** reminding students never to pay before a physical viewing

## Project structure

```
campusnest/
├── index.html
├── find-a-room.html
├── services.html
├── about.html
├── contact.html
├── css/
│   └── style.css      # All styles (mobile-first, CSS variables for the colour palette)
├── js/
│   └── main.js        # Menu toggle, compare tray, contact form confirmation
└── README.md
```

## Running the project in VS Code

### Option 1: Live Server (recommended)

1. Install [Visual Studio Code](https://code.visualstudio.com/).
2. Open the `campusnest` folder: **File > Open Folder...**
3. Open the **Extensions** panel (`Ctrl+Shift+X`, or `Cmd+Shift+X` on Mac) and install **Live Server** by Ritwick Dey.
4. Right-click `index.html` in the Explorer and choose **Open with Live Server**.
5. The site opens in your browser and reloads automatically whenever you save a file.

### Option 2: Open directly in a browser

Double-click `index.html`, or right-click it in VS Code and choose **Reveal in File Explorer** (or **Reveal in Finder**), then open it with your browser. No build step or installation is needed.

## Testing responsiveness

1. Open the site in Chrome or Edge.
2. Press `F12` to open DevTools, then `Ctrl+Shift+M` (or `Cmd+Shift+M`) to toggle device mode.
3. Try widths around 375px (phone), 768px (tablet) and 1280px (desktop).

## Tech stack

- HTML5
- CSS3 (Flexbox, Grid, custom properties)
- Vanilla JavaScript (no frameworks or dependencies)

## Design notes

- **Colour palette:** teal (`#0f5e57`, `#0a3f3b`), amber (`#f2a516`), mint and sky backgrounds
- **Fonts:** Segoe UI for body text and Trebuchet MS for headings, with system fallbacks

## Screenshot
** Home Page **
<img width="940" height="445" alt="Screenshot 2026-10-29 123529" src="https://github.com/user-attachments/assets/d083e7bb-2304-4585-9414-69ce6f7c6cb5" />
** About Page **
<img width="910" height="430" alt="Screenshot 2026-10-29 123757" src="https://github.com/user-attachments/assets/133d8b79-f721-4e36-8c60-2d8e2eabf3a2" />
** Services Page **
<img width="941" height="431" alt="Screenshot 2026-10-29 123731" src="https://github.com/user-attachments/assets/45e981e9-f913-4471-b9a8-88be1ac28b08" />
** Contact Page **
<img width="937" height="427" alt="Screenshot 2026-10-29 123834" src="https://github.com/user-attachments/assets/71ac39b0-831c-4c70-969b-a73c56210341" />
** Find a room **
<img width="932" height="419" alt="Screenshot 2026-10-29 123653" src="https://github.com/user-attachments/assets/20eb1dfb-b975-496b-a323-0dfb4d9223c3" />





## Disclaimer

CampusNest Freetown is a concept created for coursework. It is not a real accommodation service.
