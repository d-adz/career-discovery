# PathFinder — Discover Your Career DNA

> A free, self-contained career intelligence assessment built by Demi Adewole.
> **LinkedIn:** [linkedin.com/in/demiadewole](http://linkedin.com/in/demiadewole)

---

## The Story Behind This

I built PathFinder after finishing university with no clear idea of where I was headed.

I had skills, drive, and ambition — but no real framework for connecting who I *am* to what I should *do* next. Every career quiz I tried felt shallow — pick your favourite colour, here are three jobs. Every job board felt overwhelming and impersonal. I kept thinking: *why isn't there something that actually tries to understand how I think and work, not just what I studied?*

So I built it.

PathFinder is the tool I wish I had when I graduated. If you're feeling lost after university — or stuck at a crossroads, mid-career or otherwise — this is for you. It's entirely free, requires no setup, and runs directly in your browser.

---

## What It Does

PathFinder is a 15-question behavioural assessment that analyses *how* you think, work, and what energises you — then maps those patterns to career paths where you'll genuinely thrive.

Unlike personality tests that give you a four-letter label and leave you there, PathFinder gives you:

**1. Your Behavioural Archetype**
One of five deeply described profiles — The Builder, The Deep Thinker, The Connector, The Visionary, or The Director — based on your specific combination of scores across 9 dimensions.

**2. Your Strength Dimensions**
A visual breakdown of your scores across Analytical, Creative, People Skills, Technical, Leadership, Research, Structure, Entrepreneurial, and Communication dimensions — so you can see exactly where your natural strengths live.

**3. Your Identified Skills**
Six specific transferable skills you have, derived directly from your behavioural profile and dimension scores. These are skills you can put on a CV, articulate in an interview, or use to guide your next learning investment.

**4. Career Path Recommendations**
Your top 5 career matches, each scored by percentage fit, with a clear explanation of *why* that path suits your specific combination of traits — not just a generic description of the field. Each recommendation includes specific job titles to target.

**5. Personalised Next Steps**
Five concrete, immediately actionable steps you can start today — tailored to your top career match and dominant behavioural trait. Each step includes an honest time estimate (e.g., "Today — 20 mins", "This Week").

---

## Features

- **Sign up / Log in** — create a free account to save your results and access your history any time
- **Guest mode** — take the assessment without signing up (results won't be saved)
- **Personal dashboard** — view all past assessments, your archetype history, and account details
- **Results auto-saved** — every assessment you complete while logged in is automatically saved to your profile
- **Fully offline** — no server, no backend, no internet required after the file is loaded. Everything runs in your browser using local storage
- **Copy results** — one-click copy your results summary to share with others
- **Responsive design** — works on desktop and mobile

---

## How to Use

1. Open `career-discovery.html` in any modern web browser (Chrome, Safari, Firefox, Edge)
2. Create a free account (recommended) or continue as a guest
3. Answer the 15 questions honestly — choose what feels most natural, not what sounds "correct"
4. Review your results: archetype, strength dimensions, skill profile, career recommendations, and next steps
5. Come back any time — your results are saved to your profile if you're logged in

---

## The Assessment

The 15 questions cover 9 behavioural dimensions:

| Dimension | What it measures |
|---|---|
| Analytical | Logical reasoning, data-driven thinking, precision |
| Creative | Ideation, lateral thinking, aesthetic sensibility |
| People Skills | Empathy, relationship building, emotional intelligence |
| Technical | Systems thinking, building, hands-on execution |
| Leadership | Vision, direction-setting, decision-making under pressure |
| Research | Depth of curiosity, synthesis, knowledge-seeking |
| Structure | Planning, organisation, execution reliability |
| Entrepreneurial | Risk tolerance, opportunity spotting, bias to action |
| Communication | Persuasion, storytelling, clarity across audiences |

Scores are normalised across all 9 dimensions. Career fit percentages are calculated using a weighted scoring model that prioritises the dimensions most predictive of success and satisfaction in each field.

---

## Career Paths Covered

- Software Engineering / Development
- Product Management
- UX / Product Design
- Data Science / Analytics
- Entrepreneurship / Founding
- Marketing & Brand Strategy
- Consulting / Strategy
- Therapy / Coaching / Counselling
- Research / Academia
- Education / Teaching / Training
- Operations / Project Management
- Creative Direction / Writing

---

## Technical Notes

PathFinder is a **single HTML file** with no external dependencies, no build step, and no backend. It runs entirely in the browser.

**User accounts and results** are stored in the browser's `localStorage` under the following keys:
- `pf_users` — array of registered user objects
- `pf_session` — the currently logged-in user
- `pf_results_{userId}` — saved assessment results per user (up to 20 per account)

**Important:** Because data is stored in `localStorage`, it is tied to the specific browser and device you use. Clearing browser data will remove accounts and saved results. This is intentional — it keeps the tool fully self-contained with zero infrastructure.

Passwords are encoded with Base64 before storage. This is a client-side demo — do not use sensitive passwords.

---

## About the Creator

**Demi Adewole**
University graduate, builder, and career-discovery enthusiast.

PathFinder was born out of a personal frustration — the lack of a genuinely thoughtful, free tool to help people at the start of their careers understand themselves better and make smarter decisions about where to go next.

Connect on LinkedIn: [linkedin.com/in/demiadewole](http://linkedin.com/in/demiadewole)

---

*PathFinder is free to use, share, and adapt. If it helps you find your path, pass it on.*
