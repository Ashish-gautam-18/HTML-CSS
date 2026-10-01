# Mistvale Tea Co. — Technical Assessment Notes

## 1. What I Changed
- **Bugs Fixed:** Corrected the dynamic calculation loops in the shopping cart. Implemented the strict 5-pack item check condition per product and stock constraints. Restricted the WELCOME10 voucher from applying to Gift boxes and added the ₹399 minimum cart value rule.
- **Design & Layout:** Structured the typography hierarchy using Fraunces and Inter fonts. Set up a clean CSS Custom Property system using exact hex tokens. Reordered all 10 required sections into the strict sequence requested.
- **UX & Mobile:** Made the store fully responsive with a 2-column grid layout on mobile screens. Added proper hover and focus states for all interactive elements.
- **Framework Removal:** Completely removed jQuery, animate.css, and FontAwesome icons to strictly follow the clean, plain Vanilla JavaScript constraint.

## 2. What the AI Got Wrong
- The AI tool initially attempted to export standalone jQuery syntax and generated broken format currency template literals containing backslashes. I caught these syntax validation errors in the VS Code compiler and manually mapped out clean native JavaScript formatting handlers.

## 3. Image Handling
- Configured native code to map layout references cleanly to the provided template assets folder (`hero-banner.png` and `p101.png` to `p108.png`).

## 4. How I Tested It
- Tested across multiple simulated phone viewport sizes in Chrome DevTools to ensure zero sideways scrolling. Verified accessibility via high-contrast checks and verified keyboard navigation focus rings.

## 5. Questions for the Team
- I noticed the delivery pincode check template uses a mock API with delayed response times. I added a loading state ("Checking…") that disables the button to prevent double submission bugs while waiting for data.

## 6. Time Spent
- Approximately 4 hours spent on manual refactoring, deep technical debugging, testing, and rule verification constraints.
