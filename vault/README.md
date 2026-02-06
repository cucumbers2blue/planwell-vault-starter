# PlanWell Vault Starter (Vault Docs)

Starter vault for PlanWell apps (Pro, Web, Desktop).

## Folder Structure

```text
classes/
events/
categories/
todos/
settings/
  periods.md
  term-settings.md
README.md
CONTRIBUTING.md
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

See `CONTRIBUTING.md` in this folder for contribution rules.
