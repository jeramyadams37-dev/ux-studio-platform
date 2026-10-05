# UX Studio: Complete UI/UX Design Curriculum

Handoff document for Gemini. Source platform: a single-file HTML/JS web app (no backend). This file contains the full curriculum content, assessment rules, labs, and certification logic so it can be rebuilt, extended, or deepened.

## 1. Program overview

- Modules: 50, ordered Beginner, Intermediate, Advanced, Expert
- Hands-on labs: 11
- Quiz questions in bank: 227
- Goal: take a learner from zero to employable (or ready to freelance or start a design business), with measurable proof of skill.
- Audience: self-taught learners, career changers, students. Platform must work on phones.

## 2. Completion and certification rules

- A module is complete when all three parts are done: (1) lesson marked complete, (2) quiz passed at 80% or higher (rounded: score >= round(0.8 x questions)), retakes unlimited, (3) project: every step checked AND a written evidence note of at least 30 characters.
- Three certificates: Foundation (levels: Beginner; 20-question exam); Professional (levels: Beginner, Intermediate, Advanced; 30-question exam); Expert (levels: Beginner, Intermediate, Advanced, Expert; 40-question exam).
- To start a tier exam: every module in that tier complete. Professional and Expert also require all labs complete; Foundation treats labs as optional.
- Final exam: random sample of the tier's quiz bank, options shuffled, no feedback until the end, pass at 80%, failed attempts list modules to review and can be retaken.
- Certificate: learner name, tier, module count, exam score, date, random 8-character ID, printable as PDF. States it is a self-study certificate and not an accredited credential.
- Progress is stored in the browser (localStorage key "uxc": lessons, quiz answers, project steps, evidence notes, lab completions, exam results, name).

## 3. Hands-on labs (interactive builds)

1. **Contrast Lab**: Build a color pair that passes WCAG AA. Spec: Two color pickers, live WCAG contrast ratio, pass/fail for AA text, large text, UI components, AAA. Complete at >= 4.5:1 and not plain black on white.
2. **Type Scale Lab**: Design a readable modular type scale. Spec: Base size and ratio picker with live scale preview. Complete when base >= 16px and the scale is saved.
3. **Card Sort Lab**: Organize content into groups users understand. Spec: Tap 9 content items into 3 groups, name groups. Complete when all sorted, each group has >= 2 items, all named.
4. **Wireframe Builder**: Assemble a mobile screen and pass the checks. Spec: Stack-based mobile wireframe builder. Checks: header first, a hero, >= 2 cards, exactly one primary button, nav or footer last.
5. **Heuristic Review**: Diagnose 5 usability problems. Spec: Match 5 usability problems to Nielsen heuristics. Need 4 of 5.
6. **Spacing Lab**: Apply the 8px grid and proximity. Spec: Sliders for padding, inner gap, group gap. Checks: all multiples of 8, group gap > inner gap, padding >= 16.
7. **Prototype State Lab**: Wire up a button state machine. Spec: Choose next state for 5 button events (default, loading, success, error), then test a live button.
8. **Accessibility Audit**: Find the real accessibility failures. Spec: Select only real accessibility failures from 6 items (placeholder-only label, color-only error, removed focus outline are failures; the other three pass).
9. **Tree Test Lab**: Find items in a hierarchy. Spec: Tree test: find 3 items in a site hierarchy; need 3 of 3 correct.
10. **Design Token Builder**: Create a purposeful token set. Spec: Pick primary color passing 4.5:1 with white, choose spacing base, name danger token by purpose (color-danger, not red-500). Live CSS variables output.
11. **Motion Timing Lab**: Tune durations for real interactions. Spec: Sliders tune durations: button feedback 100-200 ms, panel 200-300 ms, modal 200-400 ms, with live previews.

## 4. Module index

1. What UX Really Is (Beginner)
2. User Research (Beginner)
3. Flows & Information Architecture (Beginner)
4. UX Writing & Content Design (Beginner)
5. Figma & Tool Mastery (Beginner)
6. The Pro Tool Landscape (Beginner)
7. Free Design & Prototyping Tools (Beginner)
8. Student, Educator & Bootcamp Perks (Beginner)
9. Free Assets & Learning Resources (Beginner)
10. Open Source Design Tools (Beginner)
11. Design Fundamentals: Gestalt, Color, Type, Composition (Beginner)
12. Learning How to Learn (Beginner)
13. Wireframing (Intermediate)
14. Visual Design Basics (Intermediate)
15. Interaction & Prototyping (Intermediate)
16. Mobile, Responsive & Platform Design (Intermediate)
17. Psychology & Behavior (Intermediate)
18. HTML & CSS for Designers (Intermediate)
19. Graphics, Motion & 3D Tools (Intermediate)
20. Prototyping & Interaction Tools (Intermediate)
21. Research & Testing Tools (Intermediate)
22. Free Dev, Hosting & Android-Friendly Tools (Intermediate)
23. Open Source Dev, Components & Design Systems (Intermediate)
24. Licenses & Contributing (Intermediate)
25. Critical Thinking & Creativity (Intermediate)
26. Communication, Storytelling & Collaboration (Intermediate)
27. Focus, Productivity & Wellbeing (Intermediate)
28. Usability Testing & Accessibility (Advanced)
29. Design Systems & Portfolio (Advanced)
30. Quantitative Research & Experimentation (Advanced)
31. Service Design & Product Strategy (Advanced)
32. Accessibility in Depth (Advanced)
33. Portfolio & Case Studies (Advanced)
34. Resume, Job Search & Interviews (Advanced)
35. Freelancing & Client Work (Advanced)
36. Handoff & Developer Tools (Advanced)
37. AI-Powered Design Workflows (Advanced)
38. Accessibility & QA Tools (Advanced)
39. Business, Collaboration & Delivery Tools (Advanced)
40. Free Trials, Startup & Founder Programs (Advanced)
41. Open Source Research, Accessibility & Analytics (Advanced)
42. Open Source Productivity, Docs & Self-Hosting (Advanced)
43. Money, Negotiation & Career Capital (Advanced)
44. Data, AI & Emerging Interfaces (Expert)
45. Design Leadership & Ops at Scale (Expert)
46. Capstone: Ship a Product End to End (Expert)
47. Starting a Design Business or Product (Expert)
48. Career Growth & Lifelong Learning (Expert)
49. Build Your Pro Toolkit (Expert)
50. Mastery Roadmap: 12-Month Plan (Expert)

## 5. Full module content

### Module 1: What UX Really Is

**Level:** Beginner

#### Lesson

UX (user experience) is how a product feels and works across the whole journey. UI (user interface) is the visible layer: buttons, type, color, layout. UI is part of UX, never the whole of it.

Good design solves a real problem for a real person. The common process loops through five steps: understand, define, ideate, prototype, test. You repeat it; you never run it once.

Designers decide with evidence, not taste. Every choice should trace back to a user need or a business goal.

**The five steps in practice**

Understand: talk to users and study the context. Define: write a problem statement such as 'Busy parents need a faster way to reorder groceries.' Ideate: sketch many options before choosing one. Prototype: build the cheapest version that can be tested. Test: watch real people use it, then loop back.

**Ten usability heuristics**

Jakob Nielsen's heuristics are the checklist designers reuse for decades: visibility of system status, match with the real world, user control and freedom, consistency, error prevention, recognition over recall, flexibility, minimal design, helpful error messages, and help documentation. Use them to review any screen in minutes.

**Roles and careers**

UX researchers study users. Interaction and product designers shape flows and screens. Visual and UI designers craft the look. Content designers write the words. Many teams combine roles, so learn all five and then specialize.

**Why UX pays for itself**

Poor usability costs money: more support tickets, abandoned checkouts, churn, and rework after launch. Fixing a problem in design is far cheaper than fixing it in shipped code. UX work is justified by outcomes such as task success, conversion, retention, and support volume.

**The Double Diamond**

The Design Council's Double Diamond has four phases: Discover (explore widely), Define (narrow to the real problem), Develop (explore many solutions), Deliver (test and refine one). Each diamond diverges then converges. The first diamond is about the right problem; the second is about the right solution.

**Norman's design vocabulary**

Affordance is what an object allows you to do. A signifier is the visible cue that shows how (a button's shadow, a handle). Mapping links controls to results, feedback confirms what happened, constraints limit wrong actions, and a conceptual model is the story the design tells about how it works. When people blame themselves for errors, the design failed.

**Five quality components**

Nielsen defines usability by five components: learnability (first use), efficiency (speed once learned), memorability (return after a break), errors (how many and how recoverable), and satisfaction. Pick which matter most for your product: an ATM needs learnability, a pro tool needs efficiency.

**Ethics from day one**

Design choices change behavior at scale. Avoid dark patterns, collect only the data you need, and design for people unlike you. Inclusive and accessible defaults are cheaper to build in than to retrofit.

#### Key takeaways

- UX = the whole journey; UI = what you see and tap
- Process: understand, define, ideate, prototype, test
- Design for a problem, not a screen

#### Quiz

1. Which best describes UI?
   - a) The full customer journey
   - b) The visible layer people interact with (correct)
   - c) Marketing copy
   - Why: UI is the visual and interactive surface. UX is bigger.
2. The design process is best described as…
   - a) A straight line
   - b) A loop you repeat (correct)
   - c) A one-time workshop
   - Why: Testing reveals new problems, so you iterate.
3. A good design decision should be based on…
   - a) Personal taste
   - b) Evidence about users (correct)
   - c) The newest trend
   - Why: Evidence beats opinion.
4. 'Recognition over recall' means…
   - a) Make users memorize shortcuts
   - b) Show options instead of making people remember them (correct)
   - c) Remove menus
   - Why: Visible choices cost less memory than remembered commands.
5. Which is a problem statement?
   - a) Add a blue button
   - b) Parents need a faster way to reorder groceries (correct)
   - c) Use a carousel
   - Why: It names a user and a need, not a solution.
6. A flat grey rectangle gives no hint it can be tapped. This is a failure of…
   - a) Signifiers (correct)
   - b) Typography
   - c) Branding
   - Why: The affordance may exist but nothing signals it.
7. The first diamond of the Double Diamond ends with…
   - a) A defined problem (correct)
   - b) A finished UI
   - c) A launch
   - Why: Discover then Define focuses the problem.
8. Which usability component is about returning after months away?
   - a) Memorability (correct)
   - b) Efficiency
   - c) Satisfaction
   - Why: Can people remember how to use it?
9. A pro video-editing tool should weight which component most?
   - a) Efficiency (correct)
   - b) Only learnability
   - c) Only satisfaction
   - Why: Expert users value speed after learning.
10. A user repeatedly taps the wrong control. Best first reaction?
   - a) Blame the user
   - b) Examine the design's signifiers and mapping (correct)
   - c) Add a warning popup
   - Why: Repeated errors point to a design cause.

#### Project: Audit an app you use daily

1. Pick one app and write down the main job you use it for
2. List 3 things that work well and 3 that frustrate you
3. Mark each as UX (flow) or UI (visual)
4. Write one sentence on how you would fix the biggest frustration
5. List 3 heuristics your chosen app breaks and show the screen for each
6. Write a one-sentence problem statement for the app
7. Interview one person about a time an app confused them and map the confusion to a Norman concept
8. Redefine your audit problem as a Define-phase problem statement with a measurable success metric

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 2: User Research

**Level:** Beginner

#### Lesson

Research replaces guessing. Qualitative methods (interviews, observation) explain why people act. Quantitative methods (surveys, analytics) show how many.

In an interview, ask open questions about past behavior: 'Tell me about the last time you booked a trip.' Avoid leading questions like 'Don't you think this is easy?'

Turn findings into a persona (a realistic summary of a user type) and a journey map (steps, feelings, pain points over time).

**Recruiting and ethics**

Recruit people who match your target user, not friends who will be kind. Get consent before recording, explain how data is used, and never collect more than you need. Offer a fair incentive for longer sessions.

**Surveys and analytics**

Surveys scale but only answer what you ask, so keep them short and neutral. Analytics show where people drop off but not why. Pair a number ('40% leave at step 3') with an interview to learn the reason.

**Synthesis and jobs to be done**

Affinity mapping means writing each observation on a note and clustering similar ones into themes. Jobs to be done frames needs as 'When I ___, I want to ___, so I can ___.' This keeps you focused on motivation instead of demographics.

**Choose the method for the question**

Generative research (interviews, field visits, diary studies) discovers needs. Evaluative research (usability tests, A/B tests) checks solutions. Ask: what do we need to learn, and what decision will it inform? If no decision depends on it, do not run it.

**Run a strong interview**

Structure: warm-up, context, stories about specific past events, key topics, wrap-up. Use silence, follow with 'tell me more' and 'why', and avoid leading, double-barreled ('fast and easy?'), or hypothetical questions. People are poor predictors of future behavior but good reporters of past behavior.

**Bias and quality**

Watch for social desirability (saying what sounds good), confirmation bias (hearing what you expected), recency bias, and a sample of friends. Recruit by behavior, include edge users, and have a second person take notes so you can listen.

**Beyond interviews**

Contextual inquiry observes people in their real environment. Diary studies capture behavior over time. Surveys need neutral wording, balanced scales, one idea per question, and a pilot. Keep surveys short; every extra question lowers completion.

**From notes to insight**

An observation is what you saw. An insight combines observation, the underlying reason, and what it means for design: 'New users abandon setup (observation) because they fear choosing wrongly (reason), so we should show defaults and a way to change later (implication)'. Share findings with quotes and clips, not just slides.

**Ethics and consent**

Get informed consent, explain recording and storage, allow withdrawal, store data securely, anonymize reports, and comply with privacy laws such as GDPR where they apply.

#### Key takeaways

- Qualitative = why; quantitative = how many
- Ask about past behavior, not opinions about the future
- Personas and journey maps share findings

#### Quiz

1. Which question is best for an interview?
   - a) Would you use an app like this?
   - b) Tell me about the last time you did this task (correct)
   - c) Don't you find this confusing?
   - Why: Past behavior is reliable. Hypotheticals and leading questions are not.
2. Which method tells you WHY users act?
   - a) Analytics dashboard
   - b) Interviews (correct)
   - c) A/B test
   - Why: Interviews are qualitative.
3. A journey map shows…
   - a) Server architecture
   - b) Steps, emotions and pain points over time (correct)
   - c) Color palette
   - Why: It visualizes the experience from the user's side.
4. Analytics alone can tell you…
   - a) Why users quit
   - b) Where users quit (correct)
   - c) What users feel
   - Why: Numbers locate the problem; interviews explain it.
5. Affinity mapping is used to…
   - a) Cluster observations into themes (correct)
   - b) Choose fonts
   - c) Estimate cost
   - Why: It turns raw notes into insight.
