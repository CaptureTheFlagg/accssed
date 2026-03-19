# AccessEd Project

## What this site is
A student-written website about disability rights and K-12 
accommodations. Built as a high school passion project by a 
junior with ADHD, anxiety, and fine motor delay. 
Written by a student, for students.

## Site name and tagline
Name: AccessEd
Tagline: Know Your Rights. Own Your Education.

## Audience
Primary: High school students with disabilities who are 
confused, frustrated, or being ignored by their school.
Secondary: College admissions officers reviewing the project.

## Pages to build
1. index.html — Home
2. 504-vs-iep.html — 504 vs IEP
3. rights.html — Your Legal Rights
4. process.html — The Accommodation Process
5. accommodations.html — Common Accommodations
6. advocate.html — Self-Advocacy
7. college.html — Transitioning to College
8. faq.html — FAQ
9. resources.html — Resources

## Design system
- Background: #FFFDF7
- Primary text: #1C1C1C
- Secondary text: #4A4A4A
- Accent orange-red: #D94F2B
- Accent blue: #1A56DB
- White text on dark surfaces only: #FFFFFF
- Card background: #FFFFFF
- Subtle section background: #F5F0E8
- Border color: #E0D9CE
- Heading font: Plus Jakarta Sans (Google Fonts)
- Body font: Inter (Google Fonts)
- Base font size: 17px
- Line height: 1.75
- Max content width: 720px for text, 1100px for full layout

## Design inspiration
- Notion.so: clean organization, breathing room, approachable
- Understood.org: serious topic handled with warmth
- But more personality than both — bolder typography, stronger 
  use of accent color, feels made by a real person not 
  an institution

## Personality
This site should feel like a knowledgeable older friend 
explaining your rights — not a lawyer, not a government 
website. Warm, confident, and clear. Every page should 
answer: what do I actually DO with this information?

## SKILL: Accessibility
- Every image must have descriptive alt text
- All color combinations must pass WCAG AA contrast ratio
- Font size never below 16px
- All interactive elements must be keyboard navigable
- Use semantic HTML always: nav, main, article, section, footer
- Never use divs for everything

## SKILL: Responsive design
- Mobile first — design for phone screen first, scale up
- Every page must look good at 320px, 768px, and 1200px
- Navigation must collapse to a hamburger menu on mobile
- No horizontal scrolling ever
- Touch targets minimum 44px tall on mobile

## SKILL: Code quality
- Every HTML file must be complete and self contained
- No external dependencies except Google Fonts
- Use CSS variables for all colors in :root
- Comment any complex CSS or JavaScript
- No placeholder text ever — all content must be real
- Validate HTML structure before finishing each page

## SKILL: Content accuracy
- This site contains legal and rights-based information
- Flag any uncertain legal claim with <!-- VERIFY: -->
- Never invent statistics or legal facts
- All legal information is based on federal US law unless 
  stated otherwise
- Always include near legal content: 
  "This is not legal advice"
- Cite the specific law when making legal claims

## SKILL: Writing style
- Audience is a stressed high school student who may be 
  being ignored by their school
- Write like a knowledgeable older friend, not a lawyer
- Maximum sentence length: 25 words
- No jargon without immediate plain-English explanation
- Use you and your school — never passive voice
- Break up any paragraph longer than 4 lines

## SKILL: Performance
- No unnecessary JavaScript
- If it can be done in CSS, do it in CSS
- Google Fonts limited to 2 families maximum
- No animations that cant be disabled for reduced motion
- Every page should load fast on a normal connection

## Navigation
Every page must have:
- Fixed top navigation bar linking to all 9 pages
- AccessEd logo top left linking to index.html
- Footer with legal disclaimer on every page
- Active state on current page in navigation

## Important content notes
- ADHD falls under Other Health Impairment in IDEA, 
  not its own category
- Section 504 has no fixed federal timeline — reasonable 
  time standard, many districts use 30 days per step
- IEP: 60 calendar days from consent to evaluation, 
  then 30 days to develop the IEP
- You do NOT need a diagnosis to request an evaluation
- Written request starts the clock — verbal does not
- IEPs end permanently at high school graduation
- College accommodations do not renew automatically 
  each semester
- Summary of Performance document — IEP students are 
  entitled to this at graduation, most dont know it exists
- The documentation disconnect — high school IEP alone 
  often not enough for college disability services

## Rules
- Build one page at a time
- Ask before moving to the next page
- Never use placeholder text
- All content must be real and accurate
- Mobile responsive always
- Every page links to every other page in the nav