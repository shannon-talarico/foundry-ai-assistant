# Development Workflow

## Branch Naming Conventions

Foundry uses a lightweight Git workflow with descriptive branch prefixes.

### feature/

Used for new functionality and product capabilities.

Examples:

* feature/add-production-partner-api
* feature/create-order-dashboard
* feature/add-openai-integration

---

### docs/

Used for documentation updates.

Examples:

* docs/update-readme
* docs/foundry-vision
* docs/development-workflow

---

### fix/

Used for bug fixes.

Examples:

* fix/order-status-validation
* fix/login-error-handling

---

### chore/

Used for maintenance, configuration, and tooling updates.

Examples:

* chore/update-dependencies
* chore/setup-github-actions
* chore/add-docker-compose

---

### hotfix/

Used for urgent production issues requiring immediate attention.

Examples:

* hotfix/payment-processing-error
* hotfix/order-routing-production-bug

---

### spike/

Used for research, proof-of-concepts, and technical investigations.

Examples:

* spike/shopify-webhook-research
* spike/aws-ecs-deployment
* spike/rag-experiment

---

## Development Process

1. Update local main branch.
2. Create a new branch.
3. Implement changes.
4. Commit with meaningful messages.
5. Push branch to GitHub.
6. Create Pull Request.
7. Review changes.
8. Merge into main.
9. Delete merged branch.

---

## Commit Message Conventions

Examples:

* feat: add production partner entity
* docs: update Foundry vision
* fix: handle invalid order status
* chore: update Spring Boot version

Commit messages should describe what changed and why.