6. Which question is double-barreled?
   - a) Is it fast and easy to use? (correct)
   - b) How did you last use it?
   - c) What happened next?
   - Why: It asks two things at once.
7. A good insight includes…
   - a) Observation, reason, and design implication (correct)
   - b) Only a quote
   - c) Only a statistic
   - Why: It must lead to action.
8. Social desirability bias means…
   - a) People say what sounds acceptable (correct)
   - b) Users are random
   - c) Notes are lost
   - Why: Participants may please the researcher.
9. Generative research is mainly for…
   - a) Discovering needs (correct)
   - b) Checking button color
   - c) Measuring uptime
   - Why: It explores the problem space.
10. Before running a study, you should know…
   - a) The decision it will inform (correct)
   - b) The final UI
   - c) The logo
   - Why: Research should drive decisions.

#### Project: Run 3 mini interviews

1. Choose a topic (e.g. how people order food)
2. Write 5 open questions about past behavior
3. Interview 3 people for 10 minutes each and take notes
4. Group notes into 3 themes and write one persona
5. Write 5 jobs-to-be-done statements from your interview notes
6. Run a 5-question survey with 10 responses and compare it with your interviews
7. Write a discussion guide with warm-up, context, 5 story prompts, and wrap-up
8. Write each insight in the observation, reason, implication format (at least 3)

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 3: Flows & Information Architecture

**Level:** Beginner

#### Lesson

Information architecture (IA) is how content is organized and labeled so people can find it. Use words users already use, not internal jargon.

Card sorting asks people to group topics their own way. Their groups become your navigation. Keep top-level navigation to about 5 items.

A user flow maps the steps from a goal to its completion. Shorter flows with fewer decisions convert better.

**Navigation patterns**

A bottom tab bar suits 3 to 5 equal, frequent destinations on mobile. A hamburger drawer hides items, so use it for secondary links only. A hub-and-spoke layout fits tasks that start from one home. Pick the pattern that matches how often people switch sections.

**Search and labeling**

Offer search when content is large or users know what they want. Support typos, show recent searches, and show helpful empty results. Make labels specific: 'Billing' beats 'Account stuff'.

**Tree testing**

Tree testing shows users only your text hierarchy and asks them to find items. If less than 70% succeed, rename or regroup before drawing any screens. It is the cheapest way to validate IA.

**Findability is the goal**

Users find things through navigation, search, and links. Evaluate findability, not just structure: can people locate X in under a minute without help? Information scent (cues that suggest a link leads to what they want) drives clicks; weak labels lose users.

**Taxonomy and labeling**

Group by user mental models, not org charts. Use consistent, specific, front-loaded labels, avoid overlapping categories, and decide whether items can live in more than one place (tags and facets). Balance breadth and depth: a few clear levels usually beats a deep tree or a giant menu.

**Wayfinding**

Always answer: where am I, where can I go, and how do I get back? Use clear titles, breadcrumbs for deep content, highlighted current location, and predictable placement. Make URLs readable because they are part of the IA.

**Flows in depth**

Map the happy path first, then edge cases: errors, empty states, permissions, offline, and cancel. Mark entry points (search, email, ad) because users rarely start at your home page. A wireflow combines wireframes with flow arrows to show screens and decisions together.

**Task analysis**

Break a goal into steps and count decisions, inputs, and waits. Remove steps, prefill known data, and defer optional work. Measure with task success, time, and drop-off per step.

#### Key takeaways

- Label with the user's words
- Card sorting reveals mental models
- Fewer steps, fewer decisions

#### Quiz

1. Card sorting helps you…
   - a) Pick colors
   - b) Learn how users group content (correct)
   - c) Write code
   - Why: It exposes their mental model.
2. Best navigation labels are…
   - a) Internal team terms
   - b) Words users already use (correct)
   - c) Clever and playful
   - Why: Clarity beats cleverness.
3. A user flow shows…
   - a) Steps from goal to completion (correct)
   - b) Brand voice
   - c) Server load
   - Why: It maps the path to a task.
4. Best use of a bottom tab bar?
   - a) 10 rarely used items
   - b) 3 to 5 frequent destinations (correct)
   - c) Legal links
   - Why: Tabs need to be few and equally important.
5. A tree test checks…
   - a) Colors
   - b) Whether people can find items in your hierarchy (correct)
   - c) Load speed
   - Why: It validates structure without visuals.
6. Information scent refers to…
   - a) Cues that signal where a link leads (correct)
   - b) A smell
   - c) Server logs
   - Why: Strong cues keep users on track.
7. Which labeling approach is best?
   - a) Specific and user-friendly (correct)
   - b) Internal codenames
   - c) Vague and clever
   - Why: Clarity improves findability.
8. Which belongs in a flow after the happy path?
   - a) Error and edge cases (correct)
   - b) Marketing slogans
   - c) Typography
   - Why: Failure paths must be designed.
9. Why do users rarely start at the home page?
   - a) They arrive via search, links, and ads (correct)
   - b) Home pages are illegal
   - c) Browsers hide them
   - Why: Design every entry point.
10. Facets and tags help when…
   - a) Items fit multiple categories (correct)
   - b) Nothing is searchable
   - c) You have one page
   - Why: They support multiple access paths.

#### Project: Map a signup flow

1. Choose a product and one goal (e.g. create an account)
2. Draw every step as boxes and arrows, including errors
3. Remove or merge at least 2 steps
4. Write the final flow in under 6 steps
5. Write your full site map as an indented list
6. Run a tree test with 3 people on 3 find-it tasks
7. Create a full sitemap with 3 levels and test it with a tree test (aim for 80%+ success)
8. Draw a wireflow including 3 error states and 2 entry points

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 4: UX Writing & Content Design

**Level:** Beginner

#### Lesson

**Words are interface**

Every label, error, and empty state is design. Write for the task: say what happens next, in plain verbs and sentence case. 'Save changes' beats 'Submit'.

**Voice and tone**

Voice is the brand's constant personality. Tone shifts with context: calm in errors, upbeat in success. Write a short voice guide with 3 traits and do/don't examples.

**Errors, empty states, microcopy**

An error says what went wrong and how to fix it, without blame or apology. An empty state invites the first action. Keep the same name for an action through the whole flow.

**Content strategy basics**

Start with user tasks, then decide what content supports each. Create a content model (types, fields, relationships), a style guide, and templates so pages stay consistent. Write for scanning: front-load key words, one idea per sentence, short paragraphs.

**Inclusive and global writing**

Use plain language (about grade 8 for broad audiences), avoid idioms and gendered defaults, and leave room for translated text, which can be 30 percent longer. Never use text in images for essential content.

#### Key takeaways

- Plain verbs, sentence case
- Errors explain and fix
- Same action, same name

#### Quiz

1. Best button label?
   - a) Submit
   - b) Save changes (correct)
   - c) OK
   - Why: It states the result.
2. A good error message…
   - a) Blames the user
   - b) Explains the problem and the fix (correct)
   - c) Says 'Error 500'
   - Why: Users need a next step.
3. Tone vs voice?
   - a) Tone is constant
   - b) Voice is constant, tone adapts (correct)
   - c) They are the same
   - Why: Personality stays, mood flexes.
4. Translated text may be…
   - a) Longer, so leave room (correct)
   - b) Always shorter
   - c) Identical
   - Why: Plan for expansion.
5. Write for scanning by…
   - a) Front-loading key words (correct)
   - b) Long paragraphs
   - c) Hidden labels
   - Why: Users skim.

#### Project: Rewrite an app's copy

1. Collect 10 buttons, errors, and empty states from one app
2. Rewrite each with clear verbs and next steps
3. Write a 3-trait voice guide
4. Test the rewrite with 3 people for comprehension
5. Rewrite one screen at plain-language level and test comprehension with 3 people

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 5: Figma & Tool Mastery

**Level:** Beginner

#### Lesson

**Core Figma skills**

Learn frames, auto layout, constraints, components, variants, styles, and variables. Auto layout makes designs resize like real code, and components keep edits consistent across screens.

**Working like a pro**

Name layers, organize pages (Cover, Flows, Components, Archive), use shared libraries, and learn shortcuts. Keep files clean so developers and teammates can navigate them.

**The wider toolkit**

Pair design tools with FigJam or Miro for workshops, Maze or Lookback for testing, Notion for docs, and Jira or Linear for tickets. Tools change, so learn the principles beneath them.

**Systems features**

Variables store color, number, string, and boolean values with modes (light, dark, brand). Components use properties and variants; slots and nested instances keep structure flexible. Use auto layout everywhere so content changes do not break layouts.

**Collaboration habits**

Use branches or version notes for major changes, comment with clear asks, and separate exploration from approved pages. Prepare a ready-for-dev status, annotate behavior, and keep libraries published and versioned.

#### Key takeaways

- Auto layout and components first
- Clean files are a professional habit
- Principles outlive tools

#### Quiz

1. Auto layout helps by…
   - a) Adding color
   - b) Making designs resize like code (correct)
   - c) Exporting video
   - Why: It mirrors responsive behavior.
2. Variants are used for…
   - a) Component states and options (correct)
   - b) Page names
   - c) Fonts
   - Why: They group states in one component.
3. Why name layers?
   - a) Fun
   - b) Handoff and teamwork (correct)
   - c) Required by law
   - Why: Others must understand your file.
4. Variable modes are used for…
   - a) Light, dark, or brand themes (correct)
   - b) Layer names
   - c) Fonts only
   - Why: One value set per theme.
5. Auto layout makes designs…
   - a) Resilient to content changes (correct)
   - b) Slower
   - c) Static
   - Why: It adapts like code.

#### Project: Build a clean UI kit

1. Create a file with Cover, Flows, Components pages
2. Build a button, input, and card with auto layout and variants
3. Define color and text styles or variables
4. Share the file view-only and ask a peer to navigate it
5. Create a variable collection with light and dark modes and apply it to 5 components

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 6: The Pro Tool Landscape

**Level:** Beginner

#### Lesson

**The standard stack**

Most professional teams design and prototype in Figma, run workshops in FigJam or Miro, document in Notion or Confluence, track work in Jira or Linear, and chat in Slack. Learn this core first because job posts name it most.

**Choosing tools**

Pick by job to be done: research, ideation, UI, prototype, handoff, testing, delivery. Prefer tools your team already uses, with good export and collaboration. Start with free plans, and check current features and pricing since they change often.

**Hardware and setup**

A laptop with 16 GB RAM, a second screen if possible, a mouse, and a reliable connection covers most work. Browser-based tools like Figma also run on tablets and phones for review.

**Workflow, not features**

Map your project from brief to handoff and name the output each stage produces. Standardize file naming, version notes, and review steps. Fewer, well-known tools used consistently beat a pile of half-learned ones.

**Evaluate a new tool**

Test it on a real task, time yourself, check export options, collaboration, accessibility, security, and cost over a year. Decide with a simple scorecard and set a review date.

#### Key takeaways

- Learn the standard stack first
- Choose by job, not hype
- Check current pricing and features

#### Quiz

1. Most-used UI tool in industry?
   - a) Figma (correct)
   - b) Notepad
   - c) Excel
   - Why: Figma dominates product design teams.
2. Choose tools by…
   - a) Popularity only
   - b) The job to be done (correct)
   - c) Logo color
   - Why: Fit beats hype.
3. Before paying for a tool…
   - a) Try the free plan (correct)
   - b) Buy annual immediately
   - c) Skip evaluation
   - Why: Test fit first.
4. A tool scorecard should include…
   - a) Export, collaboration, cost, security (correct)
   - b) Only logo
   - c) Only price
   - Why: Evaluate fit and risk.
5. Best tool habit?
   - a) Use a few consistently (correct)
   - b) Try all
   - c) Never learn shortcuts
   - Why: Depth beats breadth.

#### Project: Assemble your starter stack

1. List the 7 jobs in your workflow
2. Pick one tool per job
3. Create free accounts and log in on your devices
4. Complete one tiny project using the whole stack
5. Create a tool scorecard and test 2 tools on one real task

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 7: Free Design & Prototyping Tools

**Level:** Beginner

#### Lesson

**Figma and FigJam free**

Figma's Starter plan is free with no trial clock and no card, and works in a browser or the desktop and mobile apps. It limits team size, files, and version history, but it is enough to learn and to build a portfolio. Figma does not offer a free trial of its paid plan, so rely on Starter or the Education plan.

**Free alternatives**

Penpot is an open-source design and prototyping tool close to Figma and free to use. Canva has a free tier for graphics and social assets. Excalidraw and tldraw cover quick sketches and diagrams. Photopea runs a Photoshop-like editor in the browser.

**Free creative software**

Inkscape (vector), GIMP and Krita (images and painting), Blender (3D and animation), and Affinity (check current pricing, as Canva has made major changes to it) cover illustration, editing, and 3D without a subscription. Always verify a tool's current free terms on its official site.

#### Key takeaways

- Figma Starter is free forever, with limits
- Penpot is a strong open-source alternative
- Verify free terms on official pages

#### Quiz

1. Does Figma offer a free trial of its paid plan?
   - a) Yes, 30 days
   - b) No, use Starter or Education instead (correct)
   - c) Only on Android
   - Why: Starter is free permanently; Education is free for eligible learners.
2. Penpot is…
   - a) An open-source design tool (correct)
   - b) A paid-only plugin
   - c) A video editor
   - Why: It is free and open source.
3. Blender is used for…
   - a) 3D and animation (correct)
   - b) Accounting
   - c) Email
   - Why: It is a free 3D suite.

#### Project: Build a zero-cost design setup

1. Create a free Figma Starter account and a Penpot account
2. Rebuild one screen in both and compare workflows
3. Install or open Inkscape or Photopea and make one icon
4. Write a one-page summary of what each free tool does best

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 8: Student, Educator & Bootcamp Perks

**Level:** Beginner

#### Lesson

**Figma Education**

Verified students, educators, and bootcamp learners can get Figma's Professional features free through the Education plan, which is intended for learning and not professional work. Eligibility needs school or program verification and it renews: roughly two years for K-12 and higher education and six months for bootcamps. If verification lapses your account drops to Starter and your files stay.

**GitHub Student Developer Pack**

This pack bundles 100+ partner offers (tools, credits, and courses) for verified students, and verification lasts about two years before rechecks. Offers change often: in 2026, reports say GitHub paused new Copilot student sign-ups and a cloud credit partner left the pack. Claim useful offers promptly and read each partner's terms.

**More education discounts**

Check JetBrains educational licenses, Canva for Education, Notion's education plan, Google Workspace for Education, and Microsoft Education offers. Use your school email, and ask your institution or program which licenses it already pays for.

#### Key takeaways

- Education plans are for learning, not client work
- Pack offers change, claim early
- Always check your school's existing licenses

