# UX + AI Prompt Library

Prompts for designers and product people building with AI, by [Ileana Marcut](https://github.com/IleanaMarcut). Every prompt here was tested in real work and is yours to copy and adapt. I write about how I use them on [UX + AI](https://ileanamarcut.substack.com/), the newsletter.

**Contents**

- [See your product through a different lens](#see-your-product-through-a-different-lens)
- [Spot AI opportunities in your product](#spot-ai-opportunities-in-your-product)
- [Turn an idea into a build-ready spec](#turn-an-idea-into-a-build-ready-spec)
- [Debug the root cause](#debug-the-root-cause)
- [Prepare and analyze user interviews](#prepare-and-analyze-user-interviews)
- [Run a quick clarity check](#run-a-quick-clarity-check)
- [Define what your AI should not do](#define-what-your-ai-should-not-do)
- [Turn an image into an interactive particle hero](#turn-an-image-into-an-interactive-particle-hero)
- [Be found by AI assistants](#be-found-by-ai-assistants)
- [Build your own Substack dashboard](#build-your-own-substack-dashboard)
- [Turn your patterns into skills](#turn-your-patterns-into-skills)

---

## See your product through a different lens

Full article: [5 Prompts That Help You See Your Product Through a Different Lens](https://ileanamarcut.substack.com/p/different-lens-ai-prompts)

Five prompts that stress test a product idea from angles you would not take on your own. They work with ChatGPT, Claude, Gemini, or any AI assistant.

### 1. The Reality Check

A fake news post-mortem that spots blind spots before you build or launch.

```
Act as a tech journalist writing a news-style post-mortem.
The product below failed 18 months after launch.

Write a short fake news article summarizing:

- What we misunderstood about our customers
- What we ignored or overcomplicated
- What decisions seemed smart but failed
- What we should’ve done to minimize the risk

List 10 clear reasons why the product failed.
```

### 2. The Emotional Hook

Finds the emotional driver behind adoption.

```
Assume the product’s real value is emotional, not functional.

Identify:

- What users want to feel before using it (stress, confusion, insecurity)
- What users want to feel after using it (relief, control, confidence)
- What identity the product supports (smart, professional, calm, efficient)
- What emotions block adoption (fear of failure, shame, overwhelm)
- What emotional moment your product should “own”

Then output:

- The 1 emotional promise that matters most
- 10 emotional reasons users will stay or leave
- 3 moments that increase trust instantly
- A rewrite of the product pitch focused only on emotion + identity
```

### 3. The Unfair Advantage

Uncovers or sharpens what makes your product hard to copy.

```
Assume competitors can copy:
- features
- pricing
- landing page
- UI

Find what they cannot copy because it depends on:
- insight
- access
- relationships
- credibility
- speed
- deep niche focus

Then output:

1) 10 things competitors can copy fast
2) 10 unfair advantages I could build or claim
3) 3 unfair advantages that best fit this product
4) A positioning line that makes the advantage obvious
```

### 4. The Future Shock

Tests your product against realistic future shifts.

```
Your job is to test this product against the future, but **every future shift must be directly relevant to the product below** (not generic trends).

First, read the product description carefully and identify:
- the core user behavior
- the core dependency (what must be true for it to work)
- the biggest vulnerability (what could break it)

Then generate **3 realistic future shifts** that would directly impact this product:

1) **A tech shift** specific to this product’s category or key technology
2) **A user behavior shift** specific to this user group and context
3) **A market/competitor shift** in the exact space this product competes in

For each future shift, answer:

- What breaks in the product instantly?
- What becomes irrelevant overnight?
- What becomes more valuable than before?
- What would we need to change to survive and still win?

Then output:

1) The 3 shifts (short + clear + relevant)
2) The 3 product adaptations (one per shift)
3) The strongest future-proof version of the product (combine insights)
4) A new positioning line that stays strong across all 3 futures
```

### 5. The Product Shapeshifter

Redesigns the product under 3 extreme constraints to reveal its core value.

```
Your job is to redesign the same product under 3 extreme constraints.
Each version must still deliver the same user outcome, but with a totally different shape.

Create 3 versions:

### Version 1: No App Allowed
The product cannot be an app, SaaS, or platform.
What does it become?

### Version 2: No Learning Curve
The user cannot spend more than 30 seconds learning how it works.
What changes?

### Version 3: No Trust Required
Assume users don’t trust you at all.
No data sharing, no permissions, no risky onboarding.
How does it still work?

Then output:

1) The 3 redesigned versions (clear description)
2) What each version reveals about the product’s true value
3) Which version is most likely to win and why
4) One experiment to test the strongest version in 7 days
```

### The product description block

Each of the five prompts above ends with this block. Fill it in once, keep it handy, and paste it under whichever lens you run:

```
Here’s the product description:
🔥 fill the details of your project below 🔥

Product in 1 sentence
What are you building, and what does it help someone do?

Target user
Who exactly is it for? (role + context + type of customer)

Problem
What painful problem are they dealing with today?

When it happens
When does this problem show up the most? (specific moment or situation)

Solution features
What does the product do? (3 to 6 features in plain language)

Current alternatives
What do they use instead today? (tools, workarounds, “do nothing”)

Why better / different
Why would someone choose this over the alternatives?

User flow (3 steps)
What are the 3 main steps a user takes from start to success?

Outcome
What changes for the user after using it? What’s the win?

Pricing model
How do you make money? (subscription, one-time, usage-based, etc.)

Biggest assumption
What must be true for this idea to work at all?
```

---

## Spot AI opportunities in your product

Full article: [Design for AI: How to Spot AI Opportunities in Your Product](https://ileanamarcut.substack.com/p/spotting-ai-opportunities-in-your)

A 3-step chain: turn research notes into needs, needs into How Might We questions, and questions into realistic AI capabilities with feasibility scores. Run the steps in order, in your AI tool of choice.

### 6. Turn user pains into clear need statements

```
Here are raw notes from my user research (interviews, support tickets, feedback):

[paste your notes here]

Turn these into a short list of clear user needs. For each one:

- Write it as one simple sentence, from the user's point of view
- Focus on the real problem, not a solution
- Group similar pains into a single need

Important: Use only what's in my notes.

- Do not invent data, examples, or needs that aren't there
- Do not interpret meaning or assume anything I didn't say
- If something is unclear or missing, flag it instead of guessing
```

### 7. Reframe needs into How Might We questions

```
Here is a list of user needs from my research:

[paste your user needs here]

For each need, write 2 to 3 "How Might We" questions. Each one should:

- Start with "How might we..."
- Stay broad enough to allow different solutions
- Focus on the user's goal, not a specific feature

Only work from the needs I listed. Don't add new needs, and don't assume a solution inside the question.
```

### 8. Map needs to AI capabilities with feasibility scores

```
I’m working on identifying valuable and realistic AI opportunities for our product/solution.

Below is a list of real User Needs and corresponding How Might We (HMW) questions that we gathered through research.

For each pair, suggest a few ways AI could help, using practical, feasible capabilities like:

- Summarization
- Prediction
- Personalization
- Recommendation
- Classification
- Anomaly detection
- Natural language understanding/generation
- Automation of repetitive tasks
- Data insights or visualization

For every suggestion, include:

- AI Capability being used
- Brief description of how the AI would work and solve the problem
- A Feasibility & Complexity Score (Low, Medium, or High) based on current AI maturity and likely integration effort

Avoid vague or overly futuristic ideas, stay grounded in what’s actually buildable today.

Return your response in a clean, structured format.
```

---

## Turn an idea into a build-ready spec

### 9. Feature specification generator

Full article: [Design with AI: From Idea to Prototype](https://ileanamarcut.substack.com/p/from-idea-to-prototype-with-ai) · Tool: ChatGPT or any AI assistant

Turns an idea plus your notes and research into a structured spec, ready for design and development.

```
Based on your knowledge and initial research on this topic, help me define a feature specification document for this scope. The goal is to capture everything needed to move from idea to design and development implementation. The output should be structured, including the goal of the feature, a step-by-step user flow, and specifications and requirements.
```

### 10. Specification for AI prototyping tools

Full article: [AI Workflow: Build Fast. Test Faster.](https://ileanamarcut.substack.com/p/ai-workflow-build-fast-test-faster) · Tool: any AI assistant, output aimed at Lovable or Replit

Generates a complete PRD that Lovable or Replit can build a clickable prototype from, with exact labels, states, and edge cases.

```
Please help me design and generate a specification document that an AI prototyping tool (like Lovable or Replit) can use to build a clickable application.

PRODUCT NAME: [Your Product Name]

CONTEXT:
[Describe in 3–7 sentences:
- What the product does
- Who it’s for
- The problem it solves
- Style and design notes (fun, minimal, emoji-friendly, etc.)
- Any specific content you already know (titles, questions, button labels, menu items, footer text, sample recommendations)
- Constraints (e.g. 3 steps only, no backend, mobile-first)]

STRUCTURE THE OUTPUT LIKE THIS:

1. **Product Overview**
- Short description of purpose and main user goal

2. **User Flow**
- Step-by-step path from entry to exit
- For each step, describe actions, system response, and any error/validation states

3. **Screens (with complete text and content)**
For each screen, include:
- Title/header text
- Body content or questions
- All buttons/links with exact text labels and actions
- Menu/footer text
- Option labels with emojis or icons
- Microcopy for errors and validations (e.g. “Please select an option before continuing”)
- Empty states (e.g. “You haven’t saved anything yet”)
- Interaction feedback (highlight selected, disabled states, hover text)

4. **States and Data**
- What data is tracked (answers, selections, saved items)
- Example mock outputs (e.g. exactly 3 recommendations with titles, descriptions, emojis, price, and placeholder images)
- How saved items are stored and displayed (session only, in-memory)

5. **Edge Cases**
- No selection made → Next button disabled + error text
- Empty results or empty saved list → show friendly message
- Restart or exit behavior

6. **Style & Accessibility**
- Design tone (e.g. playful, colorful, emoji-heavy)
- Layout rules (mobile-first, responsive, grid/list where relevant)
- Accessibility basics (keyboard navigation, focus states, ARIA labels)

RULES FOR UNDEFINED FEATURES:
- Never leave dead links or undefined buttons.
- If a feature is mentioned but not fully defined, represent it explicitly with either:
  - a **placeholder screen** (for nav/buttons) OR
  - an **empty state** (for lists).
- Avoid vague ranges or optional wording. Always specify exact numbers, labels, and content.
- Default to in-memory only (no backend/database). If backend features are required, the spec must include exact endpoints, services, and fields. Otherwise simulate them with placeholders.
- Every data object must include enough fields to look realistic in a prototype (at least title + description + emoji/icon, and preferably price + placeholder image or status field).

FINAL OUTPUT:
Return everything in a clear, structured text block with ready-to-use content, error messages, and placeholders, so it can be dropped directly into Lovable or Replit to generate a working clickable application.
```

### 11. Spec check-up

Full article: [AI Workflow: Build Fast. Test Faster.](https://ileanamarcut.substack.com/p/ai-workflow-build-fast-test-faster) · Tool: any AI assistant

Reviews and refines the spec above before you drop it into a prototyping tool.

```
Please review this product specification and refine it so it’s ready to use with an AI prototyping tool (like Lovable or Replit).

Check for:
- Undefined nav items or dead links
- Vague ranges (e.g. “2–3 items”)
- Missing text (buttons, labels, error messages, empty states)
- Data objects that are underspecified (e.g. a “product” without title/description/image/price, a “task” without status/priority/due date)
- Features that require backend logic or 3rd-party services when only in-memory behavior is defined
- Interaction or confirmation states that are not clearly described (what happens after a click)
- Gaps in flow, such as:
  - What happens if a user clicks nav items during a flow (e.g. mid-quiz)
  - What Saved/History screens show (if in nav)
  - Whether saving an item shows confirmation (toast, inline message)
  - Any extra screens or messages needed to make the flow smooth

Fixes:
- Replace vague ranges with exact numbers.
- If a feature is mentioned but not fully defined, always represent it explicitly with either a placeholder screen or an empty state (never remove features).
- Default to in-memory only (no backend/database). If backend features are mentioned (e.g. login, payments, APIs), simulate them with placeholder flows unless endpoints and services are explicitly defined.
- Every button, option, and screen must have a clear label and action. If a button has no real action, link it to a placeholder screen.
- Every data object must include enough fields to look realistic in a prototype (at least 3–4 fields).

Final Output:
1. A short review summary (issues or risks found)
2. A corrected and refined version of the spec, ready for Lovable/Replit
```

---

## Debug the root cause

### 12. Root-cause debug

Tool: any AI coding tool

Use it when the model is stuck in a loop, keeps applying fixes that don't work, or is changing code without clearly understanding why the problem exists.

```
The issue persists.
Issue:
[Brief description of what is not working]

Expected behavior:
[What should happen]

Current behavior:
[What actually happens]

Error / logs (if any):
[Paste error messages or logs]

Relevant code / context:
[code snippet or description]

Change approach.
Analyze the problem from scratch.
Address it from different perspectives.
Identify the root cause.
Fix the problem.

Do not fix anything until the root cause is identified.
Ask if information is missing.
```

---

## Prepare and analyze user interviews

### 13. Interview guide generator

Full article: [AI Workflow: Build Fast. Test Faster.](https://ileanamarcut.substack.com/p/ai-workflow-build-fast-test-faster) · Tool: any AI assistant

Prepares a user testing interview guide from your PRD or prototype.

```
Please help me prepare a user testing interview guide.

Context:
[Paste your PRD, include prototype screenshots, or write a short description of your product/feature]

Persona Description:
[Who you’re testing with]

Research goal:
[What you want to learn, e.g. validate an assumption, test usability, check value]

Assumptions to validate:
[List the key things you want answers to]

Deliverables:
1. 10 open-ended interview questions tailored to my goal, product flow, and persona.
2. 3 follow-up prompts I can use if participants give short answers.
3. A short reminder list of at least 5 common mistakes to avoid (e.g. leading questions, yes/no traps).
```

### 14. Interview analysis in four tables

Full article: [AI Workflow: Build Fast. Test Faster.](https://ileanamarcut.substack.com/p/ai-workflow-build-fast-test-faster) · Tool: ChatGPT, Claude, or NotebookLM

Turns raw transcripts into participant notes, patterns, assumption checks, and answers, always grounded in quotes.

```
Please analyze the following user interview transcripts and output the results in **four tables** using the structure below.

---

1. **Participant Notes Table**

| Participant | Demographics & Background | Key Notes (per screen/topic) | Quotes |

Rules:
- One row per participant.
- Summarize key observations in plain language.
- Include at least 1–2 direct quotes per participant.

---

2. **Patterns & Themes Table**

| Pattern | Supporting Quotes | Users |

Rules:
- Extract up to 6 major themes across all participants.
- Each pattern must include at least one direct quote and list which participants mentioned it.

---

3. **Assumptions Validation Table**

| Assumption | Validated? (Yes/No/Mixed) | Evidence / Quotes |

Rules:
- Use the list of assumptions I provide (or extract implied ones if none are given).
- Mark each assumption as ✅ Yes, ❌ No, or ⚠️ Inconclusive.
- Always include at least one supporting quote.

---

4. **Questions & Answers Table**

| Screen / Step | Question | Answer (Summarized) | Supporting Quotes |

Rules:
- For each of my research questions, summarize what participants said.
- Keep answers short and grounded in quotes.

---

General Rules:
- Always include quotes alongside summaries (don’t paraphrase only).
- If something is unclear or missing, write “Needs human interpretation.”
- Stay grounded in the transcripts (no invented insights).
- Output must be clean, formatted Markdown tables only.
```

---

## Run a quick clarity check

### 15. Quick clarity check

Tool: any AI assistant, attach a screenshot of your screen

A 30 second first-time user test for any screen.

```
Act as a first-time user with no prior context. You open this screen for the first time and have 30 seconds to understand it.

Evaluate it using these criteria:

- Purpose clarity: Is it clear what this product or screen is for?
- Emphasis clarity: What seems most emphasized first based on placement, size, or wording, and does it match the intended purpose?
- Action clarity: Is it obvious what you should do first?
- Language clarity: Are any labels, terms, or numbers ambiguous?

Based only on what you see:
- What is unclear or potentially confusing?
- What do you think this product/service is for?
- What would you expect to do next?

Suggest 3 concrete changes (copy, layout, or CTA) that would most improve clarity. Be specific and practical.
Avoid generic UX advice.
```

---

## Define what your AI should not do

### 16. AI boundaries review

Tool: any AI assistant

A prompt to evaluate boundaries, control, and trust.

```
Review this AI feature from a UX perspective, focusing on behavior, boundaries, and user trust.

Clearly distinguish between suggestion, automation, and decision-making in your evaluation.

Evaluate it against the following:

- Where should the system stop instead of continuing?
- What should it never do, generate, or override?
- When should it ask for input instead of assuming?
- When should it say “I don’t know” or refuse?
- What decisions should always remain with the user?
- Where could the system act too confidently or mislead?
- Where might users feel uncertain about what’s happening?
- What behavior could break trust over repeated use?
- In what situations might the system behave differently for similar inputs?
- What edge cases or failure scenarios are not handled well?

Then:
- Identify the top 3 UX risks
- Suggest concrete improvements to increase clarity, control, and trust

Base your reasoning only on the information available. Avoid assumptions.
```

---

## Turn an image into an interactive particle hero

Full article: [Turn Any Image Into Interactive Particles With Midjourney + Claude Code](https://ileanamarcut.substack.com/p/interactive-particles-midjourney-claude-code)

Three prompts in sequence: generate a portrait in Midjourney, turn it into a cursor-reactive particle hero with Claude Code, then add a live control panel.

### 17. The portrait

Tool: Midjourney

```
Profile portrait of woman facing left, head tilted up, eyes closed, serene,
smooth matte sculptural skin, soft directional studio light,
deep shadow under the jaw and neck, plain seamless pale gray background,
the back of the head dissolving into abstract iridescent glitch fragments,
digital dispersion, monochrome face with prismatic color only in the glitch,
fine grain, editorial, simple one color grey background
--ar 2:1 --chaos 10 --stylize 150
```

For a different vibe, append one of these style references:

```
--sref 2231201766
--sref 4561519008
```

### 18. The particles

Tool: Claude Code, attach your image

```
Use the image I provide to build a full-screen functional hero web page: an image rendered as thousands of white particles of light on black, that the cursor pushes around.

Description:

The image should look like it's made of light — countless tiny white specks, dense where the picture is bright and along its edges, thinning out into the shadows, all floating on a pure black background.
Trace out just the subject in detail — its shape and the light and shadow within it, not a flat silhouette, and remove the background.
At rest it should feel alive but calm — the particles drift and breathe very gently, like dust suspended in still air.
When I move the cursor across it, the particles near the pointer push away and the image parts around them, then drift back into place once I move on. It should work with touch as well as a mouse.
Keep it smooth and crisp on any screen size, and if someone has reduced motion turned on, just show it still.
Make it one self-contained React component.
```

### 19. The control panel

Tool: Claude Code, optional

```
Add a small live control panel on the page so I can tweak it without touching code.
Place it in the upper right corner: minimal panel and collapsable.
Settings options:
- a slider for the number of particles
- a slider for how big each speck is
- a colour picker for the particle colour (default white)
- a slider for the cursor size (how big the pointer is and how far it pushes)
- a dropdown for the cursor style (dot, ring, or crosshair)

Changing any control updates the effect live, and the panel shouldn't fight the artwork.
```

---

## Be found by AI assistants

Full article: [Using Schema to Be Found by AI Assistants](https://ileanamarcut.substack.com/p/using-schema-to-be-found-by-ai-assistants)

Two JSON-LD schema templates plus the short prompt that fills them in with your details. Paste the filled templates into the `<head>` of your site.

### 20. Fill your schema template

Tool: any AI assistant. Paste it with your company details and the two templates below.

```
I want to generate a complete JSON-LD schema for my website using the templates below. Take my answers and populate them into the schema templates provided.
```

Organization schema, for your homepage:

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Your Company Name",
  "legalName": "Your Company Legal Entity",
  "url": "https://www.yourwebsite.com",
  "logo": "https://www.yourwebsite.com/logo.png",
  "description": "Short, clear description of your company and what you do.",
  "sameAs": [
    "https://www.linkedin.com/company/yourcompany",
    "https://www.instagram.com/yourcompany",
    "https://www.threads.com/@yourcompany"
  ],
  "contactPoint": {
    "@type": "ContactPoint",
    "email": "hello@yourcompany.com",
    "contactType": "Customer Relations",
    "areaServed": "Global"
  },
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "Street Address, Suite/Floor",
    "postalCode": "ZIP / Postal Code",
    "addressLocality": "City",
    "addressCountry": "Country Code"
  },
  "founder": [
    {
      "@type": "Person",
      "name": "Founder One Name",
      "jobTitle": "Role / Title",
      "sameAs": [
        "https://www.linkedin.com/in/founderone",
        "https://founderwebsite.com/"
      ]
    },
    {
      "@type": "Person",
      "name": "Founder Two Name",
      "jobTitle": "Role / Title",
      "sameAs": [
        "https://www.linkedin.com/in/foundertwo",
        "https://github.com/foundertwo"
      ]
    }
  ],
  "hasOfferCatalog": {
    "@type": "OfferCatalog",
    "name": "Services",
    "itemListElement": [
      { "@type": "Offer", "itemOffered": { "@type": "Service", "name": "UX Design for AI Products" } },
      { "@type": "Offer", "itemOffered": { "@type": "Service", "name": "Product Strategy" } },
      { "@type": "Offer", "itemOffered": { "@type": "Service", "name": "AI Rapid Prototyping" } },
      { "@type": "Offer", "itemOffered": { "@type": "Service", "name": "Custom Chatbots & Assistants" } },
      { "@type": "Offer", "itemOffered": { "@type": "Service", "name": "Web & Mobile App Development" } },
      { "@type": "Offer", "itemOffered": { "@type": "Service", "name": "Backend & API Integration" } },
      { "@type": "Offer", "itemOffered": { "@type": "Service", "name": "Technical Support & Maintenance" } }
    ]
  }
}
</script>
```

FAQ schema, for your FAQ page:

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [
    {
      "@type": "Question",
      "name": "What does your company do?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "We help teams design and build digital products through UX, strategy, development, and AI."
      }
    },
    {
      "@type": "Question",
      "name": "Do you work with global clients?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Yes. Based in Berlin, we collaborate with startups, product teams, and agencies worldwide."
      }
    },
    {
      "@type": "Question",
      "name": "What kind of services do you provide?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Our services include UX design for AI products, product strategy, web and mobile app development, automation, and custom AI-powered solutions."
      }
    },
    {
      "@type": "Question",
      "name": "Can you join our existing product team?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Absolutely. We often integrate with teams to provide design, development, or AI expertise. We move fast, collaborate openly, and bring senior-level skills without the overhead."
      }
    },
    {
      "@type": "Question",
      "name": "How do I get started?",
      "acceptedAnswer": {
        "@type": "Answer",
        "text": "Just reach out via hello@yourcompany.com — we’ll review your needs and set up a first call."
      }
    }
  ]
}
</script>
```

---

## Build your own Substack dashboard

Full article: [Building a Custom Substack Dashboard With Claude Cowork](https://ileanamarcut.substack.com/p/building-a-custom-substack-dashboard)

Builds a custom Substack dashboard as a Live Artifact, with KPI tiles, growth forecasting, and a weekly scheduled refresh. Needs Claude Cowork with the Claude Chrome extension connected, signed in to your Substack admin.

### 21. The dashboard prompt

```
Build a custom Substack dashboard for [insert your Substack link] as a Live Artifact.

**1. Capture my Substack's data.**

Use the Chrome extension to read my Substack admin (I'll be signed in) and capture all the data accessible there.

**2. Design the dashboard.**

A single page with:

- KPI tiles for:
  - Total subscribers (with weekly net change: new minus unsubs)
  - Paid subscribers
  - Annual revenue
  - 30-day open rate
- A free-to-paid conversion rate tile, computed from paid count and total
- A subscriber growth chart with a horizontal goal line at my target, a dashed forecast at my current growth rate, and a status pill (on track / slightly behind / behind pace)
- A milestone strip below the chart: each round subscriber number I've crossed, the date, the days between, and a lightning bolt on the fastest leg
- 4x "what's working" cards with auto-generated findings from my posts: paid vs free reach, top recent post, open rate trend, posting cadence
- A posts table, sortable, with clickable article links. Use a modern, responsive table component with clean typography and proper spacing
- The standard Substack views laid alongside: acquisition donut, audience overlap, network breakdown, top referring publications

**3. Schedule the refresh.**

Create a weekly task that runs every Monday at 10am, updating only the data, not the layout.
```

---

## Turn your patterns into skills

After enough conversations with your AI, you've built a whole system without noticing. This prompt reads back across your history and turns what you already do into reusable skills, prompts, and frameworks. 👇🏽

### 22. The pattern audit

Tool: any AI assistant that can read your conversation history

```
Look across all my past conversations and projects with you. I want you to spot what I actually do, not what I say I do.

1. Read widely first. Sample my history across topics, not just the recent ones. Don't judge from the titles alone. Look at how I phrase requests and what I push back on.
2. Find the recurrent work. Rank the task types I repeat most, with rough frequency.
3. Find my signature behaviors. The habits, preferences, voice rules, and standards that show up everywhere. These matter more than any single task.
4. Turn them into proposals. For each one give me a Title, a one line Description, Why (the evidence you saw), and Value (what it saves or unlocks). Label each as a Skill, Prompt, or Framework, and say whether it's new or an extension of something I already have.
5. Prioritize. Tell me which three are the highest leverage to build first, and which single principle everything else should sit on.

Be concrete and honest. If something is repetitive but low value, say so. Don't invent patterns to fill the list.
```

---

## About

Explore more frameworks and toolkits on [UX + AI](https://ileanamarcut.substack.com/). Built something with one of these? Say hi on [LinkedIn](https://www.linkedin.com/in/ileanamarcut/).
