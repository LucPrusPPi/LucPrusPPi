# Observation Diary

## 2026-07-12

### Profile rebuild

- Featured **CyberBook** as INNOCAMP hackathon 1st place (Innopolis 2026, MTS case).
- Removed FastFarmer / private product names from public `lab.svg` and README.
- Visual direction: teal/gold on dark slate (winner accent), less purple badge noise.
- Push target: only `LucPrusPPi/LucPrusPPi` (+ CyberBook metadata). Never FastFarmer.

## 2026-07-08

### Good ideas

- Use the GitHub profile repository `LucPrusPPi/LucPrusPPi` instead of changing unrelated local projects.
- Keep the README client-facing: visible value, stack, workflow, and selected public repositories.
- Mention performance-minded engineering and AVX2-ready math as an engineering direction, not as an empty promise.

### Corrections made

- `gh` CLI was not installed, so GitHub work had to go through the REST API.
- The profile repository did not exist, so the safest path is to create it as a public special repository.
- Existing public repositories are uneven in freshness, so the README should emphasize current engineering focus instead of pretending every old repo is flagship work.

### Misses and risks

- The access token was pasted into the chat. It should be revoked after this setup is complete.
- GitHub profile images depend on third-party badge/stat services; the README still reads correctly if those images fail.

### Resolution

- Prepared a small profile repository with `README.md` and this observation diary.
- Verification target: GitHub API repository creation, file upload, and final content fetch.

## 2026-07-08 follow-up

### What was missed

- The GitHub profile page did not immediately render the special repository README even though the repository and file were public and reachable.
- PandaBook participation was not included in the first version.

### Resolution

- Added `phaeton-oq/PandaBook` as collaboration work in the public profile README.
- Decided to update the visible GitHub bio as a fallback because it appears in the profile sidebar even if GitHub delays profile README rendering.

## 2026-07-08 stack pass

### What improved

- Reworked the profile from generic "developer" copy into a stack-accurate engineering profile.
- Used local project evidence: Rust workspace, FastAPI control server, React 19/Vite UI, TypeScript/Fastify backend, PostgreSQL, Redis, Socket.IO, Playwright, Windows packaging, and PowerShell automation.
- Kept AI-assisted engineering as a workflow signal instead of turning the profile into a joke or backend self-presentation.

### What still needs UI action

- GitHub still needs the profile README to be shared to Overview from the special repository UI if it does not auto-render.
- The Codex Chrome extension is disconnected in the user's browser popup, so direct browser clicking is blocked until the extension connection is restored.

## 2026-07-08 visual cleanup

### What improved

- Removed old public repositories from the README showcase; PandaBook remains as the only external public collaboration.
- Reframed private/current work as directions instead of pretending every old repository is representative.
- Replaced PowerShell in the visible stack badges with C, C++, C#, .NET, and Netwide Assembler to make the profile feel closer to native/performance engineering.
- Reworked copy toward a cleaner left-profile identity: short, product-facing, and less backend-internal.

## 2026-07-08 visual rebuild

### What went wrong

- The previous README was still table-heavy and looked like a technical spreadsheet instead of an awesome-profile style landing block.

### Resolution

- Rebuilt the README around custom SVG visuals, animated typing text, badge walls, a PandaBook card, and a private-lab visual panel.
- Removed stack tables entirely from the visible README.

## 2026-07-08 broken image cleanup

### What went wrong

- External `github-readme-stats` images broke in the public profile and degraded the visual result.
- The inline engineering signature wrapped awkwardly in GitHub's README column.
- `lab.svg` used a top accent line that was too wide and looked heavy.

### Resolution

- Replaced external PandaBook and stats cards with local SVG assets.
- Replaced inline signature text with a local `signature.svg`.
- Shortened and narrowed `lab.svg` so its accent line is contained inside the card.