#### Quiz

1. Figma Education is meant for…
   - a) Learning, not professional work (correct)
   - b) Client work only
   - c) Anyone, no verification
   - Why: The plan is for educational use.
2. If Figma education verification lapses…
   - a) Files are deleted
   - b) You move to Starter and keep files (correct)
   - c) Account is banned
   - Why: You keep your work on the free plan.
3. GitHub Student Pack offers…
   - a) Never change
   - b) Change, so verify current terms (correct)
   - c) Are lifetime
   - Why: Perks and credits vary over time.

#### Project: Claim every perk you qualify for

1. List your school or program and your verified email
2. Apply for Figma Education and the GitHub Student Developer Pack
3. Check 5 more education discounts on official sites
4. Make a spreadsheet of each perk with expiry and renewal dates

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 9: Free Assets & Learning Resources

**Level:** Beginner

#### Lesson

**Free assets**

Google Fonts and Font Squirrel offer open-licensed fonts. Lucide, Phosphor, and Heroicons provide open-source icons. Unsplash and Pexels offer free photos, and unDraw offers illustrations. Always read each license and credit when required.

**Free learning**

Use official docs and tutorials: Figma's learning resources and community files, web.dev, MDN, Google's Material Design guidelines, Apple's Human Interface Guidelines, and the W3C WAI pages. Many universities and platforms offer free or audit-mode courses.

**Community**

Join design communities, critique groups, and open-source projects such as Penpot to practice with real teams. Contributing to open source is portfolio-worthy evidence of collaboration.

#### Key takeaways

- Check licenses on every asset
- Official docs are the best free curriculum
- Open-source contribution builds a portfolio

#### Quiz

1. Before using a free image…
   - a) Read its license (correct)
   - b) Assume it is public domain
   - c) Ignore credit
   - Why: Terms vary by source.
2. Best free reference for web accessibility?
   - a) W3C WAI (correct)
   - b) A random blog
   - c) None
   - Why: WAI is the official source.
3. Open-source work shows…
   - a) Collaboration skills (correct)
   - b) Nothing
   - c) Only coding
   - Why: It proves you work with others.

#### Project: Build a free asset library

1. Choose 2 fonts and 1 icon set from open-licensed sources
2. Save 10 free photos with licenses recorded
3. Bookmark 10 official docs and tutorials
4. Complete one free course or tutorial and publish notes

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 10: Open Source Design Tools

**Level:** Beginner

#### Lesson

**UI and prototyping**

Penpot is an open-source (MPL-2.0) design and prototyping platform built on web standards like SVG and CSS, with free cloud use, self-hosting, native design tokens, CSS flex and grid layout, and an inspect mode for developers. Excalidraw and tldraw give quick whiteboard sketching, and diagrams.net (draw.io) handles flows and diagrams. Mermaid turns text into diagrams.

**Graphics and media**

Inkscape does vector graphics and icons. GIMP edits photos and Krita is built for digital painting. Scribus lays out print documents. Blender covers 3D, animation, and rendering, and Kdenlive or OBS Studio handle video editing and screen recording.

**Why choose open source**

You get no license cost, files in open formats, a community, and the freedom to inspect or modify the tool. The trade-offs can be a steeper learning curve and fewer polished plugins, so test with a real project first.

#### Key takeaways

- Penpot, Inkscape, GIMP, Krita, Blender cover most design work
- Open formats keep your files portable
- Test fit with a real project

#### Quiz

1. Which is open-source UI design?
   - a) Penpot (correct)
   - b) Photoshop
   - c) Sketch
   - Why: Penpot is open source and web-standard based.
2. Krita is made for…
   - a) Digital painting (correct)
   - b) Accounting
   - c) Coding
   - Why: It is an open-source painting app.
3. An open-source trade-off may be…
   - a) A steeper learning curve (correct)
   - b) Mandatory fees
   - c) No community
   - Why: Polish and plugins vary.

#### Project: Make a project with only open-source tools

1. Sketch a flow in Excalidraw or diagrams.net
2. Design 3 screens in Penpot
3. Create an icon in Inkscape and a graphic in GIMP or Krita
4. Export everything in open formats (SVG, PNG, PDF) and note what was harder than expected

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 11: Design Fundamentals: Gestalt, Color, Type, Composition

**Level:** Beginner

#### Lesson

**Gestalt principles**

People perceive wholes before parts. Proximity groups near items, similarity groups alike items, continuity follows paths, closure completes shapes, figure and ground separates subject from background, and common region groups items inside a boundary. Use these before adding borders or labels.

**Color theory**

Hue is the color family, saturation is intensity, and value is lightness. Value contrast carries legibility; hue carries mood and meaning. Build palettes from a neutral ramp plus one accent, test them in grayscale, and remember meaning varies by culture.

**Typography and composition**

Type has structure: x-height, ascenders, leading, tracking, and kerning. Use a modular scale, align to a baseline, and keep one dominant element per view. Use contrast, repetition, alignment, and proximity (CRAP) as a layout check, and treat whitespace as an active shape.

**Testing hierarchy**

Squint test: blur your screen; the most important element should still stand out. Rank elements 1, 2, 3 and check that size, weight, color, and position match the ranking. If three things compete for first place, nothing wins.

**Contrast rules you can measure**

WCAG sets minimum contrast for text at 4.5:1 (3:1 for large text) and 3:1 for UI components and graphics. AAA asks 7:1 for text. Check every text and background pair, including disabled and hover states, and never rely on color alone.

**Color harmony**

Analogous colors sit next to each other on the wheel (calm), complementary colors sit opposite (energetic), and triadic colors are evenly spaced. Use 60-30-10 as a start: dominant neutral, secondary, small accent. Define semantic roles (success, warning, error) separately from brand.

**Type in depth**

Choose a text face for readability at small sizes and optionally a display face for personality. Line height 1.4 to 1.6 for body, tighter for headings; limit line length to 45 to 75 characters; align left for most reading. Use real hierarchy tokens (title, heading, body, caption) instead of arbitrary sizes.

**Layout, balance, rhythm**

Grids create order; baseline alignment makes rhythm. Balance can be symmetric (formal) or asymmetric (dynamic). Repeat spacing values so the page feels consistent, and use white space to group (macro) and to separate lines or letters (micro).

#### Key takeaways

- Gestalt explains grouping without lines
- Value contrast makes text readable
- One dominant element per view

#### Quiz

1. Proximity means…
   - a) Near items read as a group (correct)
   - b) Same-color items group
   - c) Big items win
   - Why: Nearness signals relationship.
2. Legibility depends mostly on…
   - a) Value contrast (correct)
   - b) Hue
   - c) Saturation only
   - Why: Light versus dark difference drives reading.
3. A modular scale gives…
   - a) Related type sizes (correct)
   - b) Random sizes
   - c) More fonts
   - Why: Sizes share a ratio.
4. Minimum contrast for normal text (WCAG AA)?
   - a) 4.5:1 (correct)
   - b) 2:1
   - c) 10:1
   - Why: Large text can use 3:1.
5. Minimum contrast for UI components?
   - a) 3:1 (correct)
   - b) 1:1
   - c) 7:1
   - Why: Controls and icons need 3:1.
6. Squint test checks…
   - a) Visual hierarchy (correct)
   - b) Spelling
   - c) Download speed
   - Why: Blur reveals what stands out.
7. Complementary colors are…
   - a) Opposite on the wheel (correct)
   - b) Adjacent
   - c) Identical
   - Why: They create strong contrast.
8. Good body line height is about…
   - a) 1.4 to 1.6 (correct)
   - b) 0.8
   - c) 3
   - Why: Comfortable reading needs space.

#### Project: Apply fundamentals to a poster

1. Design a one-page poster using only proximity and alignment for grouping
2. Pick a palette and test it in grayscale
3. Set a type scale with 4 sizes
4. Critique it with CRAP and revise once
5. Run a squint test on 3 screens and fix hierarchy ties
6. Test every color pair in your palette for 4.5:1 and 3:1 where required and record results

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 12: Learning How to Learn

**Level:** Beginner

#### Lesson

**What the evidence supports**

Retrieval practice (testing yourself) beats rereading. Spaced repetition revisits ideas at growing intervals. Interleaving mixes related skills instead of blocking them. Deliberate practice means working at the edge of ability with specific goals and fast feedback.

**The Feynman and build loop**

Explain a concept in plain words as if teaching a beginner; wherever you stall, you have a gap. Then build something with it. Learning sticks when you produce, not just consume.

**A learning system**

Keep a learning log of what you studied, what you built, what confused you, and what to review. Use flashcards for vocabulary and heuristics, schedule reviews, and set a weekly project. Teach, write, or present what you learn.

**Plan the practice**

Pick one skill per week and define a measurable output (for example, 'rebuild a checkout flow with 3 states'). Practice at the edge of your ability, get feedback within a day, then repeat. Mix easy wins with stretch tasks to stay motivated.

**Avoid illusions of learning**

Rereading and watching tutorials feel productive but build little. Close the video and reproduce the result from memory. Teach it aloud in plain language; stalls mark gaps. Review at 1, 3, 7, and 21 days.

#### Key takeaways

- Test yourself more than you reread
- Space and interleave practice
- Build and teach to retain

#### Quiz

1. Which beats rereading?
   - a) Retrieval practice (correct)
   - b) Highlighting
   - c) Skimming
   - Why: Active recall strengthens memory.
2. Deliberate practice needs…
   - a) Specific goals and feedback (correct)
   - b) Long hours alone
   - c) Passive viewing
   - Why: It targets weaknesses.
3. Interleaving means…
   - a) Mixing related skills (correct)
   - b) One skill only
   - c) Skipping review
   - Why: It improves transfer.
4. Which builds memory best?
   - a) Reproducing from memory (correct)
   - b) Rewatching tutorials
   - c) Highlighting
   - Why: Retrieval strengthens recall.
5. A measurable weekly output is…
   - a) Rebuild a flow with 3 states (correct)
   - b) Learn more about design
   - c) Watch 5 videos
   - Why: Specific outputs create feedback.

#### Project: Set up your learning system

1. Create a learning log with date, topic, build, and confusion
2. Make 30 flashcards from the heuristics and principles you learned
3. Schedule review days (1, 3, 7, 21)
4. Teach one module to a friend or in a short post
5. Plan 4 weeks of practice with one measurable output per week

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 13: Wireframing

**Level:** Intermediate

#### Lesson

A wireframe is a low-fidelity layout that shows structure and priority without color or imagery. Grey boxes force you to fix hierarchy first.

Start with sketches on paper, then move to digital. Design mobile first: a small screen forces you to keep only what matters.

Use real content. 'Lorem ipsum' hides problems like long names or empty states.

**Layout and grids**

Use a column grid (4 columns on mobile, 12 on desktop) so elements align. Group related items closer together than unrelated ones (proximity). Leave generous margins; whitespace is a tool, not waste.

**Common patterns**

Lists show scannable items. Cards bundle a topic with an action. Forms collect input. Dashboards summarize status. Choose the pattern from the user's task: compare, browse, enter data, or monitor.

**Form best practices**

Use one column, put labels above fields, mark optional fields, validate inline after the user leaves a field, and make error messages say how to fix the problem. Ask only for what you need.

**Fidelity ladder**

Sketches explore options fast. Low-fidelity wireframes test structure and content priority. Mid-fidelity adds real copy and components. Hi-fi tests visuals and motion. Move up only when the lower level stops answering your questions.

**Content-first**

Start with the content hierarchy: what must users see first, second, third? Write real headlines and labels. Lorem ipsum hides length and tone problems and delays decisions.

**State inventory**

Each screen has states: loading, empty, partial, error, success, offline, and permission-denied. List them for every screen and wireframe the important ones, since most bugs and support issues live there.

**Responsive and component thinking**

Wireframe at least small and large breakpoints and note how components reflow (stack, hide, collapse). Reuse components so patterns stay consistent and developers can build once.

**Annotating and reviewing**

Add short annotations: purpose, rules, data source, and edge cases. When reviewing with stakeholders, state what feedback you want ('structure and priority, not color') and review against the user's task and heuristics.

#### Key takeaways

- Structure before style
- Mobile first forces priority
- Use real content, include empty and error states

#### Quiz

1. Why use grey boxes?
   - a) Cheaper to print
   - b) Focus on structure, not decoration (correct)
   - c) Clients like grey
   - Why: Style distracts from layout decisions.
2. Mobile first means…
   - a) Design the small screen first (correct)
   - b) Skip desktop
   - c) Use only apps
   - Why: Constraints drive priority.
3. Why avoid lorem ipsum?
   - a) It is illegal
   - b) It hides real content problems (correct)
   - c) It loads slowly
   - Why: Real text exposes layout breaks.
4. Where should form labels go?
   - a) Inside as placeholder only
   - b) Above the field (correct)
   - c) Far to the right
   - Why: Persistent labels stay readable while typing.
5. Proximity means…
   - a) Related items are placed close together (correct)
   - b) Everything is centered
   - c) Use more colors
   - Why: Closeness signals relationship.
6. A state inventory lists…
   - a) Loading, empty, error, success, and other states (correct)
   - b) Team members
   - c) Fonts
   - Why: It prevents missing states.
7. Why avoid lorem ipsum?
   - a) It hides content problems (correct)
   - b) It is slow
   - c) It is copyrighted
   - Why: Real content reveals real issues.
8. Annotations should record…
   - a) Purpose, rules, data, edge cases (correct)
   - b) Only colors
   - c) Nothing
   - Why: They guide build and review.
9. Move to higher fidelity when…
   - a) Lower fidelity stops answering questions (correct)
   - b) The client asks
   - c) You like color
   - Why: Fidelity follows learning needs.
10. Wireframe review should focus on…
   - a) Structure and priority (correct)
   - b) Brand colors
   - c) Logo size
   - Why: Direct feedback to the right level.

#### Project: Wireframe a home screen

1. Pick an app idea and list its top 3 user tasks
2. Sketch 3 versions of the home screen on paper
3. Pick the best one and redraw it with real text
4. Add an empty state and an error state
5. Wireframe a signup form following the form rules
6. Annotate your wireframe with the grid and spacing you used
7. Create a state inventory for 3 screens and wireframe the key empty and error states
8. Wireframe small and large breakpoints and annotate reflow rules

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 14: Visual Design Basics

**Level:** Intermediate

#### Lesson

Hierarchy tells the eye where to look first. Create it with size, weight, color, contrast and spacing. If everything is bold, nothing is.

Pick one or two typefaces. Use a type scale (for example 14, 16, 20, 28, 40). Body text should sit at 16px or larger with line height around 1.5.

Use an 8px spacing grid. Limit color to a base, one accent, and states (success, error). Contrast between text and background must reach 4.5:1.

