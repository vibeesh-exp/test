### Description

When you raise a PR, include 
- a summary of the change or issue fix. 
- Relevant motivation and context.
- List any dependencies that are required for this change.

## Type of changes

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] This change requires a documentation update


### Screenshots
Add screenshots (if any)


## Checklist
### Scope & Quality
- [ ] This PR represents **one logical, well-scoped change**
- [ ] Code follows project standards and introduces **no new warnings**
- [ ] I have performed a **self-review** and cleaned up commits
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
- [ ] SQL follows project conventions and **avoids embedded business logic**
- [ ] Schema changes are **versioned, backward compatible, and zero-downtime safe**
- [ ] Query performance and indexing have been considered
- [ ] Sensitive data (PII/secrets) is handled securely

---

### Testing & Validation
- [ ] Appropriate **unit tests** are added or updated
- [ ] All new and existing tests **pass locally**
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
- [ ] CI/CD pipelines pass successfully

---

## Notes for Reviewers
<!-- Call out areas that need special attention or context -->
