```markdown
# 1. Purpose

meta-rails will help visitors work out what materials and tools they need to perform a task and choose the right materials for the job. It will also introduce material-sourcing, delivery and referrals to individual suppliers.

This first version is an information page; interactive services are planned for later.

# 2. Visitors

Visitors are people who need to find the right materials and tools to achieve an objective.

They need to understand how meta-rails could help with material selection, specifications, quantities, suppliers and estimated costs.

Visitors will use phones and laptops. [CHECK]

# 3. Page layout

Build one page with no menu and these six sections, in this order:

1. **The name and one line:** Show “meta-rails” and “What would you want to do today?” first.
2. **Three things worth knowing:** Explain material selection, materials and tools, and sourcing and delivery.
3. **Good to know:** Present the five standalone facts below.
4. **Sign-up section:** Show only “Sign-up opens soon.”
5. **Ask section:** Show only “The chatbot is coming soon.”
6. **Footer:** Show the site name and a short description.

Use static text throughout. The opening question must not look like an input field.

# 4. Content

Browser tab title:

“meta-rails | Materials and tools for your job”

Use the exact page copy below.

## The name and one line

meta-rails

What would you want to do today?

## Three things worth knowing

### Choose materials for your job

We aim to help you find materials suited to what you want to achieve.

### Work out what you need

We aim to help you identify the materials, specifications, quantities and tools your job needs.

### Find sourcing and delivery help

We plan to offer materials for sale, referrals to individual suppliers, and help with sourcing and delivery.

## Good to know

meta-rails plans to suggest materials suited to your task and propose relevant materials it can sell.

Photo-based advice is a planned feature, but photo uploads are not available on this page.

meta-rails plans to help you find where to buy materials, potentially through partner suppliers.

meta-rails plans to check whether it can supply the quantity of material you need.

meta-rails plans to provide estimated costs based on industry averages.

## Sign-up section

Sign-up opens soon.

## Ask section

The chatbot is coming soon.

## Footer

meta-rails

Materials and tools for the job.

# 5. Look and feel

Use a simple, intuitive construction theme with a calm layout.

Suggested palette: [CHECK]

- Page background: warm off-white, `#F7F5F0`.
- Body text: charcoal, `#242424`.
- Headings: deep slate, `#243746`.
- Box backgrounds: white, `#FFFFFF`.
- Box borders: muted grey, `#D5D9DC`.
- Construction accent: amber, `#E8AA32`, used for decorative lines or small details.
- Text on amber: charcoal, `#242424`.

Do not use amber for small text on a white background.

Use the system font stack `system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", sans-serif`. [CHECK]

Use 18px body text with a line height of 1.6, 32px for the main heading, 24px for section headings and 20px for box headings. [CHECK]

Use friendly, direct wording and generous spacing. [CHECK]

Use three simple boxes for the three things worth knowing, stacked vertically on phones. They may sit side by side on wider screens.

Use no photographs or icons in this first version; convey the construction theme through colours, borders and clear typography. [CHECK]

Design for a 390px-wide phone first. Use flexible widths, readable text and approximately 20px side padding. Do not require zooming or allow sideways scrolling.

# 6. Technical rules

- Create one file called `index.html`, with an optional `style.css`.
- Use plain HTML and CSS only.
- Do not use frameworks, libraries, JavaScript or a build step.
- Publish free on Vercel from GitHub, with no custom settings required.
- Use fonts already available on a phone or laptop.
- Include no keys, passwords or real personal details anywhere.
- Do not build form fields, a chat box, photo uploads or other interactive controls yet.
- Every file in the repository is public, including `site-plan.md`.
- Use semantic HTML, a mobile viewport declaration and a logical heading order.
- Keep all future capabilities clearly described as planned.

# 7. Coming in Session 2

Neither the sign-up form nor the chatbot is built yet.

## Sign-up form

The intended sign-up is for promotional offers and help sourcing and delivering materials.

Planned details:

| Detail | Why it is needed |
| --- | --- |
| Name | To address the visitor when responding to their enquiry. [CHECK] |
| Email | To send promotional offers and material-sourcing information. |
| Telephone number | To contact the visitor about sourcing and delivery. |
| Delivery address | To arrange delivery of sourced materials. |

Whether both email and telephone must be required is undecided. [CHECK]

Collect the delivery address only when delivery is requested, rather than at initial sign-up. [CHECK]

Before building, decide how visitors agree to receive promotions and how their details will be stored and handled. [CHECK]

## Chatbot questions and intended answers

1. **“Do you have this material?”**
   The intended service is to advise visitors on suitable materials and suggest relevant materials meta-rails can sell. Actual stock must be confirmed before saying an item is available. [CHECK]

2. **“Can I upload the photo and you advise me on what I need?”**
   Photo-based material suggestions are a desired future capability. Upload support is not part of the first page, and its Session 2 scope needs confirmation. [CHECK] A photo alone may not establish the best material definitively; the chatbot should request missing details before making a recommendation. [CHECK]

3. **“Do you know where I can buy this material?”**
   The intended service is to refer visitors to individual suppliers, potentially partners. Partner identities and supplier information are not yet provided. [CHECK]

4. **“How much quantity do I need?”**
   The stated service is to check whether meta-rails can supply the quantity requested. Calculating how much a job requires is a separate capability; its inputs and calculation method are not yet decided. [CHECK]

5. **“How much would it cost?”**
   The intended service is to provide an estimate based on industry averages. Data sources, currency and how estimates will be updated are not yet decided. [CHECK] Estimates should be identified as estimates rather than confirmed supplier quotations. [CHECK]

The chatbot should use facts supplied by the site owner and acknowledge when those facts do not provide an answer. [CHECK]

The desired experience is that visitors can ask questions and get answers. Answers about stock, suppliers, quantities or prices require supporting information; do not invent them.

## Questions the future service may ask visitors

- What are you trying to solve today?
- What materials do you need to get it done?
- Do you have any specifications for what you need?
- How much quantity do you need?
- Do you need tools?

These questions are recorded for later development, not displayed as fields in this first version.

# 8. Done when

Run these six checks on the live page:

1. A stranger can understand that meta-rails is about choosing materials and tools, with planned sourcing and delivery help.
2. A stranger can find information addressing all five visitor questions in “Good to know.”
3. A stranger can clearly see that sign-up and the chatbot are coming soon.
4. The page addresses all five questions without presenting planned features as currently available.
5. At 390px wide, the page is readable without zooming or sideways scrolling.
6. The page and repository contain nothing forbidden by the technical rules: no frameworks, libraries, JavaScript, build step, secrets, real personal details, form fields or chat box.

Live chatbot answers are a later-session goal and are not a completion check for this first page.

# 9. How to work

Build only what this plan describes.

Ask before adding anything else.

Treat items marked [CHECK] as unconfirmed assumptions. Confirm them before turning them into additional functionality or factual claims.

Do not invent stock availability, supplier partnerships, prices or service guarantees.

When finished:

- List the files you made.
- Go through each of the six “Done when” checks.
- Say whether each check passes.
- If a check cannot be verified, say “Not verified” and explain what remains to be checked.
```