**Color in a system**

Build a palette from a base neutral scale (5 to 9 steps), one brand accent, and semantic colors for success, warning, error, and info. Test every pair for contrast. Dark mode needs its own tuned values, not just inverted ones.

**Typography details**

Limit line length to 45 to 75 characters. Use a ratio scale (1.25 works well) so sizes feel related. Pair a distinctive display face with a readable text face, and keep weights to three at most.

**Spacing, icons and imagery**

Use consistent icon style and stroke width. Crop images to guide attention toward the content. Use spacing multiples of 8 so rhythm stays predictable across screens.

**Systems over styling**

Define styles once and reuse: type, color, spacing, radius, shadow, and elevation. Choose a corner radius and stroke weight philosophy that fits the brand (sharp for precision, round for friendliness) and stay consistent.

**Imagery, icons, motion**

Use imagery that supports the message, with consistent crop and tone. Keep icon grids, stroke widths, and metaphors consistent and pair icons with labels when meaning is unclear. Test dark mode and high-contrast variants early.

#### Key takeaways

- Hierarchy: size, weight, color, space
- Type scale + 8px spacing grid
- Text contrast at least 4.5:1

#### Quiz

1. Minimum text contrast ratio (WCAG AA)?
   - a) 2:1
   - b) 3:1
   - c) 4.5:1 (correct)
   - Why: 4.5:1 for normal text.
2. How many typefaces for most apps?
   - a) One or two (correct)
   - b) Five
   - c) As many as fit
   - Why: Fewer is more consistent.
3. What creates hierarchy?
   - a) Only color
   - b) Size, weight, contrast, spacing (correct)
   - c) Animation
   - Why: Many levers work together.
4. A healthy body text line length is…
   - a) 20 characters
   - b) 45 to 75 characters (correct)
   - c) 150 characters
   - Why: Long lines tire the eye.
5. Semantic colors are used for…
   - a) Decoration
   - b) Meaning such as success and error (correct)
   - c) Logos
   - Why: They communicate state.
6. Why define styles once?
   - a) Consistency and speed (correct)
   - b) Fewer colors only
   - c) Marketing
   - Why: Reuse prevents drift.
7. Icons with unclear meaning should…
   - a) Have text labels (correct)
   - b) Be larger
   - c) Be animated
   - Why: Labels remove ambiguity.

#### Project: Style your wireframe

1. Choose 1 typeface and a 4-step type scale
2. Pick a base, an accent, and success/error colors
3. Apply them to your wireframe from the previous module
4. Check text contrast with a free contrast checker
5. Create a light and a dark palette and check contrast on both
6. Redesign one screen twice with a different hierarchy and compare
7. Define radius, stroke, and shadow rules and apply them to 5 components

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 15: Interaction & Prototyping

**Level:** Intermediate

#### Lesson

Interaction design covers how a product responds: taps, swipes, loading, feedback. Every action needs a visible reaction within 100 ms.

Microinteractions (a toggle sliding, a button confirming) show what changed. Use motion to explain, not to decorate. Keep it under 300 ms and respect reduced-motion settings.

A prototype links screens so you can test flows before building. Use Figma or similar tools. Prototype only what you need to test.

**Gestures and Fitts's law**

Fitts's law says bigger and closer targets are faster to hit. Put primary actions within thumb reach at the bottom of mobile screens. Provide a visible alternative to every gesture, such as a button next to swipe-to-delete.

**Feedback and states**

Design every state: default, hover, focus, pressed, loading, success, empty, and error. Use skeleton screens for loads over one second, and use optimistic updates for quick actions. Let users undo instead of asking 'Are you sure?'.

**Fidelity levels**

Paper tests flow. Clickable wireframes test navigation. High-fidelity prototypes test visual and motion details. Move up in fidelity only when the lower level stops answering your questions.

**Model the states**

Treat every control as a small state machine: idle, hover or focus, pressed, loading, success, error, disabled. Define transitions between them and what the user sees and hears at each. Missing states are the top source of bugs.

**Timing and easing**

Use 100 to 200 ms for small feedback, 200 to 300 ms for panels, and ease-out for entering and ease-in for leaving. Avoid motion that delays tasks, and honor the reduced-motion setting by swapping movement for fades or instant changes.

#### Key takeaways

- Always give feedback within ~100 ms
- Motion explains change, stays short
- Prototype just enough to test

#### Quiz

1. Good motion is…
   - a) Long and flashy
   - b) Short and meaningful (correct)
   - c) Always looping
   - Why: Under 300 ms, tied to a user action.
2. Why prototype?
   - a) To impress clients
   - b) To test a flow before building (correct)
   - c) To avoid research
   - Why: Cheap to change before code.
3. A loading state should…
   - a) Show nothing
   - b) Show progress or feedback (correct)
   - c) Block all input silently
   - Why: Silence feels broken.
4. Fitts's law suggests primary actions should be…
   - a) Small and hidden
   - b) Large and easy to reach (correct)
   - c) Only in menus
   - Why: Target size and distance drive speed.
5. Better than a confirm dialog?
   - a) Undo (correct)
   - b) Hiding the action
   - c) Longer text
   - Why: Undo preserves speed and safety.
6. Entering elements usually use…
   - a) Ease-out (correct)
   - b) Linear forever
   - c) No timing
   - Why: Ease-out feels responsive.
7. Reduced-motion users should get…
   - a) Less or no movement (correct)
   - b) More animation
   - c) Same animation
   - Why: Respect system settings.

#### Project: Prototype one flow

1. Choose the flow from module 3
2. Build 4 to 6 screens in Figma or on paper
3. Link them with tap interactions
4. Add one microinteraction (like a button confirmation)
5. Design all 8 states for one component
6. Add an undo option to a destructive action in your prototype
7. Draw a state diagram for one control with all 7 states and transitions

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 16: Mobile, Responsive & Platform Design

**Level:** Intermediate

#### Lesson

**Responsive systems**

Design breakpoints around content, not devices: commonly 360, 768, 1024, 1440 px. Use fluid grids, flexible images, and relative units. Test on real phones and with text zoom.

**Platform conventions**

iOS Human Interface Guidelines and Material Design set expectations for navigation, gestures, and controls. Follow platform norms unless you have strong evidence to break them.

**Touch and context**

Design for one hand, glare, interruptions, and slow networks. Keep thumb-zone actions low, load key content first, and make offline states clear.

**Layout across sizes**

Use fluid grids with min and max widths, let content wrap, and set breakpoints where the design breaks. Keep tap targets at least 44px with spacing, respect safe areas around notches and home indicators, and prefer one-handed reachability for primary actions.

**Performance as design**

Slow pages lose users. Compress images, lazy-load below the fold, ship system or subset fonts, and design skeleton and offline states. Test on a mid-range phone and a throttled network, not only your flagship device.

#### Key takeaways

- Breakpoints follow content
- Respect platform conventions
- Design for thumbs and weak networks

#### Quiz

1. Breakpoints should follow…
   - a) Popular phones
   - b) Where content breaks (correct)
   - c) Marketing dates
   - Why: Content decides, devices change.
2. Primary mobile actions belong…
   - a) Top corner
   - b) Within thumb reach (correct)
   - c) Hidden in menus
   - Why: Reachability matters.
3. Why follow platform guidelines?
   - a) Users already know them (correct)
   - b) They are required by law
   - c) Faster rendering
   - Why: Familiarity reduces learning.
4. Breakpoints should be set…
   - a) Where the layout breaks (correct)
   - b) At device model names
   - c) Randomly
   - Why: Content decides.
5. Why test on throttled networks?
   - a) Real users have slow connections (correct)
   - b) It is required by law
   - c) Faster builds
   - Why: Performance is part of UX.

#### Project: Make one flow work everywhere

1. Design your flow at 360, 768, and 1280 px
2. Create iOS and Android variants of navigation
3. Test on a real phone with large text enabled
4. List 3 offline or slow-network states and design them
5. Test your prototype on a mid-range phone with a throttled connection and list 3 fixes

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 17: Psychology & Behavior

**Level:** Intermediate

#### Lesson

**Laws that guide layout**

Hick's law: more choices slow decisions. Miller's range: working memory holds about 4 to 7 chunks. Jakob's law: users expect your product to work like others they use. Doherty threshold: respond within about 400 ms.

**Biases and nudges**

Defaults, social proof, and loss aversion shape behavior. Use them to help users reach goals, never to trap them. Dark patterns such as hidden cancellation erode trust and invite regulation.

**Cognitive load**

Reduce load by chunking, progressive disclosure, and clear hierarchy. Show advanced options only when needed.

**Attention and memory**

People scan in patterns (F and Z), notice contrast and motion, and miss things outside their goal (inattentional blindness). Working memory is small, so chunk information, use recognition over recall, and reduce competing elements.

**Motivation and habit**

Fogg's model says behavior needs motivation, ability, and a prompt. Make the action easier before trying to raise motivation. Use progress, feedback, and meaningful defaults, and never exploit loss aversion or streak anxiety against users' interests.

#### Key takeaways

- Fewer choices, faster decisions
- Defaults are powerful, use ethically
- Reveal complexity progressively

#### Quiz

1. Hick's law says…
   - a) More choices slow decisions (correct)
   - b) Bigger buttons are faster
   - c) Users read everything
   - Why: Choice count increases decision time.
2. A dark pattern is…
   - a) A dark theme
   - b) A deceptive design that works against users (correct)
   - c) A gray button
   - Why: It tricks people.
3. Progressive disclosure…
   - a) Shows everything at once
   - b) Reveals details as needed (correct)
   - c) Hides all options
   - Why: It manages load.
4. Behavior requires…
   - a) Motivation, ability, and a prompt (correct)
   - b) Only motivation
   - c) Only reminders
   - Why: Fogg's model.
5. Working memory is…
   - a) Limited, so chunk information (correct)
   - b) Unlimited
   - c) Irrelevant
   - Why: Reduce load.

#### Project: Reduce load in a complex screen

1. Pick a crowded screen and count its choices
2. Remove or group at least half using chunking
3. Move advanced options behind progressive disclosure
4. Test the new version against the old with 3 users
5. Redesign one task to be easier (ability) and write what prompt triggers it

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 18: HTML & CSS for Designers

**Level:** Intermediate

#### Lesson

**Why designers code**

Knowing the basics lets you design what can be built, prototype in the browser, and talk to engineers with respect. You do not need to be a developer.

**Core concepts**

HTML gives structure: headings, lists, buttons, inputs, landmarks. CSS gives style: the box model (content, padding, border, margin), flexbox for rows and columns, grid for two-dimensional layout, and media queries for responsiveness.

**Semantic and accessible**

Use real buttons and links, not clickable divs. Use label elements for inputs and heading order for structure. Semantic HTML gives accessibility for free.

**Layout in practice**

Use flexbox for one-dimensional rows and columns and grid for two-dimensional layouts. Use relative units (rem, %, clamp()) so type and spacing scale, and set a max-width for readable line length. Prefer CSS variables for tokens.

**Debugging with DevTools**

Inspect an element, read the box model, toggle styles, and check computed values. Resize to find breakpoints, emulate devices and slow networks, and run Lighthouse for accessibility and performance hints.

#### Key takeaways

- Learn structure, box model, flex, grid
- Design within what the web can do
- Semantic HTML is accessible HTML

#### Quiz

1. Box model order from inside out?
   - a) Margin, border, padding, content
   - b) Content, padding, border, margin (correct)
   - c) Border, content, margin, padding
   - Why: Content sits inside padding, then border, then margin.
2. Flexbox is best for…
   - a) One-dimensional layouts (correct)
   - b) 3D
   - c) Databases
   - Why: It arranges items in a row or column.
3. Why use a real button element?
   - a) It looks better
   - b) Built-in keyboard and screen-reader support (correct)
   - c) It is faster to type
   - Why: Native elements bring accessibility.
4. Grid is best for…
   - a) Two-dimensional layout (correct)
   - b) Fonts
   - c) Databases
   - Why: Rows and columns together.
5. CSS variables store…
   - a) Tokens such as colors and spacing (correct)
   - b) Images only
   - c) Servers
   - Why: They carry design decisions.

#### Project: Code your own page

1. Write semantic HTML for a landing page
2. Style it with CSS variables for your tokens
3. Make it responsive with flexbox and one media query
4. Run an automated accessibility check and fix issues
5. Build a responsive card grid using CSS variables and verify it in DevTools at 3 sizes

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 19: Graphics, Motion & 3D Tools

**Level:** Intermediate

#### Lesson

**Vector and image**

Illustrator and Affinity Designer handle vectors and icons. Photoshop and Affinity Photo handle photo editing. Figma covers most UI vectors, so learn the others for brand, illustration, and asset work.

**Motion**

After Effects creates polished animation, exported to the web with Lottie. Rive builds interactive, state-driven animations. Principle and Figma Smart Animate handle quick UI motion.

**3D and web-interactive**

Spline and Blender create 3D scenes; Spline publishes to the web. Use 3D and motion sparingly and with reduced-motion fallbacks and small file sizes.

#### Key takeaways

- Vectors for icons and brand
- Lottie and Rive for app motion
- Use 3D sparingly, performance first

#### Quiz

1. Lottie is…
   - a) A JSON-based animation format (correct)
   - b) A font
   - c) A server
   - Why: It plays After Effects animations on the web and apps.
2. Rive is good for…
   - a) Interactive state-driven animation (correct)
   - b) Accounting
   - c) Photos
   - Why: It supports interactive states.
3. Heavy 3D needs…
   - a) Performance checks and fallbacks (correct)
   - b) Nothing
   - c) More shadows
   - Why: Speed and accessibility matter.

#### Project: Make a motion asset

1. Design an icon in a vector tool
2. Animate it for 1 to 2 seconds
3. Export it as Lottie or Rive and check file size
4. Add a reduced-motion fallback

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 20: Prototyping & Interaction Tools

**Level:** Intermediate

#### Lesson

**Figma prototyping**

Connect frames with triggers (tap, hover, drag), use Smart Animate for transitions, variables and conditionals for logic, and share links for testing on a phone with Figma Mirror or the mobile app.

**Advanced tools**

ProtoPie handles sensors, device inputs, and complex logic. Framer builds responsive, publishable sites and prototypes with real components. Origami and Principle are used in some teams. Code prototypes in HTML/CSS/JS are the highest fidelity.

**Pick the fidelity**

Test flow with a clickable Figma, test feel with ProtoPie or code, and test content with real data. Match tool to the question.

#### Key takeaways

- Smart Animate and variables in Figma
- ProtoPie for sensors and logic
- Match fidelity to the question

#### Quiz

1. For sensor and device input prototypes?
   - a) ProtoPie (correct)
   - b) Word
   - c) Calendar
   - Why: It supports device inputs and logic.
