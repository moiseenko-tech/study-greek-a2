# study-greek-a2

A repository for studying Modern Greek verbs at A2 level.

## Structure

- `data/verbs.txt` — source of truth: one verb per line, alphabetical order
- `VERBS.md` — topic-grouped tables: verb, past (1st sg.), future (1st sg.), translation; anchor links to CONJUGATIONS.md
- `CONJUGATIONS.md` — full conjugation tables, one H2 per verb, alphabetical order

## Conventions

### Verb forms

Prefer the `-άω` form over the contracted `-ώ` form for Group B1 verbs (e.g. `μιλάω`, not `μιλώ`).

Group B2 verbs (`-ώ/-είς`) have no `-άω` alternate and stay as-is: `αργώ`, `εξηγώ`, `καλώ`, `μπορώ`, `οδηγώ`, `χρησιμοποιώ`.

### Conjugation table format

Each verb in `CONJUGATIONS.md` has a 6-row table in person order (εγώ → εσύ → αυτός/ή/ό → εμείς → εσείς → αυτοί/ές/ά):

```markdown
| Настоящее | Прошлое | Будущее |
|-----------|---------|---------|
| ... | ... | ... |
```

No pronoun column — person is implied by row order.

For impersonal verbs (`αρέσει`, `πρέπει`) use a reduced table with a note explaining usage.
