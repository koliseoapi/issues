# GitHub Labels Configuration

This document describes the labels that should be configured for this repository.

## Type Labels

| Label | Color | Description |
|-------|-------|-------------|
| `bug` | #d73a4a | Something isn't working as expected |
| `feature-request` | #a2eeef | Suggestion for new functionality |
| `enhancement` | #84b6eb | Improvement to existing functionality |
| `documentation` | #0075ca | Related to documentation |
| `question` | #d876e3 | General questions about the platform |

## Status Labels

| Label | Color | Description |
|-------|-------|-------------|
| `confirmed` | #0e8a16 | Issue has been verified by the team |
| `assigned` | #fbca04 | Someone is working on this issue |
| `in-progress` | #c5def5 | Work is actively being done |
| `solved` | #1d76db | Issue has been resolved |
| `wontfix` | #ffffff | Issue will not be addressed |
| `duplicate` | #cfd3d7 | Issue already exists elsewhere |
| `needs-info` | #d93f0b | More information needed from the reporter |

## Priority Labels

| Label | Color | Description |
|-------|-------|-------------|
| `priority-high` | #b60205 | Critical issue that needs immediate attention |
| `priority-medium` | #fbca04 | Important but not critical |
| `priority-low` | #0e8a16 | Nice to have, lower priority |

## Setup Instructions

To set up these labels in the repository, a maintainer with admin access can:

1. Go to the repository Settings
2. Navigate to Issues > Labels
3. Create each label with the specified name, color, and description

Alternatively, labels can be managed programmatically using the GitHub API or CLI tools.

### Using GitHub CLI

```bash
# Type labels
gh label create "bug" --description "Something isn't working as expected" --color "d73a4a"
gh label create "feature-request" --description "Suggestion for new functionality" --color "a2eeef"
gh label create "enhancement" --description "Improvement to existing functionality" --color "84b6eb"
gh label create "documentation" --description "Related to documentation" --color "0075ca"
gh label create "question" --description "General questions about the platform" --color "d876e3"

# Status labels
gh label create "confirmed" --description "Issue has been verified by the team" --color "0e8a16"
gh label create "assigned" --description "Someone is working on this issue" --color "fbca04"
gh label create "in-progress" --description "Work is actively being done" --color "c5def5"
gh label create "solved" --description "Issue has been resolved" --color "1d76db"
gh label create "wontfix" --description "Issue will not be addressed" --color "ffffff"
gh label create "duplicate" --description "Issue already exists elsewhere" --color "cfd3d7"
gh label create "needs-info" --description "More information needed from the reporter" --color "d93f0b"

# Priority labels
gh label create "priority-high" --description "Critical issue that needs immediate attention" --color "b60205"
gh label create "priority-medium" --description "Important but not critical" --color "fbca04"
gh label create "priority-low" --description "Nice to have, lower priority" --color "0e8a16"
```