2. Framer is known for…
   - a) Publishable responsive sites and prototypes (correct)
   - b) Accounting
   - c) Photo editing
   - Why: It builds live sites.
3. Best fidelity?
   - a) Always the highest
   - b) The one that answers your question (correct)
   - c) Always paper
   - Why: Do not overbuild.

#### Project: Prototype at two fidelities

1. Build a clickable flow in Figma
2. Add variables and conditional logic
3. Rebuild the key interaction in ProtoPie, Framer, or code
4. Test both on a real phone and compare findings

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 21: Research & Testing Tools

**Level:** Intermediate

#### Lesson

**Moderated and unmoderated**

Zoom, Lookback, and UserTesting support moderated sessions and recruiting. Maze, Useberry, and Lyssna run unmoderated prototype tests and surveys at scale.

**Analytics and behavior**

Google Analytics and Mixpanel or Amplitude track funnels and cohorts. Hotjar, FullStory, and Microsoft Clarity add heatmaps and session replay. Respect privacy and consent.

**Synthesis and IA**

Dovetail and Notion store and tag research. Optimal Workshop runs card sorts and tree tests. Keep a searchable repository so insights outlive projects.

#### Key takeaways

- Moderated for why, unmoderated for scale
- Replay and heatmaps show behavior
- Keep a research repository

#### Quiz

1. Tree testing tool?
   - a) Optimal Workshop (correct)
   - b) Photoshop
   - c) Slack
   - Why: It supports card sorts and tree tests.
2. Heatmaps show…
   - a) Where users click and scroll (correct)
   - b) Server cost
   - c) Brand color
   - Why: They reveal behavior patterns.
3. Session recordings require…
   - a) Consent and privacy care (correct)
   - b) Nothing
   - c) Hidden collection
   - Why: Protect users.

#### Project: Run a tool-based study

1. Set up an unmoderated test in Maze or similar
2. Recruit 8 participants
3. Run a tree test or card sort in Optimal Workshop
4. Store findings in a tagged repository

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 22: Free Dev, Hosting & Android-Friendly Tools

**Level:** Intermediate

#### Lesson

**Code and version control**

VS Code, Git, and GitHub are free for most use. GitHub Pages hosts static sites free. Netlify, Vercel, and Cloudflare Pages offer free tiers for small sites, subject to usage limits you should check.

**Working from Android**

Figma and Penpot run in a mobile browser for review and light edits. In Termux you can install git, Node.js, and a simple web server to code and preview HTML/CSS prototypes, then push to GitHub Pages. Pair a keyboard and a browser for the best experience.

**Free quality tools**

Chrome DevTools and Lighthouse are free in the browser. The WAVE and axe browser extensions check accessibility. WebAIM's contrast checker is free. Microsoft Clarity and Google Analytics offer free analytics, and you must follow privacy rules.

#### Key takeaways

- GitHub Pages hosts static sites free
- Termux + git + a web server can prototype on Android
- Free audit tools exist for accessibility and performance

#### Quiz

1. GitHub Pages hosts…
   - a) Static sites (correct)
   - b) Only databases
   - c) Only video
   - Why: It serves HTML, CSS, and JS.
2. Which tool checks contrast free?
   - a) WebAIM contrast checker (correct)
   - b) Spreadsheet
   - c) Calendar
   - Why: It is free and widely used.
3. Termux lets you…
   - a) Run a Linux-style terminal on Android (correct)
   - b) Print documents
   - c) Edit video only
   - Why: It supports git and a local server.

#### Project: Ship a free prototype from your phone

1. Create a GitHub account and a repository
2. In Termux, install git and a simple server and edit an HTML page
3. Push to GitHub and enable GitHub Pages
4. Run Lighthouse and WAVE on the live URL

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 23: Open Source Dev, Components & Design Systems

**Level:** Intermediate

#### Lesson

**Core web stack**

Git, Node.js, and an editor such as VS Code (built on the open-source Code-OSS) or VSCodium are open or open-core. HTML, CSS, JavaScript, and frameworks like React, Svelte, and Vue are open source. Vite and similar tools give fast local builds.

**Component and token libraries**

Tailwind CSS provides utility classes. Radix UI and React Aria supply accessible unstyled components. shadcn/ui copies well-made components into your project. Style Dictionary transforms design tokens into CSS, iOS, and Android values. Storybook documents and tests components.

**Icons, fonts, and animation**

Lucide, Phosphor, and Heroicons are open icon sets. Google Fonts hosts many open fonts (often OFL licensed), such as Inter. Lottie player libraries and Rive runtimes render animations in apps.

#### Key takeaways

- Prefer accessible unstyled primitives
- Tokens + Style Dictionary scale across platforms
- Check each package's license

#### Quiz

1. Storybook is for…
   - a) Documenting and testing components (correct)
   - b) Photo editing
   - c) Billing
   - Why: It shows components in isolation.
2. Style Dictionary helps…
   - a) Convert tokens into platform code (correct)
   - b) Draw icons
   - c) Host sites
   - Why: One source, many outputs.
3. Unstyled accessible primitives…
   - a) Give behavior and a11y, you add style (correct)
   - b) Remove all behavior
   - c) Are paid only
   - Why: They speed up accessible UI.

#### Project: Build a tokenized component kit

1. Create a tokens file (color, type, spacing)
2. Build a button and input from an accessible primitive
3. Document both in Storybook
4. Publish the kit to GitHub with a README and license

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 24: Licenses & Contributing

**Level:** Intermediate

#### Lesson

**Understand licenses**

Permissive licenses like MIT, BSD, and Apache 2.0 let you use code in many projects if you keep notices. Copyleft licenses like GPL require sharing changes under the same terms in some cases. Fonts often use the SIL Open Font License, and content may use Creative Commons. When unsure, read the license or ask a lawyer.

**Using open assets legally**

Record each asset's source, license, author, and required credit in a file. Some licenses forbid commercial use or modification. Open source is not the same as public domain.

**Contributing back**

Start with documentation fixes, accessibility issues, translations, icons, and 'good first issue' labels. Read CONTRIBUTING.md and the code of conduct, discuss before big changes, and open small focused pull requests. Contributions are strong portfolio proof.

#### Key takeaways

- Permissive vs copyleft matters
- Track source, license, credit
- Start with docs, a11y, and good first issues

#### Quiz

1. MIT license is…
   - a) Permissive (correct)
   - b) Copyleft only
   - c) Public domain
   - Why: It allows broad reuse with notice.
2. Open source equals…
   - a) Public domain
   - b) Licensed with specific terms (correct)
   - c) Free for any use
   - Why: Terms still apply.
3. A good first contribution?
   - a) Fix docs or a11y issue (correct)
   - b) Rewrite the project
   - c) Delete files
   - Why: Small changes build trust.

#### Project: Make your first contribution

1. Pick an open-source design or UI project you use
2. Read its CONTRIBUTING file and find a good first issue
3. Submit a docs, accessibility, or design improvement
4. Add the contribution to your portfolio with a short write-up

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 25: Critical Thinking & Creativity

**Level:** Intermediate

#### Lesson

**Frame the problem**

Ask why until you reach the real need, define success metrics, and write 'How might we…' questions that are neither too broad nor too narrow. Beware solution bias, where you pick the answer before understanding the problem.

**Diverge, then converge**

Generate many ideas without judgment (crazy 8s, brainwriting, SCAMPER), then narrow with criteria such as impact, effort, and risk. Use first-principles thinking to question assumptions, and run pre-mortems ('imagine it failed: why?').

**Thinking traps**

Confirmation bias, anchoring, sunk cost, and survivorship bias distort judgment. Seek disconfirming evidence, write decisions with their reasons, and review outcomes later to calibrate yourself.

**Evaluate evidence**

Ask: who collected it, how many people, what was left out, and does it fit other evidence? One strong pattern across methods beats a dramatic single quote. State your confidence level and what would change your mind.

**Creative methods**

Constraints spark creativity: limit time, colors, or screens. Try analogies from other fields, reverse the problem ('how could we make this worse?'), and combine two unrelated ideas. Sketch 8 ideas in 8 minutes before refining any.

#### Key takeaways

- Frame the problem before solving
- Diverge then converge
- Name and counter your biases

#### Quiz

1. A pre-mortem asks…
   - a) Why might this fail? (correct)
   - b) Who is to blame?
   - c) What is next quarter?
   - Why: It surfaces risks early.
2. Divergence means…
   - a) Generating many options (correct)
   - b) Picking one
   - c) Presenting
   - Why: Quantity first, then evaluate.
3. Confirmation bias is…
   - a) Favoring evidence that agrees with you (correct)
   - b) Testing twice
   - c) Following rules
   - Why: Seek disconfirming data.
4. Strong evidence typically…
   - a) Appears across methods (correct)
   - b) Is one dramatic quote
   - c) Fits your hunch
   - Why: Triangulation raises confidence.
5. Reversing the problem helps by…
   - a) Exposing hidden assumptions (correct)
   - b) Saving time
   - c) Skipping research
   - Why: Seeing failure reveals causes.

#### Project: Run a full problem-solving cycle

1. Write a problem statement and 3 HMW questions
2. Generate 20 ideas in 15 minutes
3. Score them with impact, effort, and risk
4. Write a pre-mortem and a decision log
5. Run an 8-minute sketch sprint then rank ideas against 3 criteria

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 26: Communication, Storytelling & Collaboration

**Level:** Intermediate

#### Lesson

**Tell the story**

Structure presentations as context, problem, insight, options, recommendation, and next step. Lead with the answer for executives and with the journey for peers. Use the user's words and short clips to make evidence vivid.

**Give and receive feedback**

Give feedback that is specific, tied to a goal, and kind. Receive it by listening, asking questions, and separating the idea from yourself. Run critique with roles: presenter, facilitator, and note-taker.

**Work with product and engineering**

Align early on goals and constraints, share work in progress, speak in outcomes, and learn each partner's trade-offs. Write things down: briefs, decision docs, and meeting notes that capture who decides what.

**Stakeholders**

Map stakeholders by influence and interest. Learn each person's goal and fear, and tie design to their metric. Share early and often so nothing in a review is a surprise, and record decisions with who agreed.

**Conflict and feedback**

Disagree about the problem and the evidence, not the person. Ask 'what would need to be true for your option to win?' Use test results to settle opinion fights, and agree on how to decide before debating.

#### Key takeaways

- Story: problem, insight, recommendation
- Feedback: specific, goal-tied, kind
- Write decisions down

#### Quiz

1. Executives usually prefer…
   - a) The answer first (correct)
   - b) A long journey
   - c) No data
   - Why: Lead with the recommendation.
2. Good feedback is…
   - a) Specific and goal-tied (correct)
   - b) Vague praise
   - c) Personal
   - Why: It can be acted on.
3. A decision doc captures…
   - a) What, why, and who decided (correct)
   - b) Only designs
   - c) Nothing
   - Why: It preserves context.
4. Reviews should…
   - a) Contain no surprises (correct)
   - b) Be saved for launch
   - c) Avoid stakeholders
   - Why: Early sharing builds trust.
5. Best way to settle opinion disputes?
   - a) Test or gather evidence (correct)
   - b) Vote by seniority
   - c) Ignore
   - Why: Evidence moves decisions.

#### Project: Present like a pro

1. Choose a project and write a 6-part story outline
2. Present it in 8 minutes to 2 people
3. Ask for feedback using a critique format
4. Revise and record a final 3-minute version
5. Create a stakeholder map and tie your project to each person's metric

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 27: Focus, Productivity & Wellbeing

**Level:** Intermediate

#### Lesson

**Deep work habits**

Block uninterrupted time for hard work, silence notifications, and plan the next day the night before. Start with the smallest next step to beat procrastination. Batch email and meetings so craft time stays protected.

**Energy and health**

Sleep, movement, daylight, and breaks drive performance more than extra hours. Set up ergonomics (screen at eye level, wrists neutral), follow regular breaks, and rest your eyes. If anxiety, low mood, or burnout persists, talk with a qualified health professional.

**Boundaries and sustainability**

Define working hours, say no with alternatives, and avoid comparison spirals. Track wins weekly. Sustainable pace beats sprints, and creativity needs rest and input from outside design.

#### Key takeaways

- Protect deep work blocks
- Sleep and movement beat extra hours
- Seek professional help when needed

#### Quiz

1. Best use of deep work?
   - a) Hard, valuable tasks (correct)
   - b) Email
   - c) Chat
   - Why: Protect time for demanding work.
2. What boosts performance most?
   - a) Sleep and movement (correct)
   - b) More hours always
   - c) Skipping breaks
   - Why: Recovery matters.
3. If burnout persists…
   - a) Talk to a professional (correct)
   - b) Ignore it
   - c) Work harder
   - Why: Get support.

#### Project: Build a sustainable routine

1. Plan a week with 3 deep-work blocks
2. Set notification and meeting boundaries
3. Add a daily walk and a fixed sleep window
4. Review at week's end and adjust one thing

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 28: Usability Testing & Accessibility

**Level:** Advanced

#### Lesson

A usability test watches real users attempt tasks with your prototype. Five users find most major problems. Ask them to think aloud, and do not help.

Rate each issue by severity: blocks the task, slows it, or annoys. Fix blockers first.

Accessibility is part of quality, not an add-on. Follow WCAG: sufficient contrast, tap targets of at least 44px, labels on inputs, full keyboard use, and never use color alone to carry meaning.

**Writing a test plan**

A plan states the goal, the participants, the tasks, and the success criteria. Write tasks as scenarios ('You need to cancel next month's order') and never name interface labels. Pilot the test with one person first.

**Metrics**

Track task success rate, time on task, and error count. The System Usability Scale (SUS) is a 10-question survey; a score above about 68 is average. Use numbers to track progress and quotes to persuade stakeholders.

**WCAG in four words**

WCAG organizes accessibility as POUR: Perceivable, Operable, Understandable, Robust. Add alt text, captions, logical focus order, visible focus, and screen-reader labels. Test with VoiceOver or TalkBack and by keyboard only.

**Run it well**

Pilot first. Recruit by behavior, give scenario tasks, and ask users to think aloud. Observe silently, note quotes and errors, and ask 'what did you expect?' after a stumble. Debrief and rate severity by frequency, impact, and persistence.

**Accessibility practice**

Provide visible focus, logical tab order, labels tied to inputs, and error text that names the field and the fix. Support zoom to 200 percent, avoid time limits, and announce dynamic changes to assistive tech. Test with real users when you can.

#### Key takeaways

- Five users reveal most problems
- Don't help; watch and note
- Accessibility: contrast, 44px targets, labels, keyboard

#### Quiz

1. How many users find most major issues?
   - a) 1
   - b) About 5 (correct)
   - c) 100
   - Why: Small rounds, repeated, work best.
