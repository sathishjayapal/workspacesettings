# workspacesettings
For IntelliJ workspace settings

## Overview

This repository contains shared IntelliJ IDEA workspace settings for the project.

## What's included

- `.idea/codeStyles/` — Shared code style configuration (use per-project settings)
- `.idea/inspectionProfiles/` — Shared inspection profile (`Project Default`)
- `.idea/.gitignore` — Excludes personal/local IDE files from version control

## Usage

Clone this repository and copy (or symlink) the `.idea` directory into your project root, or open the project directly in IntelliJ IDEA. The IDE will pick up the shared settings automatically.

## Files excluded from version control

The following files are intentionally excluded via `.idea/.gitignore` as they contain user-specific or machine-specific state:

- `workspace.xml` — Personal IDE layout and local settings
- `shelf/` — Locally shelved changes
- `httpRequests/` — Editor-based HTTP client history
- `dataSources/` and `dataSources.local.xml` — Local datasource credentials
