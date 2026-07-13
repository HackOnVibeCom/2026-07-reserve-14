# HackOnVibe — Project Questionnaire

**1. What does your application/service do?**

FORGE Launchpad generates real launch-promotion materials — an app store listing, a landing page blurb, three social posts in different voices, a roadmap infographic, and an Instagram-ready square ad — from a single form and a single Claude call. Its first real subject is FORGE Advisor Lite, a synthetic test-data generator built and deployed the same weekend, so everything Launchpad has generated describes a real, working, live application rather than a hypothetical one built to fit the brief.

**2. Who is the target audience?**

Solo builders and small teams shipping small products frequently — people who need competent launch copy and a couple of decent graphics every few weeks, don't have a marketing hire, and don't have the budget or time to freelance it out each time.

**3. Which countries are the expected buyers of this service?**

English-speaking, builder-dense markets first: United States, Canada, United Kingdom, and Australia — where the indie-hacker and solo-founder population doing frequent small launches is largest and where an English-only tool needs no localization to be useful on day one.

**4. Who are your competitors?**

Generic AI copywriting tools (Copy.ai, Jasper, and similar) produce marketing text but aren't grounded in the specific facts of one real launch and don't produce matched visual collateral from that same input. Design tools like Canva produce graphics but require manual work and don't generate copy at all. FORGE Launchpad's difference is a single input producing both consistent copy and consistent visuals together, from one generation, rather than a patchwork of separate tools each requiring their own manual setup.

**5. What is your advantage?**

Two things a general-purpose copywriting tool doesn't do. First, generation and packaging are split in the backend: the one expensive Claude call happens once and every piece of collateral draws from that same cached result, so the copy and the visuals can't drift out of sync the way independent tool calls would. Second, the prompts themselves are built to prevent overclaiming — the infographic's "Today vs. Tomorrow" split is rendered from two real lists the user typed, not free text a model could quietly embellish — which matters directly for the credible, honest business story this track is judging.
