# GitHub Profile Cleanup Plan

Target profile: https://github.com/frowingo

Public snapshot checked on 2026-07-03:

- Name: Emre Can Mece
- Bio: `eski repo: frowing37`
- Public repos: 12
- Profile README repo: not found at `frowingo/frowingo`
- `gh` CLI: not installed locally
- Local workspace remote: none

## Priority 1: Profile Surface

Create a new public repository named exactly:

```text
frowingo
```

GitHub will treat `frowingo/frowingo` as the special profile repository. Add `README.md` using the contents of:

```text
github-profile-polish/PROFILE_README.md
```

Recommended profile bio options:

```text
Backend APIs, iOS apps, and product experiments.
```

```text
Go backend + Swift iOS + C#/.NET projects.
```

```text
Building practical software across backend and mobile.
```

Also fill these profile fields:

- Location: `Turkey` or your city if you want it public
- Website: portfolio, LinkedIn, or a pinned project demo
- Email: only if you want public inbound contact

Remove the current bio `eski repo: frowing37` after the old-account migration note is handled in README or repo descriptions.

## Priority 2: Pin The Right Repos

Recommended pinned repos:

1. `houseflowAPI`
2. `houseflowApp`
3. `timora`
4. `aniWidgets`
5. `notifyme-go`
6. `iworfShop-light-api`

Avoid pinning forked migration repos unless they are actively maintained or have strong screenshots/demos.

## Priority 3: Repo Descriptions

Add descriptions to original repos that currently have no description:

```text
houseflowAPI
Go backend API for the Houseflow project.
```

```text
houseflowApp
Swift iOS companion app for the Houseflow project.
```

```text
timora
C#/.NET application experiment focused on clean architecture and practical workflows.
```

```text
surprise
JavaScript web experiment with GitHub Pages support.
```

```text
aniWidgets
Swift widget project for lightweight, glanceable iOS experiences.
```

```text
notifyme-go
Small Go utility for notification-oriented workflows.
```

```text
iworfShop-light-api
Lightweight C#/.NET shop API.
```

## Priority 4: Topics

Suggested topics:

```text
houseflowAPI: go, api, backend, rest-api
houseflowApp: swift, ios, mobile-app
timora: csharp, dotnet
aniWidgets: swift, ios, widgets
notifyme-go: go, cli, notifications
iworfShop-light-api: csharp, dotnet, api, ecommerce
```

Forked repos from `frowing37` should either be:

- kept public and labeled clearly as migrated/archive work, or
- made private if they are not useful for portfolio review.

## Priority 5: README Pass

The three most important repos need a README first:

1. `houseflowAPI`
2. `houseflowApp`
3. `timora`

Use:

```text
github-profile-polish/REPO_README_TEMPLATE.md
```

Minimum sections:

- What it is
- Tech stack
- Features
- Setup
- Screenshots or API examples
- Status / roadmap

## Priority 6: Visual Polish

For profile impact:

- Add one screenshot or short GIF to `houseflowApp`.
- Add example request/response blocks to `houseflowAPI`.
- Add badges only where they say something real: language, build status, platform, license.
- Add licenses to original public repos if you want others to reuse the code.

## Priority 7: Migration Cleanup

Repos forked from `frowing37` currently dominate the most recent repo list because they were forked on 2026-07-01, even though their original pushes are older.

Forked migration repos:

- `ScholarSift-WebScraping`
- `Tefnut-Third_Person_Game`
- `Husion-A-Gym-Website`
- `NLP-Article-Offer`
- `ProductApp-OnionArchitectureExample`

Recommended treatment:

- Put `migrated-from-frowing37` in topics.
- Improve descriptions so they do not look like raw imports.
- Add a short README note: `This project was migrated from my previous GitHub account.`
- Consider unpinning them unless they are still representative of your current work.

