# Bug Report — Myntra Clone Website

**Reported By:** Shreya Gupta
**Environment:** Chrome 118+, Windows 10

---

## 🐞 Bug #01 — Navbar link unresponsive
- **Module:** Navigation
- **Severity:** Medium | **Priority:** High
- **Steps to Reproduce:**
  1. Open the homepage
  2. Click on a navbar menu item
- **Expected Result:** Link navigates to the corresponding section/page
- **Actual Result:** Link does not respond (no href target assigned)
- **Status:** Open

---

## 🐞 Bug #02 — Footer links are non-functional placeholders
- **Module:** Footer
- **Severity:** Low | **Priority:** Medium
- **Steps to Reproduce:**
  1. Scroll to the footer
  2. Click on footer links (About, Contact, etc.)
- **Expected Result:** Links navigate to relevant pages/sections
- **Actual Result:** Links are placeholders (`#`) and do not navigate
- **Status:** Open

---

## 🐞 Bug #03 — Element overflow on mobile viewport (375px)
- **Module:** Responsive Design
- **Severity:** Medium | **Priority:** High
- **Steps to Reproduce:**
  1. Open the site in Chrome
  2. Press F12 → Toggle device toolbar → select iPhone SE (375px)
  3. Scroll through the page
- **Expected Result:** All elements fit within viewport; no horizontal scrolling
- **Actual Result:** Product card section overflows, causing horizontal scroll
- **Status:** Open

---

**Severity Guide:** Critical → blocks usage | High → major feature broken | Medium → feature partially works | Low → cosmetic issue
