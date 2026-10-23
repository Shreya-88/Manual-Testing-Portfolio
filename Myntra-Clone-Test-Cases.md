# Test Cases — Myntra Clone Website

**Project:** Myntra Clone (HTML, CSS, Bootstrap)
**Tested By:** Shreya Gupta
**Test Type:** Manual Testing
**Environment:** Chrome 118+, Edge, Windows 10 | Viewports: 1920px / 768px / 375px

---

| TC ID | Module | Test Case Description | Steps to Execute | Expected Result | Actual Result | Status |
|-------|--------|----------------------|------------------|-----------------|---------------|--------|
| TC_01 | Homepage | Verify homepage loads successfully | Open index.html in browser | Page loads fully with all sections visible | Page loaded correctly | ✅ Pass |
| TC_02 | Header | Verify logo is displayed | Open homepage, check top-left | Logo visible and not distorted | Logo displayed correctly | ✅ Pass |
| TC_03 | Header | Verify logo click redirects to homepage | Click on logo from any section | User returns to homepage/top | Works as expected | ✅ Pass |
| TC_04 | Navigation | Verify all navbar menu items are visible | Check navbar (Men, Women, Kids, etc.) | All menu items visible and readable | All items visible | ✅ Pass |
| TC_05 | Navigation | Verify navbar links are clickable | Click each navbar item | Each link responds/navigates to section | One link unresponsive | ❌ Fail (Bug #01) |
| TC_06 | Search Bar | Verify search bar is visible | Check header area | Search bar displayed with placeholder text | Displayed correctly | ✅ Pass |
| TC_07 | Banner | Verify main banner image loads | Open homepage | Banner image loads without breaking | Loaded correctly | ✅ Pass |
| TC_08 | Product Section | Verify product images load | Scroll to product section | All product images display properly | All images loaded | ✅ Pass |
| TC_09 | Product Section | Verify product cards alignment | Inspect product grid | Cards evenly aligned with equal spacing | Aligned correctly | ✅ Pass |
| TC_10 | Product Section | Verify hover effect on product cards | Hover mouse over products | Hover effect (zoom/shadow) works | Works as expected | ✅ Pass |
| TC_11 | Footer | Verify footer is displayed | Scroll to page bottom | Footer visible with all sections | Footer displayed | ✅ Pass |
| TC_12 | Footer | Verify footer links are clickable | Click footer links | Links respond correctly | Some links are placeholders | ❌ Fail (Bug #02) |
| TC_13 | Responsive | Verify layout on tablet view (768px) | Resize browser to 768px width | Layout adjusts, no overlapping | Layout adjusts correctly | ✅ Pass |
| TC_14 | Responsive | Verify layout on mobile view (375px) | Resize browser to 375px width | All elements stack properly, no horizontal scroll | Minor element overflow found | ❌ Fail (Bug #03) |
| TC_15 | Cross-Browser | Verify site renders in Chrome | Open site in Chrome | Site displays correctly | Displays correctly | ✅ Pass |
| TC_16 | Cross-Browser | Verify site renders in Edge | Open site in Edge | Site displays correctly | Displays correctly | ✅ Pass |
| TC_17 | UI | Verify font consistency across page | Review all text sections | Uniform font family and readable sizes | Fonts consistent | ✅ Pass |
| TC_18 | UI | Verify color scheme matches design | Compare sections visually | Consistent brand colors throughout | Colors consistent | ✅ Pass |

---

**Summary:** 18 Executed | 15 Passed | 3 Failed → See [Bug-Report.md](Bug-Report.md)
