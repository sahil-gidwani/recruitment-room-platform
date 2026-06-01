# Contribution Guide

## Finding an Issue

Start with the issue list and look for work that matches your experience level and available time. Good first issues, documentation tasks, and small bug fixes are usually the easiest place to begin.

## Claiming an Issue

If you want to work on an issue, leave a comment saying that you are interested and plan to take it on. Mention any questions you have and wait for confirmation before starting if the issue might overlap with other work.

## Branch Naming Conventions

Use one of these branch patterns:

- `feature/<feature-name>`
- `bugfix/<issue-name>`
- `docs/<topic>`

Examples:

- `feature/player-comparison`
- `feature/radar-chart`
- `bugfix/filter-error`
- `docs/setup-guide`

## Creating a Feature Branch

Create a new branch from `main` after the issue is claimed. Keep the branch name short and descriptive so it is easy to understand in pull requests and project boards.

## Making Changes

Keep the change small and focused on the issue you claimed. One feature per pull request is preferred, and documentation updates should stay limited to the topic being addressed.

## Opening a Pull Request

Open a pull request as soon as the work is ready for review. Include a clear summary, link the related issue, and add any screenshots or validation notes that help explain the change.

## Responding to Review Feedback

Treat review comments as part of the collaboration process. Reply clearly, make the requested changes where appropriate, and explain any tradeoffs when a suggestion cannot be applied directly.

## Merging After Approval

Merge only after the pull request has approval and the checklist is complete. The merge should be simple to understand, easy to review, and aligned with the issue that was originally claimed.

## Pull Request Workflow

1. Find an issue that matches the work you can take on.
2. Comment on the issue to claim it.
3. Create a feature branch.
4. Make changes in small, focused steps.
5. Open a pull request with the template.
6. Respond to review feedback.
7. Merge after approval.

## Contributor Principles

- Keep pull requests small and focused.
- Aim for one feature per pull request.
- Discuss large features before implementation.
- Prioritize readability over complexity.
- Be respectful during reviews.

## GitHub Labels

Recommended labels for the project:

- `good first issue`
- `help wanted`
- `frontend`
- `backend`
- `data`
- `visualization`
- `scouting`
- `documentation`
- `enhancement`
- `bug`

Use labels to help contributors quickly find work that matches their experience and to help maintainers group issues by topic.

## GitHub Projects Workflow

Use a simple board with these columns:

- Backlog
- Ready
- In Progress
- Review
- Done

Move issues from Backlog to Ready when they are understood and unblocked. Move work to In Progress when someone has claimed it, to Review when a pull request is open, and to Done after approval and merge.

## Coding Standards

Keep the codebase simple, readable, and consistent. Prefer clear names, small files, and minimal abstractions. Avoid introducing complexity that is not needed for the current milestone.

## Review and Merge Standards

Review should focus on clarity, correctness, and maintainability. Approvals should confirm that the change matches the issue, is easy to understand, and does not introduce unnecessary complexity.

## Maintainer Guidelines

- Review for readability, scope, and alignment with the roadmap.
- Require approval before merging pull requests.
- Merge only when the checklist is complete and checks are green.
- Close or unassign inactive issues and pull requests after a reasonable period of no response.
- Reopen or re-triage issues when new information appears.