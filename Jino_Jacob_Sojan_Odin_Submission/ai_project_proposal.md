# Project Idea: Odin Study Companion

**Problem:** Students often lose track of learning tasks, practical demos, and evidence required for assessment.

**Solution:** A privacy-conscious web app that lets learners record course milestones, link GitHub work, and generate study questions based on notes they provide.

**MVP features:** coursework checklist; project links; notes; quiz generation from user-provided text; local progress dashboard; exportable progress report.

**Suggested stack:** HTML/CSS/JavaScript or React front end; Node.js API; SQLite/PostgreSQL; optional LLM API behind a server-side proxy; OAuth only if needed. Never expose API keys in browser code.

**Reference review to complete personally:**
- shubhamsaboo/awesome-llm-apps — survey app ideas and patterns
- hannibal046/awesome-llm — review model/resource categories
- markfulton/ai-employees — examine agent workflow ideas
- markus-global/markus — evaluate its architecture and applicability
- stanford-oval/storm — research-assisted writing approach
- HuangLeijiana/novel-agent — multi-step agent orchestration
- ThomasHoussin/Claude-Book — documentation and prompt workflow ideas

**Milestones:** Week 1 UI and data model; Week 2 task tracker; Week 3 quizzes; Week 4 testing and demo. **Ethics:** user consent, citation of source notes, hallucination warnings, and deletion controls.

These are research starting points, not claims that each repository was fully reviewed.