2. During a test you should…
   - a) Explain the screen
   - b) Stay quiet and observe (correct)
   - c) Fix bugs live
   - Why: Helping hides real problems.
3. Minimum recommended tap target?
   - a) 16px
   - b) 24px
   - c) 44px (correct)
   - Why: Large targets reduce errors.
4. POUR stands for…
   - a) Perceivable, Operable, Understandable, Robust (correct)
   - b) Plan, Observe, Use, Repeat
   - c) Pixel, Opacity, Unit, Radius
   - Why: These are the four WCAG principles.
5. A good test task…
   - a) Names the button to click
   - b) Describes a goal as a scenario (correct)
   - c) Is vague
   - Why: Naming labels gives away the answer.
6. After a stumble, ask…
   - a) What did you expect? (correct)
   - b) Why didn't you see it?
   - c) Nothing
   - Why: Learn expectations without blame.
7. Error text should…
   - a) Name the field and fix (correct)
   - b) Say 'invalid'
   - c) Use red only
   - Why: Be specific and accessible.

#### Project: Test and fix

1. Write 3 tasks for your prototype
2. Test with 3 people while they think aloud
3. Log every issue and rate severity
4. Fix the top 2 issues and note what changed
5. Write a full test plan with tasks and success criteria
6. Run an accessibility check using a screen reader on your prototype
7. Run a think-aloud test and rate each issue by frequency, impact, and persistence

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 29: Design Systems & Portfolio

**Level:** Advanced

#### Lesson

A design system is a shared library of tokens (color, type, spacing), components, and rules. It keeps products consistent and speeds up teams.

Build components with variants and states: default, hover, focus, disabled, error. Name tokens by purpose ('color-danger'), not value ('red-500').

Handoff means giving developers specs, assets, and behavior notes. Then present your work as case studies: problem, your role, process, decisions, outcome.

**Tokens and components**

Define tokens first, then build primitives (button, input), then patterns (form, card). Document each component with usage, do and don't, states, and accessibility notes. Version your system and announce changes.

**Handoff**

Share a clean file, name layers, use auto layout, and note behavior that visuals cannot show: animations, validation, and edge cases. Review the built result with developers before launch.

**Portfolio and interviews**

Show 3 to 4 case studies, not 20 screens. Explain constraints and trade-offs, not just outcomes. In interviews, practice walking through your process in 5 minutes and be ready to discuss what you would change.

**System governance**

Decide who can change the system, how requests are reviewed, and how releases are versioned. Track adoption and detached components, deprecate old patterns with notice, and write usage guidance with do and don't examples.

**Portfolio storytelling**

Open each case study with the problem and your role, show 2 to 3 decisions with alternatives you rejected, include evidence (quotes, metrics), and end with outcomes and reflection. Keep a short intro and make your best work reachable in one click.

#### Key takeaways

- Tokens + components + rules
- Name by purpose, include all states
- Case study: problem, process, outcome

#### Quiz

1. Best token name?
   - a) red-500
   - b) color-danger (correct)
   - c) bright
   - Why: Purpose survives rebrands.
2. A design system gives you…
   - a) Consistency and speed (correct)
   - b) More meetings
   - c) Fewer users
   - Why: Reuse reduces rework.
3. A strong case study includes…
   - a) Only final screens
   - b) Problem, process, decisions, outcome (correct)
   - c) Just a logo
   - Why: Hiring managers want your thinking.
4. Build order in a design system?
   - a) Pages, then tokens
   - b) Tokens, primitives, patterns (correct)
   - c) Only components
   - Why: Foundations first keeps things consistent.
5. A strong portfolio shows…
   - a) 20 unlabeled screens
   - b) A few case studies with decisions (correct)
   - c) Only logos
   - Why: Process and thinking get you hired.
6. Healthy system governance includes…
   - a) Review process and versioning (correct)
   - b) No rules
   - c) Only a style guide
   - Why: Governance keeps it trustworthy.
7. Case studies should show…
   - a) Decisions with alternatives (correct)
   - b) Only polished UI
   - c) Only logos
   - Why: Thinking proves skill.

#### Project: Build a mini system and case study

1. Define 5 color tokens, a type scale, and spacing steps
2. Design a button with 5 states
3. Write a one-page case study of your best project
4. Put it all together as your first portfolio piece
5. Document your button component with usage and accessibility notes
6. Practice presenting your case study aloud in 5 minutes
7. Write a contribution and deprecation policy for your mini system

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 30: Quantitative Research & Experimentation

**Level:** Advanced

#### Lesson

**Experiment design**

An A/B test compares a control and a variant on one metric. State a hypothesis, choose a primary metric, calculate sample size before starting, and run for full weekly cycles. Stopping early inflates false wins.

**Reading results**

Statistical significance (commonly p<0.05) says a difference is unlikely random; it does not say it matters. Check effect size, confidence intervals, and guardrail metrics like retention or support tickets.

**Beyond A/B**

Use funnel and cohort analysis, heatmaps, session replays, and surveys such as SUS or NPS. Triangulate: numbers find where, research explains why.

**Metrics that matter**

Use frameworks like HEART (happiness, engagement, adoption, retention, task success) to pick metrics tied to goals. Separate leading indicators (activation) from lagging ones (revenue) and define each metric precisely before measuring.

**Common mistakes**

Running many variants inflates false positives, peeking at results early inflates wins, and tiny samples mislead. Check sample ratio mismatch, segment results carefully, and confirm effects persist after the novelty fades.

#### Key takeaways

- Hypothesis, metric, sample size first
- Significance is not importance
- Triangulate numbers with research

#### Quiz

1. Stopping a test early causes…
   - a) Better data
   - b) Inflated false positives (correct)
   - c) Faster learning with no risk
   - Why: Peeking breaks the statistics.
2. A guardrail metric…
   - a) Is the success goal
   - b) Checks you did not harm something else (correct)
   - c) Measures color
   - Why: It protects the wider experience.
3. Significant but tiny effect means…
   - a) Always ship
   - b) Check if the effect size matters (correct)
   - c) Ignore data
   - Why: Practical impact matters.
4. HEART stands for…
   - a) Happiness, Engagement, Adoption, Retention, Task success (correct)
   - b) Hover, Edit, Act, Run, Test
   - c) None
   - Why: Google's UX metrics framework.
5. Peeking early causes…
   - a) More false positives (correct)
   - b) Better accuracy
   - c) No effect
   - Why: Stop rules matter.

#### Project: Plan an experiment

1. Write a hypothesis for a design change
2. Choose primary and guardrail metrics
3. Estimate sample size with a free calculator
4. Document how you will interpret each outcome
5. Define 5 HEART metrics for a product with exact formulas

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 31: Service Design & Product Strategy

**Level:** Advanced

#### Lesson

**Service blueprints**

A service blueprint maps user actions, frontstage touchpoints, backstage work, and supporting systems across time. It reveals where internal handoffs cause user pain.

**Strategy and prioritization**

Connect design to goals with OKRs. Prioritize with frameworks like RICE (reach, impact, confidence, effort) or Kano (basic, performance, delight). Say no with evidence.

**Business literacy**

Learn unit economics, retention, and conversion. Frame proposals as outcomes: 'cut checkout drop-off by 10%', not 'redesign checkout'.

**Systems and ecosystems**

A service spans channels, people, policies, and tools. Map touchpoints across channels, find handoff failures between teams, and design the backstage so the frontstage promise holds.

**Strategy artifacts**

Write a vision, a clear problem, and outcome goals. Use opportunity solution trees to link outcomes to opportunities to experiments, and an assumption map to test the riskiest beliefs first. Roadmaps should state outcomes, not feature promises.

#### Key takeaways

- Blueprint front and backstage
- Prioritize with RICE or Kano
- Frame work as outcomes

#### Quiz

1. A service blueprint shows…
   - a) Only screens
   - b) Frontstage and backstage across time (correct)
   - c) Logo rules
   - Why: It exposes the whole system.
2. RICE helps you…
   - a) Choose colors
   - b) Prioritize work (correct)
   - c) Write copy
   - Why: It scores reach, impact, confidence, effort.
3. Best proposal framing?
   - a) Redesign checkout
   - b) Cut checkout drop-off by 10% (correct)
   - c) Make it prettier
   - Why: Outcomes win support.
4. An opportunity solution tree links…
   - a) Outcome, opportunities, solutions, experiments (correct)
   - b) Colors and fonts
   - c) Teams and salaries
   - Why: It keeps strategy testable.
5. Test which assumptions first?
   - a) The riskiest (correct)
   - b) The easiest
   - c) None
   - Why: Reduce the biggest uncertainty.

#### Project: Blueprint and prioritize

1. Draw a service blueprint for a real service
2. Mark 3 backstage causes of user pain
3. Score 6 ideas with RICE
4. Write a one-page strategy memo with an outcome goal
5. Build an assumption map and design one cheap test for the riskiest assumption

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 32: Accessibility in Depth

**Level:** Advanced

#### Lesson

**Inclusive design**

Design for permanent, temporary, and situational limits: a broken arm, bright sunlight, a noisy train. Solutions for edge cases improve the experience for everyone.

**Practical standards**

Meet WCAG 2.2 AA: contrast 4.5:1, focus visible, target size, consistent help, no color-only meaning, captions and transcripts, reflow at 400% zoom, and motion that can be reduced.

**Testing and process**

Combine automated tools (catch about a third of issues) with manual keyboard and screen-reader testing and with disabled participants. Add accessibility notes to every handoff and to your definition of done.

**Semantics and ARIA**

Use native HTML first: buttons, links, headings, lists, and form labels give roles and keyboard behavior for free. Use ARIA only to fill gaps, and wrong ARIA is worse than none. Manage focus when content changes (modals, route changes) and keep a logical order.

**Cognitive and motor access**

Reduce cognitive load with clear language, consistent patterns, and forgiving flows. For motor needs, offer large targets, alternatives to drag and gestures, and enough time. Avoid flashing content more than three times per second.

#### Key takeaways

- Disability can be permanent, temporary, or situational
- Meet WCAG 2.2 AA
- Automated tools are not enough

#### Quiz

1. Automated tools catch…
   - a) Everything
   - b) A portion of issues (correct)
   - c) Nothing
   - Why: Manual testing is required.
2. Color-only status is…
   - a) Fine
   - b) A failure; add text or icons (correct)
   - c) Required
   - Why: Not everyone perceives color.
3. Situational disability example?
   - a) Glare on a screen (correct)
   - b) Blindness
   - c) Deafness
   - Why: Temporary context creates limits.
4. First choice for interactive elements?
   - a) Native HTML (correct)
   - b) ARIA on divs
   - c) Images
   - Why: Native elements include accessibility.
5. Flashing limit?
   - a) No more than 3 flashes per second (correct)
   - b) 10 per second
   - c) None needed
   - Why: Seizure safety.

#### Project: Audit and fix

1. Audit a real site against WCAG 2.2 AA
2. Test with keyboard only and a screen reader
3. Document 10 issues with severity and fixes
4. Redesign the worst screen and re-test
5. Fix focus management on a modal and verify with keyboard only

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 33: Portfolio & Case Studies

**Level:** Advanced

#### Lesson

**What employers look for**

Hiring managers scan quickly. They want clear problem framing, evidence-based decisions, craft, collaboration, and measurable outcomes. Three strong case studies beat ten shallow ones.

**Case study structure**

Use: context and your role, the problem, constraints, research, process and key decisions with alternatives you rejected, solution, results, and what you learned. Show messy work, not just polished screens.

**Building and presenting**

Host a fast, accessible site with a clear headline, your best work first, and contact info visible. If you lack clients, do self-initiated projects, redesigns with real research, volunteer work, or hackathons.

**Show impact**

Quantify outcomes where you can (time saved, errors reduced, conversion) and say how you measured. If numbers are not available, show qualitative proof such as test quotes and before and after comparisons. Be honest about your role and what the team did.

**Presentation craft**

Lead with a one-line summary, use annotated visuals, and keep each case study readable in about 5 minutes. Show process artifacts (sketches, maps, test notes) sparingly and make everything accessible with alt text and strong contrast.

#### Key takeaways

- 3 strong case studies beat 10 weak ones
- Show decisions and trade-offs
- No clients? Create real projects

#### Quiz

1. Best case study content?
   - a) Only final screens
   - b) Problem, process, decisions, results (correct)
   - c) A logo
   - Why: Thinking proves skill.
2. No work experience, then…
   - a) Wait
   - b) Build self-initiated projects with research (correct)
   - c) Copy others
   - Why: Real process counts.
3. Which goes first?
   - a) Your weakest
   - b) Your strongest work (correct)
   - c) Your resume
   - Why: First impressions matter.
4. If you lack metrics…
   - a) Show qualitative evidence honestly (correct)
   - b) Invent numbers
   - c) Skip the case study
   - Why: Integrity matters.
5. A case study should take about…
   - a) 5 minutes to read (correct)
   - b) 1 hour
   - c) 10 seconds
   - Why: Respect reviewers' time.

#### Project: Publish your portfolio

1. Pick 3 projects and outline each case study
2. Write each in the 8-part structure
3. Build a one-page site with fast load and clear contact
4. Get feedback from 3 designers and revise
5. Add measurable or qualitative outcomes to each case study and cut each to a 5-minute read

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 34: Resume, Job Search & Interviews

**Level:** Advanced

#### Lesson

**Resume and online presence**

Keep a one-page resume focused on outcomes ('reduced checkout steps from 7 to 4') over duties. Match keywords from the posting. Keep LinkedIn consistent with your portfolio and share work publicly.

**Finding roles**

Search job boards, company career pages, and design communities. Network with genuine curiosity: ask for advice, not jobs. Consider internships, apprenticeships, contract work, and adjacent roles such as product, content, or research design to get in.

**Interviews and design challenges**

Expect recruiter screens, portfolio presentations, whiteboard or take-home challenges, and behavioral rounds. Practice the STAR method (situation, task, action, result), clarify the problem before solving it, think aloud, and ask about the team, process, and success metrics.

**Prepare your stories**

Prepare 6 to 8 stories covering conflict, failure, influence, ambiguity, and impact. Practice the STAR method with specific numbers and your individual contribution. Research the company's product and users and prepare 3 thoughtful critiques and questions.

**Design challenge method**

Restate the goal, ask clarifying questions, state assumptions, define users and success, explore 2 to 3 options, choose one with trade-offs, and sketch key screens. Narrate your thinking, manage time, and finish with risks and next steps.

#### Key takeaways

- Resume: outcomes, not duties
- Network by asking for advice
- In challenges: clarify, think aloud, trade-offs

#### Quiz

