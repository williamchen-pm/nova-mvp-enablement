# NOVA — Sales & Support Enablement Prototype

▶ [View the live prototype](https://williamchen-pm.github.io/nova-mvp-enablement/)

An interactive enablement walkthrough for the MVP release of an AI assistant embedded in a multi-tenant security management platform. Built for the people who have to explain it: sales engineers, partner-facing sellers, and support.

---

## About this version

I am the original author of this enablement guide. I designed and built it during my professional work as a product manager, and this copy is published here as a portfolio piece with all proprietary content removed.

Company and product names, hardware models, firmware versions, internal identifiers, backend system references, and commercial terms have been replaced with generic equivalents. All accounts, alerts, and figures shown are illustrative. No confidential material, customer data, or pricing is included.

---

## The problem

A new AI capability does not get adopted because it shipped. It gets adopted because the people in front of customers can explain what it does, what it does not do, and why it is worth turning on. At MVP that explanation usually does not exist yet. Sales engineers improvise, support fields questions they were never briefed on, and partners hear four different versions of the same answer.

The gap is rarely the product. It is that enablement material shows up as a slide deck describing an interface nobody has used, which is a poor way to learn something interactive.

## What this prototype does

- **Teaches inside the real interface** — the walkthrough runs alongside a working copy of the platform, so the person learning is clicking the thing they will demo rather than reading about it
- **Gives sellers language, not features** — each step pairs the action with suggested narrative for the customer conversation and a support angle covering what to know underneath it
- **Anticipates how customers actually ask** — every use case includes phrasing variants, because customers rarely use the words in the datasheet
- **Handles the awkward questions directly** — data handling, model training, and usage limits are scripted rather than left for someone to improvise badly in front of a partner
- **Covers the whole MVP surface** — organized as sequential use cases so a new hire can work through it end to end, or an experienced SE can jump to the one they need

## Why it was built this way

Adoption of an embedded assistant is a distribution problem before it is a product problem. The capability was already built; what determined whether it got used was whether the field could position it confidently. Making the enablement interactive and grounded in the live interface meant the first time someone demoed it to a partner was not the first time they had used it.

The wider goal was platform pull. An assistant that sellers can demo well makes the platform underneath it more compelling, which matters when the surrounding product is competing on more than feature count.

---

**Role:** Product Manager. I led the execution for the assistant this prototype represents, defined use cases, and produced enablement materials.

**Stack:** HTML, CSS, JavaScript · React

**Note:** Design prototype for demonstration purposes. All data shown is illustrative.

---

© William Chen. Published for portfolio review. Not licensed for reuse or redistribution.
