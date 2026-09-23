# Publish to GitHub

The repository content is ready to publish under:

`planet-fitness-3-statement-dcf`

Recommended description:

`Work-in-progress 3-statement financial model and DCF valuation of Planet Fitness (NYSE: PLNT), built from public SEC filings in Excel.`

Recommended topics:

`financial-modeling`, `dcf`, `valuation`, `excel`, `three-statement-model`, `finance`, `forecasting`, `fp-and-a`, `planet-fitness`

## GitHub web upload

1. Create a new **public** repository named `planet-fitness-3-statement-dcf`.
2. Do **not** initialize it with a README, .gitignore, or license because those files are already included here.
3. Upload the contents of this folder to the repository root.
4. Commit with: `Add Planet Fitness three-statement model portfolio project`.
5. Add the suggested description and topics under repository settings/details.

## Command-line option

From the folder containing these files:

```bash
git init -b main
git add .
git commit -m "Add Planet Fitness three-statement model portfolio project"
gh repo create planet-fitness-3-statement-dcf --public --source=. --remote=origin --push
```

The `gh` command requires GitHub CLI authentication on your computer.
