
## Senior Full-Stack Engineer | TypeScript & Node | Broadcast & Live Production | Developer Tooling

**Core Technologies**

- **Languages:** TypeScript, JavaScript, Python, PHP
- **Frontend:** React
- **Backend:** Node.js
- **Databases:** PostgreSQL, MySQL, MongoDB
- **DevOps & CI/CD:** Docker, docker-compose, GitHub Actions, GitLab CI, CircleCI, AWS CodeBuild, Jenkins, Travis
- **Tooling:** Git, npm, Yarn, uv, Composer

### Over 25 years of experience

- Deliver full-stack web and mobile applications in TypeScript, React, and Node.js across 25+ years in the industry.
- Build reliable, data-driven software on PostgreSQL and MySQL that supports business outcomes.

### Stepping back to simplify

- Re-architected timing for [Sofie **T-Timers**](https://github.com/Sofie-Automation/sofie-core/issues/1601) by moving calculations from the client to the server: running clocks receive only a `zeroTime` (future for countdowns, past for stopwatches/timers), paused clocks receive `remainingTime`, and both update only on state changes, with the client refreshing the display once per second via `setTimeout`.
- Cut timer recalculation from 60/s to 1/s (~98% fewer ticks), substantially reducing frontend workload and enabling new custom timer types for client-specific broadcast workflows.

### Considered a "git wizard" by colleagues

- Delivered company-wide Git talks and built tooling including pre-commit lint hooks to streamline advanced version-control workflows.
- Configured GitHub Actions, GitLab CI, CircleCI, AWS CodeBuild, Travis, and Jenkins for trigger-based test pipelines; contributed a fix to the original GitHub [`hub`](https://github.com/mislav/hub/pull/2704) CLI.
- Updated and improved [`sofie-code-standard-preset`](https://github.com/Sofie-Automation/sofie-code-standard-preset) with additional ESLint, Prettier, and EditorConfig rules to improve code readability, reduce style-driven merge conflicts, and free developers to focus on substance over style; added a setup CLI so new projects can adopt it in one command.
- Maintain [`jamies-git-tools`](https://github.com/rjmunro/jamies-git-tools), including [`git-resolve-formatting-conflicts`](https://github.com/rjmunro/jamies-git-tools/blob/main/doc/git-resolve-formatting-conflicts.md), which automatically fixes formatting-only merge clashes, and [`git-bisect-rebase`](https://github.com/rjmunro/jamies-git-tools/blob/main/doc/git-bisect-rebase.md) to bring long-running branches up to date incrementally rather than resolving every conflict at once.

### Fan of configuration as code

- Engineered [`redash-loader`](https://github.com/rjmunro/redash-loader) to export Redash BI queries and dashboards as version-controlled YAML, SQL, and JSON. Enabled tracked, branchable, and portable analytics configuration across environments.
- Built YAML import/export for [Bitfocus Companion](https://github.com/bitfocus/companion) to manage live A/V and streaming setups.
- Optimized Docker images to runtime-only binaries and orchestrated multi-container stacks with docker-compose.

### Experienced with Agile practices and collaboration

- Led sprint planning, retrospectives, and daily stand-ups in Agile teams.

### Hobbies and Community Contributions

#### Extensive volunteer experience in audio-visual operations

- I direct and vision-mix live multi-camera video for [church YouTube Live streams](https://www.youtube.com/playlist?list=PLKlHRaG4bStPTVxcHOPBFfEOPlX9hHDWl) and in-room IMAG displays and graphics; over 25 years of volunteer A/V experience including camera operating and sound engineering.

#### Significant contributions to open-source data

- Contributed extensively to early MusicBrainz, OpenStreetMap, and Stack Overflow communities.

### Available for my next project

- Delivered major [Sofie](https://github.com/Sofie-Automation/Sofie-TV-automation) TV automation features for the **BBC** and **SVT** through Superfly.
- Based near Oxford; open to remote (global), hybrid, or local on-site.

My Superfly contract is coming to its conclusion; I am now looking for my next project. Feel free to reach out to discuss broadcast automation, full-stack TypeScript, or developer tooling.
