---
name: Draft Changelog Updates
---

Periodically update CHANGELOG.md with recent changes from git commits.

Instructions:
- Check if CHANGELOG.md exists in the repository
- If it exists, check when it was last updated (using git log on the file)
- Analyze git commits since the last update, up to the last 7 days (maximum 20 commits)
- If it doesn't exist, analyze commits from the last 7 days (maximum 20 commits)
- Update or create CHANGELOG.md with relevant high-level features and bug fixes
- Keep the same level of detail and format as the existing file (if present)
- Focus on user-facing changes, features, and important bug fixes
- Open this as a draft PR when complete