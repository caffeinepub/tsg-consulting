# TSGP Consulting

## Current State
A manpower consultancy website with:
- Landing page (Hero, Services, Industries, Why Choose Us, About, Team, Company Photos, Contact/Inquiry Form)
- Admin panel to view submitted inquiries
- Backend: Motoko with inquiry submission and admin management
- Team section listing 11 employees including Siva Kumar TN (Power BI Developer)

## Requested Changes (Diff)

### Add
1. **IT Training / Online Classes section** -- A new "Online IT Training" section on the homepage highlighting that TSGP Consulting offers online IT-related classes. Feature Power BI as the flagship course, taught by Siva Kumar TN (10 years experience). Show course cards for:
   - Power BI (instructor: Siva Kumar TN, 10 yrs exp) -- flagship
   - AWS Cloud (instructor: Heamanth Kumar)
   - IT Resume Building (help candidates build strong IT resumes)
   - IT Interview Preparation (mock interview coaching)
2. **Mock Interview Preparation** -- Course card / feature block emphasizing mock interview practice for IT roles.
3. **Resume Building Support** -- Course card / feature block for IT resume building assistance.
4. **Nav link** -- Add "Training" link in the navbar pointing to the new training section (`#training`).

### Modify
- Hero badge / tagline: optionally mention "Online IT Training" alongside manpower consultancy.
- Hero stats: update "Team Members" if needed.

### Remove
- Nothing removed.

## Implementation Plan
1. Add `TrainingSection` component to `HomePage.tsx` with course cards for Power BI, AWS, Resume Building, and Mock Interview Prep.
2. Add `#training` nav link in `Navbar`.
3. Place `TrainingSection` between the Team section and the Company Photos section (or after team) in the page layout.
4. Use existing design tokens (navy, gold, card styles) for visual consistency.
5. No backend changes needed -- training is informational, enrollment via contact form.
