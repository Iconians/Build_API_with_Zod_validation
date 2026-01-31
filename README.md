# Build API with Zod validation

Build a small REST API with request validation using Zod
**Requirements**

- **Schemas** — Define Zod schemas for at least one POST (or PUT) body (e.g. create user, create post). Use string, number, optional/nullable, and at least one refinement (e.g. `.min()`, `.email()`). No untaught Zod features.
- **Validation** — Validate request body (and optionally query or params) and return 400 with clear messages when validation fails. Use only patterns from Lessons 6.1–6.9 (e.g. `safeParse`, validation middleware).
- **Endpoints** — At least one GET and one POST (or PUT). Responses and errors should be consistent.

**Grading Criteria**

| Criterion | Weight |
|-----------|--------|
| Correct Zod schemas (types and refinements from module) | 25% |
| Validation applied and errors returned (400, clear messages) | 30% |
| API endpoints work and match module skills | 25% |
| Code quality and use only module concepts | 20% |