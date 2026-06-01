# Architecture

## Project Vision

Recruitment Room is designed to be a simple, contributor-friendly Streamlit application for exploring player data and supporting scouting decisions. The repository starts with documentation and a minimal entrypoint so the eventual application can grow in a controlled way.

## High-Level Architecture

The application will follow a small, layered structure:

- `streamlit_app.py` as the application entrypoint
- `data/` for source files, sample datasets, and imported exports
- `docs/` for project guidance and contributor-facing documentation

The codebase should remain easy to navigate, with a low barrier to entry for new contributors.

## Data Flow

At a high level, data will move through the application in a straightforward sequence:

1. A user uploads or selects a dataset.
2. The application validates and prepares the data.
3. Filters and visualizations are applied.
4. Results are shown in tables and charts.
5. Outputs can be exported for sharing or later analysis.

## Future Module Structure

When implementation begins, modules should be introduced only where they reduce complexity. A future structure may separate data loading, filtering, visualization, scouting logic, and export helpers, but only after those responsibilities are clearly needed.

## Guiding Principles

- Simplicity first: prefer the smallest design that solves the current problem.
- Modularity: separate responsibilities only when it improves readability.
- Contributor friendliness: keep names clear, docs current, and project structure easy to follow.
- Incremental growth: add features in small steps with minimal surface area.