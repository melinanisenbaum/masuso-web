# AGENTS.md

AI Agent Guide for the +USO Website Repository

This file defines the context, constraints, and working rules for AI agents contributing to the +USO website.

Agents must read this file before generating code, modifying files, or proposing architecture changes.

---

## 1. Project Overview

+USO is a biomaterials venture based in Mar del Plata, Argentina.

The company develops biofabricated materials made from bacterial cellulose and organic industrial residues.

The main material developed by +USO is called **Revium™**.

Revium™ is a bio-based sheet material designed for product design applications such as:

- accessories
- footwear components
- fashion details
- labels and tags
- design objects

The website serves as the main communication and B2B lead generation platform for the material.

---

## 2. Website Goals

The website is primarily a B2B lead generation tool.

The site must help visitors understand:

- what Revium™ is
- what it can be used for
- who is developing it
- how they can collaborate or request information

Main goals:

1. Explain the material
2. Show real applications
3. Communicate sustainability and circular economy
4. Generate collaborations with designers and brands

---

## 3. Target Audience

Primary audience:

- fashion brands
- product designers
- accessory manufacturers
- footwear brands
- companies exploring sustainable materials

Secondary audience:

- research institutions
- innovation ecosystems
- sustainability initiatives

The website should not target DIY or hobby audiences.

Communication should assume professional users evaluating a material.

---

## 4. Material Context (Critical)

Revium™ is the biomaterial developed by +USO.

Revium™ is not a separate company, not a separate brand, and not a new product unrelated to the previous material narrative.

Revium™ is the current name of the biomaterial previously described as “biocuero” (bio-leather).

+USO sells biomaterial sheets. Do not present +USO as a finished product brand.

Correct framing:

> Revium™ is the biomaterial developed by +USO.

Agents must avoid:

- presenting Revium™ as a different product line
- presenting Revium™ as a standalone brand
- presenting +USO as a fashion or product brand

---

## 5. Core Narrative

The project sits at the intersection of:

- biomaterials
- circular economy
- biofabrication
- design innovation

Key ideas to communicate:

- materials grown from biological processes
- valorization of organic industrial residues
- local production
- alternatives to petroleum-based materials
- alternatives to animal leather

Agents should avoid exaggerated sustainability claims.

---

## 6. Website Structure

Current main pages:

- Home
- Material (Revium™)
- Applications
- Sustainability
- About +USO
- Contact

Possible future pages:

- Case Studies
- Research
- Collaborations
- Press

Agents must keep the architecture simple and scalable.

Agents must not introduce new top-level pages unless explicitly requested.

---

## 7. Tech Stack

The website is a lightweight marketing site.

Preferred technologies:

- HTML5
- CSS3
- Vanilla JavaScript

Optional:

- Tailwind CSS
- minimal static frameworks

Agents should avoid:

- heavy frameworks
- complex build pipelines
- unnecessary dependencies

Priority:

- simplicity
- maintainability
- fast loading

---

## 8. Project Structure

<!-- Preferred repository structure:
/public
  /images
  /icons

/src
  /css
  /js
  /components
  /pages

/docs
  AGENTS.md
  brand.md
  revium-material.md
  site-architecture.md -->


Agents should respect the repository structure and avoid unnecessary reorganization.

---

## 9. Development Guidelines

Agents should prioritize:

- semantic HTML  
- clean CSS structure  
- readable JavaScript  
- reusable components when appropriate  

Avoid:

- overengineering  
- large libraries  
- complex abstractions  

---

## 10. Design Principles

Visual identity should communicate:

- material innovation  
- nature + technology  
- biomaterial textures  

Design characteristics:

- minimal  
- clean  
- material-focused  

Use:

- high-quality material images  
- prototype photos  
- process visuals  

Avoid:

- generic sustainability imagery  
- decorative eco clichés unrelated to the material  

---

## 11. Content Writing Rules

Tone:

- professional  
- clear  
- technically credible  

Avoid:

- buzzword-heavy sustainability language  
- marketing exaggeration  
- unsupported claims  

Prefer:

- concrete explanations  
- real applications  
- clear material descriptions  

---

## 12. Lead Generation Strategy

The website should support:

- contact requests  
- collaboration proposals  
- material inquiries  

Forms should prioritize collecting:

- name  
- email  
- company  
- project description  

Forms must remain **simple and frictionless**.

---

## 13. SEO Orientation

Relevant topics include:

- biomaterials  
- biofabrication  
- bacterial cellulose materials  
- sustainable materials  
- bio-based materials  

Agents should avoid keyword stuffing.

SEO should **never reduce readability**.

---

## 14. Content Safety

Agents must **not invent**:

- material properties  
- certifications  
- performance metrics  
- production capacity  
- scientific results  
- laboratory data  
- durability claims  
- environmental metrics not explicitly provided  

If required information is missing, agents must **ask for clarification** instead of inventing data.

---

## 15. Agent Rules

Agents contributing to this repository must:

1. Preserve the identity of Revium™ as the biomaterial developed by +USO  
2. Maintain a consistent project narrative  
3. Prefer simple code solutions  
4. Respect repository structure  
5. Avoid unnecessary dependencies  
6. Avoid unsupported technical claims  

---

## 16. Long-Term Vision

The website may later include:

- sample request system  
- designer collaboration program  
- case studies  
- CRM integration  
- material documentation
- order request  

Agents should write code that allows **future expansion**.

---

## 17. Setup

Install dependencies:
npm install

Run development server:
npm run dev

Build production version:
npm run build


---

## 18. Code Style

### HTML

- Use semantic HTML5 elements  
- Avoid unnecessary div nesting  

### CSS

- Prefer modular CSS files  
- Avoid inline styles  

### JavaScript

- Use modern ES6 syntax  
- Prefer small utility functions  

---

## 19. Naming Conventions

Use **kebab-case** for component, JavaScript, and CSS filenames.

Examples:

- material-card.html  
- application-grid.html  
- contact-form.js  
- material-section.css  

---

## 20. UI Components

Common reusable components may include:

<!-- - hero-section  
- material-card  
- application-card  
- contact-form  
- image-gallery   -->

Agents should reuse existing components when possible and avoid duplicate component patterns.

---

## 21. Design System

<!-- Primary colors:

- #000000  
- #808080  
- #a48672  
- #573422  
- #fdc52c  

Typography:

- Nexa Light  
- Nexa Bold   -->

If these fonts are unavailable in code, agents should use sensible fallbacks without changing the brand direction.

---

## 22. Agent Workflow

Before implementing changes:

1. Inspect repository structure  
2. Check existing components  
3. Reuse components when possible  
4. Avoid duplicating functionality  
5. Keep changes scoped to the task  
6. Do not refactor unrelated areas unless explicitly requested  

---

## 23. Dependencies

Allowed:

- Vanilla JavaScript  
- Tailwind CSS  

Avoid unless explicitly requested:

- React  
- Vue  
- Angular  
- large frameworks or libraries  

---

## 24. Related Documentation

See:

- docs/revium-material.md  
- docs/site-architecture.md  
- docs/brand.md  

---

## 25. Summary

This repository represents a biomaterials project communicating a new material to designers and brands.

Agents should prioritize:

- clarity  
- credibility  
- simplicity  
- material-centered storytelling



