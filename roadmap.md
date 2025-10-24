# 🗺️ Project Roadmap — Adaptive Astronomy Website

> **Goal:** Build an inclusive, adaptive astronomy website that adjusts its language and content based on the visitor’s profile (age, education level, accessibility needs, etc.).  
> This roadmap outlines the main milestones and development timeline of the project.

---

## 🚀 Phase 1 — Concept and Planning
**Status:** ✅ Completed

**Objectives:**
- Define the main idea and educational purpose of the project.
- Research inclusive and adaptive content design strategies.
- Identify user profiles and accessibility needs.
- Draft initial UX flow and page structure.

**Deliverables:**
- Project overview (`README.md`)
- User personas and accessibility criteria
- Flow diagram and content outline (`docs/arquitetura.md`)

---

## 💻 Phase 2 — Frontend Prototype
**Status:** 🟡 In progress

**Objectives:**
- Build the basic user interface using React and TailwindCSS.
- Create initial pages:
  - Landing page (project intro)
  - Profile form (age, education, accessibility preferences)
  - Adaptive content page (renders text based on profile)
- Implement responsive and accessible design principles.

**Deliverables:**
- `/frontend` folder structure
- Basic navigation flow
- Sample JSON data simulating adaptive content

---

## ⚙️ Phase 3 — Backend and API Development
**Status:** 🔜 Planned

**Objectives:**
- Set up a FastAPI backend to process user profiles.
- Implement endpoints for adaptive content retrieval.
- Connect frontend form responses to backend logic.
- Handle data validation and request management.

**Deliverables:**
- `/backend` with FastAPI application
- `/api/profile` endpoint
- JSON-based content repository

---

## 🧠 Phase 4 — Database Integration
**Status:** 🔜 Planned

**Objectives:**
- Set up a SQLite (or PostgreSQL) database for storing content versions.
- Create models for user profiles, content categories, and difficulty levels.
- Implement ORM (SQLAlchemy) for easy data management.
- Connect backend routes to the database.

**Deliverables:**
- Database schema and migration scripts
- `content` and `profiles` tables
- API returning real content data

---

## ♿ Phase 5 — Accessibility and Inclusion
**Status:** 🔜 Planned

**Objectives:**
- Implement WAI-ARIA standards for assistive technologies.
- Add high-contrast, dyslexia-friendly, and night modes.
- Enable text-to-speech narration (via Web Speech API).
- Plan future support for Libras (Brazilian Sign Language) translation.

**Deliverables:**
- Accessibility mode toggle
- Audio narration functionality
- Accessibility audit report

---

## ☁️ Phase 6 — Deployment and Documentation
**Status:** 🔜 Planned

**Objectives:**
- Deploy the frontend (Vercel) and backend (Render or Railway).
- Create detailed setup instructions.
- Add screenshots and live demo links.
- Open repository for community contributions.

**Deliverables:**
- Live demo URL
- Full documentation under `/docs`
- Contribution guide and license

---

## 🧩 Long-Term Vision (Post-MVP)
- Add gamified learning features (mini quizzes, achievements)
- Implement multilingual support (PT/EN/ES)
- Use NLP to dynamically simplify text
- Integrate interactive astronomy visualizations (Three.js, NASA APIs)
- Expand to include accessibility for cognitive disabilities

---

## 📅 Timeline Summary

| Phase | Description | Status | Target Completion |
|-------|--------------|--------|------------------|
| 1 | Concept & Planning | ✅ Done | Oct 2025 |
| 2 | Frontend Prototype | 🟡 In progress | Nov 2025 |
| 3 | Backend API | 🔜 Planned | Dec 2025 |
| 4 | Database Integration | 🔜 Planned | Jan 2026 |
| 5 | Accessibility Features | 🔜 Planned | Feb 2026 |
| 6 | Deployment & Docs | 🔜 Planned | Mar 2026 |

---

## 📎 References
- [W3C WAI-ARIA Guidelines](https://www.w3.org/WAI/standards-guidelines/aria/)
- [FastAPI Documentation](https://fastapi.tiangolo.com/)
- [TailwindCSS Docs](https://tailwindcss.com/)
- [Inclusive Design Principles](https://inclusivedesignprinciples.org/)

---

**Maintained by:** [Amanda Cabral](https://github.com/amandacabral)  
**Last updated:** October 2025
