# Web Development Portfolio - Part 2 Implementation

## 1. Changelog (Feedback Corrections)
| Version | Date       | Section Modified | Description of Correction / Improvement |
| :---    | :---       | :---             | :---                                    |
| v1.1.0  | 2026-10-05 | Navigation & HTML| Corrected structural nesting in `index.html` based on Part 1 lecturer feedback. |
| v1.2.0  | 2026-10-05 | Architecture     | Integrated external `style.css` stylesheet across all subpages. |
| v1.3.0  | 2026-10-05 | Layout & Grid    | Replaced legacy float layout with modern CSS Grid and Flexbox structures. |

## 2. Responsive Design & Testing Evidence

### Breakpoint Strategy
- **Desktop (>1024px):** 3-column grid structure, full horizontal navigation bar.
- **Tablet (601px - 1024px):** 2-column grid structure, adjusted font scaling using `rem` units.
- **Mobile (<=600px):** Single-column stacked layout, vertical navigation stack.

### Testing Matrix & Screenshots
*Note: Replace image paths below with your actual captured screenshot files from DevTools.*

1. **Desktop View (1920x1080):**
   ![Desktop View](docs/screenshots/desktop-view.png)
   *Verified 3-column layout and hover interaction states on cards.*

2. **Tablet View (768x1024):**
   ![Tablet View](docs/screenshots/tablet-view.png)
   *Verified 2-column layout reflow via iPad viewport simulation in Chrome DevTools.*

3. **Mobile View (375x667):**
   ![Mobile View](docs/screenshots/mobile-view.png)
   *Verified single-column reflow and responsive navigation display.*
