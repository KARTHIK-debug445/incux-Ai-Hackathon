# React + Vite

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules.

Currently, two official plugins are available:

- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react) uses [Oxc](https://oxc.rs)
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react-swc) uses [SWC](https://swc.rs/)

## React Compiler

The React Compiler is not enabled on this template because of its impact on dev & build performances. To add it, see [this documentation](https://react.dev/learn/react-compiler/installation).

## Expanding the ESLint configuration

If you are developing a production application, we recommend using TypeScript with type-aware lint rules enabled. Check out the [TS template](https://github.com/vitejs/vite/tree/main/packages/create-vite/template-react-ts) for information on how to integrate TypeScript and [`typescript-eslint`](https://typescript-eslint.io) in your project.
## prompt
Build an enterprise-grade web application named:

"TeleIntel AI – Advanced Telecom Forensic Intelligence Platform"

This is a high-security AI-powered investigative system used by cybercrime and telecom forensic units.

IMPORTANT:
- Do NOT connect to external APIs.
- Do NOT configure OpenAI.
- Do NOT configure Supabase.
- Use structured mock data.
- Focus heavily on UI/UX quality and professional polish.

====================================================
DESIGN REQUIREMENTS (CRITICAL)
====================================================

Create an ULTRA-PREMIUM DARK GLASSMORPHISM CYBER INTELLIGENCE INTERFACE.

Visual Style:
- Deep dark gradient background (midnight navy → black)
- Frosted glass cards with blur backdrop
- Soft neon glow accents (electric blue, cyan, subtle violet)
- Smooth animated gradient highlights
- Thin glowing borders
- Elegant shadows
- Modern sans-serif typography (clean, sharp)
- High-end SaaS dashboard feel
- Government cyber intelligence aesthetic

Add:
- Subtle animated particle background
- Smooth hover transitions
- Soft glowing buttons
- Micro-interactions on click
- Animated page transitions
- Floating glass sidebar
- Collapsible navigation
- Icon-based navigation (minimal + elegant)

This must feel like:
Premium AI SaaS product
Cybersecurity command center
National intelligence system

NO basic layout.
NO flat UI.
NO simple Bootstrap look.

====================================================
APP STRUCTURE
====================================================

1) LOGIN PAGE
- Centered frosted glass login card
- Animated gradient border glow
- Role-based login (Admin / Investigator)
- Smooth entrance animation
- Demo credentials
- Secure, official look

2) MAIN DASHBOARD (Command Center)

Top Metrics Cards (Glass Panels):
- Total Calls
- Unique Phone Numbers
- Suspicious Activity Count
- Peak Activity Hour
- Most Active Tower

Charts Section:
- Animated Bar Chart (Top 5 frequent callers)
- Line Chart (Call timeline activity)
- Pie Chart (Time-based distribution)
- Heatmap-style activity visualization (if possible)

All charts must match dark theme.

3) DATASET MANAGEMENT PAGE
- Drag & Drop Upload Panel (Glass UI)
- File preview section
- Animated success notification
- Mock dataset preview table (scrollable, elegant)
- Activity log panel

4) AI INVESTIGATION ASSISTANT (Most Important Page)

Chat Interface:
- Glass chat container
- User messages aligned right
- AI responses aligned left
- Typing animation effect
- Smooth message fade-in
- Scrollable conversation area

Simulated AI Logic:

If user message contains:
- "frequent" → show top 5 callers
- "night" or "midnight" → show calls between 12AM–4AM
- "duration" or "long" → show longest calls
- "tower" or "location" → show clustered location activity
- otherwise → show overall insights summary

Each response must include:
- Clean formatted table
- Small animated chart
- Professional investigation summary paragraph
- Highlight suspicious numbers in glowing accent color

5) INVESTIGATION REPORT GENERATOR

- Button: "Generate Case Intelligence Report"
- Generate structured formatted report:
    Case ID
    Officer Name
    Date
    Investigation Summary
    Suspicious Numbers
    Behavioral Pattern Observations
    Recommended Action

Report must look printable and official.
Include watermark-style background text:
"Confidential – For Official Use Only"

====================================================
DATA SIMULATION
====================================================

Generate 800–1000 realistic telecom records.

Include:
- Indian-format mobile numbers
- One extremely frequent caller
- Multiple midnight calls
- One long-duration anomaly
- Repeated tower movement pattern

Ensure data supports intelligent-looking insights.

====================================================
EXTRA POLISH
====================================================

- Add global search bar
- Add notification bell
- Add user profile dropdown
- Add dark/light toggle (optional)
- Add subtle glow on active sidebar item
- Add smooth loading skeletons
- Add dashboard welcome animation
- Fully responsive layout

====================================================
FINAL GOAL
====================================================

The app must look like a real AI-powered forensic intelligence system used by national cybercrime units.

It must feel:
Professional.
Premium.
Futuristic.
Hackathon-winning.

No plain components.
No generic styling.
Everything should feel high-end and polished.
