# Auth POC — HTML Authentication System

A fully responsive, professionally designed authentication UI built with **HTML5**, **Bootstrap 5**, and a custom **CSS design system**. No backend — pure front-end proof of concept.

---

## Pages

| File | Description |
|---|---|
| `login.html` | Sign-in form with email & password |
| `register.html` | Registration form with live validation |
| `forgot-password.html` | Email submission for password reset |
| `reset-password.html` | New password form with strength meter & visibility toggle |
| `dashboard.html` | Post-login dashboard with stats, activity, and account info |

---

## Navigation Flow

```
login.html ──────────────────────────► dashboard.html
    │                                        │
    ▼                                        ▼
register.html ──► login.html          login.html (logout)
    │
    ▼
forgot-password.html ──► reset-password.html ──► login.html
```

---

## Tech Stack

- **HTML5** — semantic, accessible markup
- **Bootstrap 5.3.3** — grid system, utilities, navbar
- **Bootstrap Icons 1.11.3** — icon set
- **Google Fonts — Inter** — clean modern typeface
- **style.css** — custom design system (variables, components, animations)

---

## Features

- Responsive across all breakpoints — mobile (xs), tablet (sm/md), laptop (lg), desktop (xl)
- CSS custom properties for consistent color palette and spacing
- Card entrance animation (`cardIn` keyframe)
- Gradient backgrounds with radial glow effects
- Custom input groups with icon prefixes and focus ring colors per page
- Live form validation with `is-valid` / `is-invalid` group states
- Password strength meter (Weak → Fair → Good → Strong)
- Password visibility toggle (show/hide)
- Sticky navbar on dashboard
- Stat cards with hover lift effect
- Activity timeline and account info panel

---

## Responsive Breakpoints

| Breakpoint | Width | Layout |
|---|---|---|
| xs (mobile) | < 576px | Single column, compact spacing |
| sm (large mobile) | 576px – 767px | Single column, comfortable spacing |
| md (tablet portrait) | 768px – 991px | Wider card, 2-col name+email on register |
| lg (tablet landscape / laptop) | 992px – 1199px | Full layout, 4-col stat cards |
| xl (desktop) | ≥ 1200px | Optimal max-width, full spacing |

---

## File Structure

```
html forms/
├── login.html
├── register.html
├── forgot-password.html
├── reset-password.html
├── dashboard.html
├── style.css
└── README.md
```

---

## Suggested Screenshots

Include one screenshot per page for the GitHub repository:

1. `screenshot-login.png` — Login card centered on dark gradient background
2. `screenshot-register.png` — Register card with 2-column name/email layout
3. `screenshot-forgot.png` — Forgot password card with info hint box
4. `screenshot-reset.png` — Reset password card with strength bar visible
5. `screenshot-dashboard.png` — Full dashboard with navbar, banner, stat cards, and panels
6. `screenshot-mobile.png` — Any auth page on a 375px mobile viewport

---

## GitHub Repository

[https://github.com/gous-gzone/-html-authentication-poc](https://github.com/gous-gzone/-html-authentication-poc)

---

## Notes

- All navigation uses HTML `<form action="">` and `<a href="">` — no JavaScript routing
- Validation is client-side only — no server communication
- Designed as a UI/UX proof of concept for an authentication flow
