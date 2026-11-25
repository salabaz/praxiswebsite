# AGENTS.md

Guidance for AI coding agents working in this repo.

## Branch and deployment

`online` is the only long-lived branch. GitHub Pages builds from it and serves
`https://praxis-braumann.de`; **a merge to `online` is a deploy.**

- Never commit to `online` directly. Branch off it (`content/…`, `fix/…`,
  `chore/…`), open a pull request, merge the pull request.
- Every pull request should pass the `jekyll build` check
  (`.github/workflows/jekyll-build.yml`). Run `bundle exec jekyll build`
  locally when you can.
- Keep branches short-lived and delete them after merge. There is no staging
  branch; do not reintroduce one without a deploy target for it.

## Agent skills

### Issue tracker

Issues and specs live as markdown files under `.scratch/<feature-slug>/`. See `docs/agents/issue-tracker.md`.

### Triage labels

Five canonical roles, label strings equal to their names (`needs-triage`, `needs-info`, `ready-for-agent`, `ready-for-human`, `wontfix`). See `docs/agents/triage-labels.md`.

### Domain docs

Single-context: one `GLOSSARY.md` plus `docs/adr/` at the repo root. See `docs/agents/domain.md`.
