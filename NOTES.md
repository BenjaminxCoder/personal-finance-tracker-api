# Project Notes – Personal Finance Tracker API
*Last updated: 2025-12-14*

### Overall Project Milestones
- [x] Sprint 1 – FastAPI server running + /docs visible
- [ ] Sprint 2 – JWT auth complete
- [ ] Sprint 3 – PostgreSQL + Transaction CRUD
- [ ] Sprint 4 – Dockerized & deployed to AWS

---

### Sprint 1 – Project Setup & Basic API Skeleton (Dec 13–19)
**Status**: ✅ Completed 2025-12-14

**What Clicked Instantly**
- FastAPI auto-docs loaded on first try — felt like Express but with zero extra setup
- uvicorn --reload hot-reloading is smooth

**What Felt Clunky / Took Time**
- Looking at the overview of the whole project. However, I broke it down into bit size task.

**Key Lessons**
| Date       | Lesson                                      | Future Application |
|------------|---------------------------------------------|--------------------|
| 2025-12-14 | Always run uvicorn from repo root with full module path | Add run script to README early |
| 2025-12-14 | FastAPI Swagger UI is a massive productivity boost | Prioritize frameworks with built-in docs |

**Gotchas & Fixes**
| Issue                              | Symptom                            | Fix |
|------------------------------------|------------------------------------|-----|
| ModuleNotFoundError: No module named 'app' | Running uvicorn from wrong dir     | `cd` to root → `uvicorn app.main:app --reload` |

**Resources Used**
- FastAPI First Steps: https://fastapi.tiangolo.com/tutorial/first-steps/

---

### Sprint 2 – User Authentication & Security (Dec 20–26)
**Status**: ⏳ In Progress / Not Started

**What Clicked Instantly**
- 

**What Felt Clunky / Took Time**
- 

**Key Lessons**
| Date | Lesson | Future Application |
|------|--------|--------------------|
|      |        |                    |

**Gotchas & Fixes**
| Issue | Symptom | Fix |
|-------|---------|-----|
|       |         |     |

**Resources Used**
- 

---

### Sprint 3 – Database Integration & Transaction CRUD (Dec 27 – Jan 2)
**Status**: ⏳ Not Started
*(repeat same sub-sections as above)*

---

### Sprint 4 – Containerization, Deployment & Polish (Jan 3–10)
**Status**: ⏳ Not Started
*(repeat same sub-sections as above)*