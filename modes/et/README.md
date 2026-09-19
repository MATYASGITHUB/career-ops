# career-ops — Ethiopian Market (modes/et/)

This directory contains Ethiopian market-specific contexts for career-ops. The language used is English, but it adopts Ethiopian market realities.

## When to use?

Use `modes/et/` if:
- You are applying to roles in the Ethiopian market (e.g. Ethiojobs, local tech companies, or international companies with local offices).
- You want the evaluation to understand Ethiopian nuances like the ETB currency, local tax norms, and market-specific hiring practices.

## How to activate?

### Method 1 — Per session, by command
Tell Claude at the beginning of the session:
> "Use the Ethiopian market modes from `modes/et/`."

### Method 2 — Persistent, via profile
Add this to your `config/profile.yml`:
```yaml
language:
  modes_dir: modes/et
```

## Missing Modes Fallback
Modes not found in `modes/et/` (such as `scan`, `batch`, `pdf`, etc.) will automatically fallback to using their respective standard English modes from the `modes/` directory.