1. STAR stands for…
   - a) Situation, Task, Action, Result (correct)
   - b) Design, Test, Review
   - c) Plan, Sketch, Ship
   - Why: It structures behavioral answers.
2. In a design challenge, first…
   - a) Open Figma
   - b) Clarify the problem and users (correct)
   - c) Pick colors
   - Why: Framing shows senior thinking.
3. Resume bullets should show…
   - a) Duties
   - b) Outcomes (correct)
   - c) Adjectives
   - Why: Impact is persuasive.
4. In a design challenge, you should first…
   - a) Clarify goals and users (correct)
   - b) Draw final UI
   - c) Pick colors
   - Why: Frame before solving.
5. STAR answers should include…
   - a) Specific actions and results (correct)
   - b) Vague claims
   - c) Only team results
   - Why: Be concrete.

#### Project: Prepare to get hired

1. Rewrite your resume with 5 outcome bullets
2. List 20 target companies and 10 people to ask for advice
3. Prepare 5 STAR stories
4. Do 2 mock interviews and 1 timed design challenge
5. Complete a timed 60-minute design challenge and write a debrief of what to improve

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 35: Freelancing & Client Work

**Level:** Advanced

#### Lesson

**Finding and scoping clients**

Specialize in a niche (for example SaaS onboarding or healthcare apps) so clients see you as the obvious fit. Find clients through referrals, communities, outreach, and content. Run a discovery call to learn goals, budget, timeline, and decision makers.

**Proposals, pricing, contracts**

Write proposals around outcomes, scope, deliverables, timeline, and price. Price by value, project, or day rate, not by guessing hours alone. Use a contract covering scope, revisions, payment terms, kill fee, ownership, and credit. Take a deposit before starting.

**Managing the engagement**

Set communication rhythm, share work in progress, present the reasoning behind decisions, and handle scope creep with a change order. Collect testimonials and ask for referrals at the end.

#### Key takeaways

- Niche down
- Contract and deposit every time
- Change orders handle scope creep

#### Quiz

1. Scope creep is handled by…
   - a) Working free
   - b) A written change order (correct)
   - c) Ignoring it
   - Why: Extra work needs extra agreement.
2. Before starting, you should get…
   - a) A deposit and signed contract (correct)
   - b) A promise
   - c) A logo
   - Why: It protects both sides.
3. Why specialize?
   - a) Fewer clients but easier selling (correct)
   - b) It is required
   - c) Cheaper tools
   - Why: A niche builds trust and referrals.

#### Project: Prepare for your first client

1. Choose a niche and write a one-sentence offer
2. Create a proposal and contract template
3. Draft a pricing sheet with 3 packages
4. Contact 10 potential clients or ask for 3 referrals

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 36: Handoff & Developer Tools

**Level:** Advanced

#### Lesson

**Design to dev**

Figma Dev Mode exposes specs, code snippets, and component status. Tokens Studio and Figma variables sync tokens to code. Zeroheight, Supernova, or Storybook document systems.

**Developer environment**

Learn Git and GitHub for versioning, VS Code for editing, Chrome DevTools to inspect and debug layouts, and Netlify, Vercel, or GitHub Pages to publish. Even basic comfort speeds collaboration.

**Quality assurance**

Review builds against design with visual diff tools such as Chromatic, compare in DevTools, and file clear bugs with screenshots, steps, and expected results.

#### Key takeaways

- Variables and tokens bridge design and code
- Git, VS Code, DevTools basics
- Review builds and file clear bugs

#### Quiz

1. Storybook is used for…
   - a) Documenting and testing UI components (correct)
   - b) Writing novels
   - c) Video editing
   - Why: It shows components in isolation.
2. Chrome DevTools helps you…
   - a) Inspect and debug layouts (correct)
   - b) Edit photos
   - c) Send email
   - Why: It reveals real CSS.
3. A good bug report includes…
   - a) Steps, screenshot, expected result (correct)
   - b) Only 'broken'
   - c) Opinions
   - Why: It is reproducible.

#### Project: Ship a component to code

1. Build a button component with tokens in Figma
2. Recreate it in HTML/CSS using the same tokens
3. Publish it on GitHub Pages or Netlify
4. Compare design and build with DevTools and file 3 bug notes

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 37: AI-Powered Design Workflows

**Level:** Advanced

#### Lesson

**AI across the process**

Use AI for research synthesis, interview summaries, copy options, image ideas, code drafts, and design variations. Tools include Claude and ChatGPT for text and analysis, Figma's AI features, v0 and similar for UI code, and Midjourney or Firefly for imagery.

**Use with judgment**

AI drafts quickly but can be wrong, generic, or biased. Verify facts, edit for your users and brand, check licensing, and never paste confidential data into tools without approval.

**Build your own workflow**

Create reusable prompts for tasks like affinity grouping, heuristic reviews, and copy variants. Treat output as a first draft that you critique, not as a decision.

#### Key takeaways

- AI speeds drafts, not decisions
- Verify, edit, and check licensing
- Protect confidential data

#### Quiz

1. AI-generated research summaries should be…
   - a) Verified against sources (correct)
   - b) Trusted blindly
   - c) Published unchanged
   - Why: Errors are possible.
2. Before using AI imagery commercially, check…
   - a) Licensing terms (correct)
   - b) Nothing
   - c) Color names
   - Why: Rights vary by tool.
3. Confidential client data in public AI tools?
   - a) Avoid without approval (correct)
   - b) Always fine
   - c) Required
   - Why: Protect privacy and contracts.

#### Project: Build an AI-assisted workflow

1. Pick 3 repetitive tasks in your process
2. Write and test a reusable prompt for each
3. Compare AI output with your own and note errors
4. Document rules for verification and data safety

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 38: Accessibility & QA Tools

**Level:** Advanced

#### Lesson

**Automated checks**

axe DevTools, WAVE, and Lighthouse find common issues like missing labels and low contrast. Stark and Figma contrast plugins check designs before build.

**Assistive technology**

Test with VoiceOver on Apple devices, TalkBack on Android, NVDA on Windows, and keyboard-only navigation. Learn basic commands for each.

**Cross-device QA**

Test on real devices when possible, plus BrowserStack or similar for coverage, throttled network in DevTools, and text zoom. Record results in a checklist.

#### Key takeaways

- Automate, then test manually
- Learn a screen reader
- Test devices and slow networks

#### Quiz

1. TalkBack is a screen reader for…
   - a) Android (correct)
   - b) Windows only
   - c) Printers
   - Why: It is Android's screen reader.
2. Lighthouse checks…
   - a) Performance and accessibility (correct)
   - b) Taxes
   - c) Colors only
   - Why: It audits quality metrics.
3. Contrast checks should happen…
   - a) Before build (correct)
   - b) After launch only
   - c) Never
   - Why: Catch issues early.

#### Project: Create a QA checklist

1. Run axe or Lighthouse on a page
2. Test one flow with a screen reader
3. Test at 200% text zoom and slow network
4. Write a reusable checklist for future projects

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 39: Business, Collaboration & Delivery Tools

**Level:** Advanced

#### Lesson

**Team tools**

Slack or Teams for chat, Loom for async walk-throughs, Notion or Confluence for docs, Jira or Linear for tasks, and Google Workspace for sharing. Write decision docs so context survives.

**Client and business tools**

Use a proposal and contract tool (such as PandaDoc or HelloSign), invoicing and payments (Stripe, QuickBooks, or similar), a scheduler like Calendly, and a simple CRM spreadsheet or Notion. Track time and expenses.

**Presenting your work**

Present in Figma, slides, or Loom. Lead with the problem, show options, explain trade-offs, and ask for a specific decision.

#### Key takeaways

- Async tools reduce meetings
- Contracts and invoices are tooling too
- Present problem, options, decision

#### Quiz

1. Loom is useful for…
   - a) Async video walk-throughs (correct)
   - b) Vector drawing
   - c) Coding
   - Why: Share context without a meeting.
2. Invoices should be tracked in…
   - a) Accounting or invoicing software (correct)
   - b) Memory
   - c) Chat only
   - Why: Records matter for taxes.
3. A good presentation ends with…
   - a) A clear request for a decision (correct)
   - b) Silence
   - c) More slides
   - Why: Drive action.

#### Project: Set up your studio ops

1. Create a project doc template in Notion or similar
2. Set up a task board with 3 columns
3. Create contract and invoice templates
4. Record a 3-minute Loom walkthrough of one project

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 40: Free Trials, Startup & Founder Programs

**Level:** Advanced

#### Lesson

**Trial hygiene**

Free trials are for testing real workflows. Note the end date, cancel before billing if you will not use it, and review what happens to your data afterward. Use a calendar reminder and keep a list of subscriptions. Only use legitimate sources; avoid cracked software, which risks malware and legal trouble.

**Where to find trials and credits**

Check each vendor's pricing page for trials and free tiers, plus sites such as the GitHub Student Developer Pack for students. Compare what is truly free versus limited. Cloud and AI vendors often offer introductory credits that expire.

**Startup and founder programs**

Programs such as AWS Activate, Google for Startups, and Microsoft for Startups Founders Hub have offered credits and support to qualifying early-stage companies. Eligibility, amounts, and terms change, so read the current rules and apply with a real plan.

#### Key takeaways

- Calendar reminders prevent surprise charges
- Use legitimate offers only
- Startup credits need current eligibility checks

#### Quiz

1. Before a trial ends you should…
   - a) Set a reminder to cancel or decide (correct)
   - b) Ignore it
   - c) Share the login
   - Why: Prevent unwanted charges.
2. Cracked software is…
   - a) Risky and illegal (correct)
   - b) Recommended
   - c) Free forever
   - Why: It brings malware and legal risk.
3. Startup credit programs…
   - a) Have changing rules (correct)
   - b) Never change
   - c) Accept everyone
   - Why: Verify current eligibility.

#### Project: Run a trial and credit plan

1. List 5 paid tools you might need and their free tiers or trials
2. Set cancel reminders for any trial you start
3. Research 3 startup programs and their eligibility
4. Write a one-page plan matching tools and credits to your business

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 41: Open Source Research, Accessibility & Analytics

**Level:** Advanced

#### Lesson

**Accessibility**

axe-core powers many testing tools. Pa11y automates checks, and Lighthouse is open source. NVDA is a free open-source screen reader for Windows, and Orca serves Linux. Use them with manual tests, because automation finds only part of the problems.

**Research and analytics**

LimeSurvey runs surveys, and Jitsi handles video calls. Matomo, Plausible, Umami, and PostHog offer open-source analytics, some self-hostable for privacy control. Choose tools that respect user consent and data laws.

**Collecting responsibly**

Self-hosting gives data control but you must secure and update it. Anonymize data, explain what you collect, and delete it when no longer needed.

#### Key takeaways

- axe-core and NVDA are open accessibility staples
- Open analytics can be privacy-first
- Self-hosting needs security care

#### Quiz

1. NVDA is…
   - a) An open-source screen reader (correct)
   - b) A design tool
   - c) A font
   - Why: It is free and open source.
2. Self-hosted analytics requires…
   - a) Security and maintenance (correct)
   - b) Nothing
   - c) Only a logo
   - Why: You own the responsibility.
3. Automated a11y tools find…
   - a) Only some issues (correct)
   - b) All issues
   - c) No issues
   - Why: Manual testing is still required.

#### Project: Run an open-source audit stack

1. Install axe or Pa11y and scan a page
2. Test the same page with NVDA or another screen reader
3. Set up a privacy-first analytics tool on a demo site
4. Write findings and fixes in a short report

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 42: Open Source Productivity, Docs & Self-Hosting

**Level:** Advanced

#### Lesson

**Knowledge and project tools**

Logseq and AppFlowy are open-source note and workspace tools. OpenProject, Taiga, and Plane manage projects. Mattermost and Rocket.Chat offer team chat. Choose by team size and whether you want to host it.

**Documentation sites**

Docusaurus, MkDocs, and Hugo build documentation and portfolio sites from Markdown, which fits GitHub Pages. Write docs as part of the design system and publish them with the components.

**Self-hosting basics**

Self-hosting can run on a small server or a home machine using Docker. Keep backups, apply updates, use HTTPS, and limit open ports. If you lack time to maintain it, use a managed host of the open-source project instead.

#### Key takeaways

- Markdown + static site generators are portable
- Self-host only what you can maintain
- Backups and updates are essential

#### Quiz

1. MkDocs and Docusaurus build…
   - a) Documentation sites (correct)
   - b) Photos
   - c) 3D models
   - Why: They turn Markdown into sites.
2. Before self-hosting, plan…
   - a) Backups and updates (correct)
   - b) Nothing
   - c) Only colors
   - Why: Maintenance is the main cost.
3. Docker helps by…
   - a) Packaging apps to run consistently (correct)
   - b) Editing images
   - c) Writing copy
   - Why: It standardizes deployment.

#### Project: Publish an open-source docs site

1. Write 5 Markdown pages documenting your component kit
2. Build with MkDocs, Docusaurus, or Hugo
3. Deploy to GitHub Pages
4. Add a license and contribution guide to the repo

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 43: Money, Negotiation & Career Capital

**Level:** Advanced

#### Lesson

**Know your value**

Research market ranges from several sources for your role, level, and location, and track your outcomes so you can show impact. Compare total compensation: salary, bonus, equity, benefits, and growth. Check any figures against current local data.

**Negotiate**

Prepare a target, a walk-away number, and evidence. Anchor with a researched range, listen, and negotiate non-salary items too (title, scope, learning budget, flexibility). Get offers in writing.

**Personal finance basics**

Keep an emergency fund, separate business and personal money, track income and expenses, and plan for irregular freelance income and taxes. This is general education, not advice; consult a qualified accountant or financial advisor.

#### Key takeaways

- Research ranges and track impact
- Negotiate the whole package
- Consult a professional for tax and finance

#### Quiz

1. Before negotiating you need…
   - a) Research and evidence (correct)
   - b) Nothing
   - c) A guess
   - Why: Data builds leverage.
2. Beyond salary, you can negotiate…
   - a) Scope and learning budget (correct)
   - b) Nothing
   - c) Only a title
   - Why: Packages have many parts.
3. For tax questions…
   - a) Ask a qualified professional (correct)
   - b) Guess
   - c) Skip them
   - Why: Rules differ by place.

#### Project: Prepare a negotiation file

1. Gather salary ranges from 3 sources for your role
2. List 5 quantified achievements
3. Write your target, walk-away, and non-salary asks
4. Role-play the negotiation with a friend

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 44: Data, AI & Emerging Interfaces

**Level:** Expert

#### Lesson

**Designing AI products**

Make capability and limits clear. Show confidence, sources, and ways to correct the system. Design for failure: wrong outputs, refusals, and latency. Keep humans in control of consequential actions.

**Trust, ethics, privacy**

