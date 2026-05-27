## Review Settings

### What "Important" means
Reserve Important for findings that would break behavior, leak data, or block a rollback.

### Cap the nits
Report at most five Nits per review.

### Do not report
- Anything CI already enforces: lint, formatting, type errors
- Generated files under `src/gen/` or `backend/gen/`
- Dependency updates