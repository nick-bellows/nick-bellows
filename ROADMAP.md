# Roadmap

Last verified: 2026-09-02

## Handoff snapshot

| Field | Current state |
| --- | --- |
| Lifecycle | `ACTIVE` recruiter routing surface |
| Ground truth | Private resume, then current verified repository evidence |
| Positioning | Senior marketing manager in the soccer industry transitioning into software and data engineering |
| Primary reviewer paths | `learning-center-reference` for software; `fan-unification-platform` for data |

The profile must never imply that Nick currently holds a software-engineer or data-engineer title. It should make the transition credible by connecting resume-backed web, code, analytics, architecture/performance, and business-to-technical work to independently verifiable portfolio systems.

## Current milestone - first-minute recruiter route

Repository-side preparation is complete: the README routes software and data reviewers first, maps the implemented technology stacks to named projects, and `GITHUB_METADATA.md` contains reviewed account metadata. Applying the bio, pins, descriptions, topics, or homepage settings remains an explicit account-level action.

### Work

1. Keep the headline and summary aligned to the current resume title and dates.
2. Put the software and data reviewer paths before secondary projects or technology lists.
3. Link live/static demos only when logged-out checks confirm they work and the corresponding repository documents the claim boundary.
4. Keep certifications and education exact; do not add credentials from memory.
5. Apply the prepared settings in `GITHUB_METADATA.md`, including the six manual pins, only with account-level authorization.
6. Recheck the profile in GitHub's logged-out desktop and mobile views after every material edit.

### Acceptance criteria

- The first screen says `Senior Marketing Manager` and `transitioning into software and data engineering` without apology or title inflation.
- A software reviewer reaches a working soccer workflow in one click.
- A data reviewer reaches a generated identity/warehouse dashboard in one click.
- Every technology named in the profile has inspectable repository evidence.
- Portfolio disclaimers distinguish personal reference implementations from employer systems and real member data.
- No private resume contact details are copied into the README.

## Hosting decision

Use the GitHub profile as the landing page. Do not build or host a separate Vercel/Replit portfolio site yet; it would split reviewer attention and consume time better spent on the Learning Center demo and existing Pages experiences. Reconsider a personal site only after the flagship deployment, pin order, and two reviewer paths are stable.

## Maintenance

- Update selected-project text when a repository's verified lifecycle state changes.
- Remove stale demo links immediately rather than leaving a broken recruiter path.
- Keep the technology table evidence-oriented, not a badge wall.
- Review the profile against the resume before each application cycle.

## Stop conditions

- No invented professional engineering tenure, production deployment, users, metrics, affiliations, or cloud infrastructure.
- No giant badge/logo wall, generic passion statement, or technology included only for search keywords.
- No account-level pin, visibility, topic, or description change without explicit authorization.

## Verification before changing status

Compare each biographical claim to the current resume and each engineering claim to the current repository. Verify all links logged out, check mobile rendering and accessible link text, then inspect the final diff for private information.