Collect the minimum data, explain use in plain language, and give real consent controls. Audit for bias in data and in who your designs exclude. Follow regulations such as GDPR.

**Beyond screens**

Voice, conversational, spatial, and wearable interfaces require new patterns: turn-taking, error recovery, ambient feedback, and multimodal fallbacks. Prototype with Wizard of Oz tests before building.

#### Key takeaways

- Show limits, sources, and correction
- Minimize data, maximize consent
- Wizard of Oz for new modalities

#### Quiz

1. For AI outputs you should…
   - a) Hide uncertainty
   - b) Show limits and let users correct (correct)
   - c) Remove sources
   - Why: Transparency builds calibrated trust.
2. Wizard of Oz testing means…
   - a) A human simulates the system (correct)
   - b) Using magic
   - c) Skipping research
   - Why: It tests concepts before engineering.
3. Data minimization means…
   - a) Collect everything
   - b) Collect only what you need (correct)
   - c) Sell data
   - Why: Less data, less risk.

#### Project: Design an AI feature responsibly

1. Define the task and where the AI could be wrong
2. Design states for success, uncertainty, and failure
3. Add correction and human override controls
4. Write a plain-language data and consent screen

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 45: Design Leadership & Ops at Scale

**Level:** Expert

#### Lesson

**From IC to Leader**
Transitioning from an Individual Contributor (IC) to a leader requires a mindset shift: your output is no longer screens, but the performance and health of your team. Leaders absorb ambiguity and provide clarity. You must delegate craft to focus on strategy, shielding your team from organizational noise so they can focus on solving user problems.

**Hiring and Team Design**
Hire for craft, judgment, and complementary skills, not cultural 'fit' (which often breeds homogeneity). Structure teams around user journeys rather than platforms to reduce silos. A balanced team requires a mix of junior talent for velocity, mid-level for execution, and senior staff to tackle architectural ambiguity.

**DesignOps and Scaling**
Design Operations (DesignOps) scales the work by optimizing tooling, templates, research repositories, intake processes, and review rituals. When a team grows past five designers, operational friction slows delivery. DesignOps standardizes file naming, handoff protocols, and asset management so designers spend time designing, not searching for files.

**The Art of Critique**
Run critiques around strategic goals, not subjective taste. Instead of asking 'Do we like this?', ask 'Does this solve the user's problem based on our research?' Establish clear roles in reviews: a presenter, a facilitator, and a note-taker. Give feedback that is specific, actionable, and kind, focusing on the work, never the person.

**Cross-Functional Alignment**
Design cannot succeed in a vacuum. Build early alliances with product managers and engineering leads. Product owns the 'what,' engineering owns the 'how,' and design owns the 'why' and 'who.' Align on OKRs (Objectives and Key Results) early in the quarter so design effort is tied directly to business priorities.

**Measuring Design Impact**
Quantify design's value through quality, speed, and business outcomes. Track metrics like task success rate, reduced support tickets, and conversion lifts. Internally, measure operational velocity: how long does it take to ship a feature? Use data to justify headcount and budget requests.

**Managing Up and Stakeholder Influence**
A federated system with contribution models avoids bottlenecks. Build influence by sharing research findings openly, writing clear decision documents, and communicating trade-offs to executives in their language (risk and revenue). Never surprise stakeholders at a final review; share early and often.

**Ethics and System Governance**
Leaders are responsible for the ethical implications of their products at scale. Establish governance models for your design system—decide who can change tokens, how requests are reviewed, and how releases are versioned. Ensure accessibility and inclusive design are hardcoded into the definition of done, not treated as post-launch QA.

#### Key takeaways

- Your output as a leader is the team's health and velocity.
- Critique goals and user needs, not subjective taste.
- DesignOps scales process, tooling, and communication.

#### Quiz

1. The primary shift when moving from IC to design leader is…
   - a) Designing screens faster
   - b) Focusing on team output and health instead of personal deliverables (correct)
   - c) Writing all the code
   - Why: A leader's product is the team itself.
2. When hiring, prioritizing "culture fit" often leads to…
   - a) High innovation
   - b) Homogeneity and lack of diverse thought (correct)
   - c) Better accessibility
   - Why: Hiring for culture 'add' or complementary skills is safer.
3. DesignOps primarily focuses on…
   - a) Choosing brand colors
   - b) Scaling tooling, process, and removing operational friction (correct)
   - c) Running A/B tests
   - Why: Ops lets designers focus on design.
4. A good design critique asks…
   - a) Does this look modern?
   - b) Does this solve the user problem we defined? (correct)
   - c) What is your favorite color?
   - Why: Goals anchor feedback in reality.
5. In cross-functional triads, Design traditionally owns…
   - a) The 'why' and the 'who' (correct)
   - b) The server architecture
   - c) The exact launch date
   - Why: Design advocates for the user and the problem.
6. To justify budget to an executive, a design leader should focus on…
   - a) Typography trends
   - b) Business outcomes, risk reduction, and velocity (correct)
   - c) The number of Figma layers
   - Why: Executives speak the language of business impact.
7. System governance defines…
   - a) Who gets promoted
   - b) How design system changes are proposed, reviewed, and versioned (correct)
   - c) Office seating charts
   - Why: Governance prevents the system from breaking down.
8. Accessibility in a mature design team should be…
   - a) Handled by developers only
   - b) Hardcoded into the definition of done (correct)
   - c) Checked a month after launch
   - Why: Inclusive defaults are cheaper and more ethical.
9. To manage stakeholders effectively, you should…
   - a) Hide work until the final reveal
   - b) Share early, align on goals, and avoid surprises (correct)
   - c) Ignore their metrics
   - Why: Trust grows from shared insight and visibility.
10. Measuring operational velocity means tracking…
   - a) How long it takes to go from brief to shipped feature (correct)
   - b) The number of colors used
   - c) The file size of the logo
   - Why: It proves the efficiency of the design process.

#### Project: Run a team practice

1. Write a 1-page critique guideline document with 3 core rules.
2. Define a template for a 1-on-1 check-in with a junior designer.
3. Draft a decision document mapping a recent design change to a business OKR.
4. Define 3 specific metrics you would use to measure design impact on your current project.
5. Write a contribution governance policy for a UI component library.
6. Run a mock 15-minute critique session on a wireframe using your new guidelines.


### Module 46: Capstone: Ship a Product End to End

**Level:** Expert

#### Lesson

**The brief**

Choose a real problem. You will research, define, ideate, prototype, test, build a mini system, write copy, plan metrics, and present. Treat it like a client project with a deadline.

**Deliverables**

Research summary, persona and journey map, IA and flows, wireframes, high-fidelity prototype, test report, tokens and 5 components, content guide, accessibility check, experiment plan, and a case study.

**How you are judged**

Clarity of problem, quality of evidence, craft, accessibility, and your ability to explain trade-offs. Present in 10 minutes.

#### Key takeaways

- Treat it like a real client
- Evidence over opinion
- Explain your trade-offs

#### Quiz

1. The strongest capstone feature is…
   - a) Most screens
   - b) Clear evidence-led decisions (correct)
   - c) Most animations
   - Why: Reasoning shows seniority.
2. Where to begin?
   - a) High-fidelity screens
   - b) A researched problem (correct)
   - c) A logo
   - Why: Start with the user problem.
3. What ends the project?
   - a) Last screen done
   - b) A tested, presented case study (correct)
   - c) Launch day
   - Why: Test and communicate.

#### Project: Complete the capstone

1. Write the brief and research plan
2. Deliver research, flows, and wireframes
3. Deliver a tested prototype and mini design system
4. Publish a case study and present it in 10 minutes

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 47: Starting a Design Business or Product

**Level:** Expert

#### Lesson

**Choose a model**

Options: a freelance practice, a boutique studio, a productized service with fixed scope and price, or your own product (app, templates, courses). Each trades income stability against upside and workload.

**Validate before building**

Interview 10 target customers, find a painful problem, test demand with a landing page or pre-sales, and build a minimum viable product. Measure interest by commitments such as deposits or sign-ups, not compliments.

**Operate and grow**

Register a legal entity as advised by a local professional, keep business and personal finances separate, track income and taxes, and use simple accounting software. Price for profit, build recurring revenue, and invest in marketing: case studies, a newsletter, and partnerships. Consult a qualified accountant or lawyer for legal and tax matters.

#### Key takeaways

- Validate with commitments
- Productize to scale
- Get professional legal and tax advice

#### Quiz

1. Best demand signal?
   - a) Compliments
   - b) Deposits or pre-orders (correct)
   - c) Likes
   - Why: Money is real commitment.
2. A productized service has…
   - a) Fixed scope and price (correct)
   - b) Unlimited work
   - c) No deliverables
   - Why: It is repeatable and scalable.
3. For legal and tax questions…
   - a) Guess
   - b) Consult a professional (correct)
   - c) Skip them
   - Why: Rules vary by place.

#### Project: Launch a validated offer

1. Pick a model and a target customer
2. Interview 10 prospects and summarize the top problem
3. Build a landing page with a clear offer and sign-up or deposit
4. Aim for 3 paying or committed customers

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 48: Career Growth & Lifelong Learning

**Level:** Expert

#### Lesson

**Career paths**

Individual contributor path: junior, mid, senior, staff, principal. Management path: lead, manager, director, VP. Many designers also move into product, research, or founding roles. Choose by what energizes you.

**Compounding skills**

Combine craft with a second skill such as research, code, writing, data, or business. Seek mentors, give back as a mentor, write and speak, and review your work yearly against your goals.

**Staying current**

Follow research, accessibility standards, and platform updates. Rebuild old projects with new methods, join critique groups, and keep a learning log. The durable skills are judgment, empathy, communication, and curiosity.

#### Key takeaways

- Two tracks: craft or management
- Pair design with a second skill
- Judgment and empathy last

#### Quiz

1. IC path means…
   - a) Individual contributor, growing craft (correct)
   - b) Interior consulting
   - c) Intern coordinator
   - Why: You can grow without managing people.
2. A durable skill is…
   - a) One tool's shortcuts
   - b) Judgment and empathy (correct)
   - c) A single trend
   - Why: Tools change, judgment lasts.
3. Best way to learn faster?
   - a) Never share work
   - b) Seek feedback and mentors (correct)
   - c) Avoid critique
   - Why: Feedback compounds growth.

#### Project: Plan your next 12 months

1. Write your 1, 3, and 5-year career goals
2. Pick 2 skills to build and a resource for each
3. Find a mentor and schedule monthly check-ins
4. Set quarterly reviews of your portfolio and learning log

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 49: Build Your Pro Toolkit

**Level:** Expert

#### Lesson

**Design your system of tools**

List your recurring tasks, choose one primary tool for each, and write a short workflow document so new collaborators can follow it. Automate repetition with plugins, templates, and shortcuts.

**Maintain and evolve**

Review your stack each quarter. Retire unused tools, test one new tool at a time, and keep your files portable with exports and backups. Never depend on one vendor for your only copy.

**Prove it**

Show your process in your portfolio: screenshots of files, system structure, and workflows. Teams hire people who work cleanly and reliably.

#### Key takeaways

- One primary tool per task
- Review and backup regularly
- Show your workflow as proof of skill

#### Quiz

1. Why back up files?
   - a) Avoid vendor lock-in and loss (correct)
   - b) Looks professional only
   - c) Required by Figma
   - Why: Protect your work.
2. Review your stack…
   - a) Quarterly (correct)
   - b) Never
   - c) Daily
   - Why: Regular, light reviews prevent bloat.
3. A workflow document helps…
   - a) New collaborators (correct)
   - b) Nothing
   - c) Only you
   - Why: Shared process speeds teams.

#### Project: Document your toolkit

1. Write your workflow from brief to handoff
2. Create templates for files, docs, and presentations
3. Set a backup routine and test a restore
4. Add a Tools and Workflow page to your portfolio

Completion requires all steps checked plus a written evidence note (30+ characters).

---

### Module 50: Mastery Roadmap: 12-Month Plan

**Level:** Expert

#### Lesson

**Months 1 to 3: foundations**

Study fundamentals, learn Figma or Penpot, and complete 3 small projects. Run 10 interviews and a usability test. Build your learning log and flashcards.

**Months 4 to 8: depth and proof**

Complete 2 full case studies, learn HTML/CSS, accessibility, and one specialty (research, interaction, content, or systems). Contribute to open source, publish writing, and join a critique group.

**Months 9 to 12: market and growth**

Polish your portfolio, practice interviews, apply or pitch clients, and keep shipping. Review each quarter, adjust goals, and find a mentor. Weekly rhythm: 2 learning sessions, 2 build sessions, 1 review, 1 outreach.

#### Key takeaways

- Foundations, then depth, then market
- A weekly rhythm beats bursts
- Review quarterly and adjust

#### Quiz

1. Best weekly rhythm?
   - a) Learn, build, review, reach out (correct)
   - b) Only watch videos
   - c) Only apply
   - Why: Balance input, output, and connection.
2. When to polish the portfolio?
   - a) After depth and proof (correct)
   - b) Before learning
   - c) Never
   - Why: Good work comes first.
3. Why quarterly reviews?
   - a) Adjust goals with data (correct)
   - b) Avoid work
   - c) Collect tools
   - Why: Plans need updating.

#### Project: Write and start your plan

1. Set one clear 12-month goal (job, freelance, or business)
2. Break it into 3 quarterly milestones
3. Schedule your weekly rhythm in a calendar
4. Share the plan with a mentor and book a monthly check-in

Completion requires all steps checked plus a written evidence note (30+ characters).

---

## 6. Known gaps and next steps for the next builder

- Modules deepened so far (extra lessons, scenario questions, steps): What UX Really Is, User Research, Flows and Information Architecture, Design Fundamentals, Wireframing, Learning How to Learn, Critical Thinking and Creativity, Communication, Visual Design Basics, Interaction and Prototyping, Usability Testing and Accessibility, Design Systems and Portfolio, The Pro Tool Landscape, Mobile and Responsive, Psychology and Behavior, Quantitative Research, Service Design, UX Writing, Accessibility in Depth, Portfolio and Case Studies, Resume and Interviews, Figma and Tool Mastery, HTML and CSS for Designers.
- Still to deepen: Expert modules (Design Leadership, Data and AI, Capstone, Business), freelancing, free tools, open-source tools, and the tools-and-perks modules. Target per module: 8+ lesson blocks, 10+ quiz questions including scenarios, and 6+ project steps.
- Tool and pricing statements (Figma Education, GitHub Student Developer Pack, Penpot, startup credits) change often. Verify against official pages before publishing; some startup-program details came from general knowledge, not fresh research.
- Ideas: spaced-repetition review queue, user flow builder lab, prototype timing lab variants, peer review of projects, downloadable portfolio checklist.