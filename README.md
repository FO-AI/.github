# FO-AI/.github

Org-wide GitHub defaults for FO-AI. GitHub serves these to every FO-AI repository, private ones
included, unless a repository has its own `.github/ISSUE_TEMPLATE/` folder.

- `.github/ISSUE_TEMPLATE/bug.yml`: the bug report form. It sets the issue type **Bug** and the
  `bug` label. planner-mcp reads bugs by that label and parses the form's `### <label>`
  sections, so keep both stable.
- `.github/ISSUE_TEMPLATE/config.yml`: keeps blank issues available for everything else.

This repository must stay public for GitHub to apply the defaults.
