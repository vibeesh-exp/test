### Description
When raising a PR, include:
- A brief summary of the change or issue fixed
- Purpose and context of the change
- Any dependencies required for this change

---

## Type of changes
- [ ] Bug fix (non-breaking change that fixes an issue)
- [ ] New feature (non-breaking change that adds functionality)
- [ ] Breaking change (fix or feature that impacts existing behavior)

---

### Screenshots (if applicable)
Add screenshots for UI or behavior changes.

---

## Checklist

### Scope & Quality
- [ ] This PR represents **one logical, well-scoped change**
- [ ] Code follows project standards; commits are clean and reviewed
- [ ] Complex or non-obvious logic is **clearly documented or commented**

---

### Architecture & Compatibility
- [ ] Changes align with **microservices principles**
  - No unintended cross-service coupling
  - No direct database access across services
- [ ] Public APIs are **backward compatible** or properly versioned
- [ ] No unintended architectural dependencies are introduced

---

### Database & Data
- [ ] SQL follows project conventions
- [ ] Query performance and indexing have been considered

---

### Testing & Validation
- [ ] Appropriate tests are added/updated and pass locally
- [ ] Error paths and edge cases are covered where applicable

---

### Security & Reliability
- [ ] Authentication and authorization rules are correctly enforced
- [ ] No secrets, credentials, or keys are committed
- [ ] Proper error handling, logging, and resilience patterns are applied

---

### Observability & Operations
- [ ] Logging, metrics, and tracing follow standard conventions
- [ ] Changes are safe for scaling and production deployment
- [ ] Rollback or mitigation strategy has been considered (if applicable)

---

### Dependencies & Documentation
- [ ] Related PRs or downstream dependencies are merged
- [ ] Relevant documentation (README, API docs, configs) is updated

---

## Notes for Reviewers
<!-- Call out areas that need special attention, trade-offs, or context -->
