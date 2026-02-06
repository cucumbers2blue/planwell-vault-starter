# PlanWell Vault Starter

Starter vault for PlanWell apps (Pro, Web, Desktop).

## Get Started

### Option 1: Download ZIP (Recommended)
- Download the latest starter vault ZIP from Releases:
  - `https://github.com/cucumbers2blue/planwell-vault-starter/releases/latest/download/starter-vault.zip`

### Option 2: Clone Repository
```bash
git clone https://github.com/cucumbers2blue/planwell-vault-starter.git
```

## Vault Structure

```text
vault/
  classes/
  events/
  categories/
  todos/
  settings/
    periods.md
    term-settings.md
```

## Pro App Setup

1. Open Pro config: `~/.planwell/pro.toml`
2. Set:
```toml
vault_path = "/absolute/path/to/planwell-vault-starter/vault"
```
3. Save config and reload Pro.

## Best Practices

- Keep one markdown file per event/todo/category.
- Use `occurrence 1`, `occurrence 2`, ... (space, not hyphen) for recurring classes.
- Use `category` names in `events/*.md` that exist in `categories/*.md`.
- Use Monday dates for `weekStartDate` in weekly todos.
- Keep IDs filename-based and human-readable.

## Contributing

- Open issues for schema questions, starter improvements, and sample data suggestions.
- Submit PRs with clear before/after examples.

See `CONTRIBUTING.md` for details.
