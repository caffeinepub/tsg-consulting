# TSGP Consulting

## Current State
A full consultancy website with Hero, Services, Industries, Why Choose Us, About (with founder photo), Company Photos, Contact Form, and Footer sections.

## Requested Changes (Diff)

### Add
- A new "Our Team" section displaying 15 current employees of TSGP Consulting with their name, role/designation, and a professional avatar/photo. This section should appear between the About section and Company Photos section.

### Modify
- Navigation bar: add "Team" nav link pointing to #team section.
- Update the team stat in hero from generic to something reflecting "15+ Team Members".

### Remove
- Nothing to remove.

## Implementation Plan
1. Add a static array of 15 employees (names, roles, department) to HomePage.tsx.
2. Create a `TeamSection` component that renders employee cards in a responsive grid (3-5 columns on desktop, 2 on tablet, 1 on mobile).
3. Each card shows: professional avatar (using initials-based avatar with color coding), name, designation, and department badge.
4. Insert `<TeamSection />` between `<AboutSection />` and `<CompanyPhotosSection />` in the page layout.
5. Add "Team" link in the Navbar navLinks array.
6. Update hero stats to show "15+" for Team Members.
