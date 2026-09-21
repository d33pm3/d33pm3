# Publish checklist — d33pm3 profile README

## What this pack is

Dark terminal / GRC HUD for https://github.com/d33pm3

Motion (three beats only):
1. Scanline + CRT equalizer banner (`assets/grc-hud-banner.svg`, GIF fallback beside it)
2. Typing header (readme-typing-svg)
3. Contribution snake (GitHub Action → `output` branch)

## One-time publish

1. Create a **public** repository named exactly `d33pm3` under user `d33pm3`.
2. Copy these paths to the default branch (`main`):
   - `README.md`
   - `assets/grc-hud-banner.svg`
   - `assets/grc-hud-banner.gif` (optional fallback; README uses the SVG)
   - `.github/workflows/snake.yml`
3. Repo → Settings → Actions → General → allow Actions and permit `GITHUB_TOKEN` to write.
4. Actions → `contribution-snake` → Run workflow.
5. After the `output` branch exists, refresh https://github.com/d33pm3 — snake appears under BUILD LOG.
6. Change the GitHub **profile bio** (Settings → Profile). Current bio is “Curious Student - For Life.” Suggested:
   `GRC Professional · Governance, Risk, Finance, Internal Audit, Regulatory Compliance · RegTech systems`
7. Pin original repos: Reg-Extract, Policy-Extract, sebi-compliance-manager, SEBI-India-Compliances, Multi-agent-Full-Stack-App, Powergrid-India.

## What was left out on purpose

- Forks (n8n, MinerU, CPython, Metasploit, etc.)
- Ecommerce / jewelry demos
- Email
- Trophies, skill-icon walls, matrix rain

## If the snake image 404s

The workflow has not written the `output` branch yet. Run it manually. Banner and typing do not depend on it.

## If you later want CRT contribution instead of snake

Swap the BUILD LOG image for a generated CRT SVG (e.g. stefashkaa/github-profile-crt Action). Keep only one contribution widget.
