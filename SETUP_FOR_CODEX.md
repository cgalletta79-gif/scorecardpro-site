# Setup For Codex Maintenance

Goal: make Scorecard Pro maintainable by Codex without relying on manual hosting-dashboard clicking.

## Current Site Files

This repository contains the current working site files:

- `index.html` is the main Scorecard Pro page.
- `league.html` is the Golf League page with the five League listings and Event Manager.
- `README.md` describes the project.

## Required Link

The Golf League button in `index.html` must point to:

```html
league.html
```

Do not point the Golf League button to an old Tiiny URL unless that is intentionally changed and tested.

## League Listings

`league.html` should show:

- Tuesday Ladies League
- Tuesday Labors
- Wednesday Owls Club
- Wednesday No Mans
- Thursday RCS
- Event Manager

## Future Codex Workflow

After hosting is connected to this GitHub repository:

1. Tell Codex what needs changing.
2. Codex edits the repository files.
3. Codex verifies links/content in the repo.
4. The host publishes from GitHub.
5. Codex can inspect and fix future issues from the repo.

## Hosting Setup

Connect the host to this GitHub repository if the host supports GitHub deployments.

Repository:

```text
cgalletta79-gif/scorecardpro-site
```

Recommended publish root:

```text
/
```

Recommended entry file:

```text
index.html
```
