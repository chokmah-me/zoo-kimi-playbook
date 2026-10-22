# AGENTS.md — zoo-kimi-playbook

Practitioner playbook for Zoo Code + Kimi for Coding / Kimi Code CLI. Config kit, not an app. Roo Code is discontinued; `.roo/` paths still work in Zoo Code.

## Commands

```powershell
.\setup.ps1 -Target <project>
```

Unix: `./setup.sh /path/to/your/project/`. Copies `.clinerules`, `.roo/`, and `templates/AGENTS.md` if the target has none.

## Work rules

- Volatile facts (model IDs, tiers, quota, prices) live in `REFERENCE.md`. Do not freeze them in this file.
- `/coding/` is subscription-quota. Per-token prices are the separate Open Platform product.
- Prefer Zoo Code's native Kimi Code provider (OAuth) over the legacy OpenAI-compatible Format.

## Pointers

- `README.md` — tracks A/B/C
- `PLAYBOOK.md` — strategy
- `REFERENCE.md` — verified 2026-09-30
- `INSTALLATION_GUIDE.md`
