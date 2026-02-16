# Implementor: Route to Public Repo - Summary

## What Was Done

Deprecated this repository (`Thorg-App/issues-thorg-vscode`) and redirected all issue submissions to `https://github.com/Thorg-App/thorg-root-public`.

### Changes

1. **`README.md`** - Replaced content with a deprecation notice that:
   - Clearly states the repo is deprecated
   - Points users to `Thorg-App/thorg-root-public` for issue submission
   - Preserves the reference to Thorg Notes Landing Page documentation

2. **Removed issue templates**:
   - `.github/ISSUE_TEMPLATE/bug_report.md` - deleted
   - `.github/ISSUE_TEMPLATE/feature_request.md` - deleted
   - `.github/ISSUE_TEMPLATE/question.md` - deleted

3. **`.github/ISSUE_TEMPLATE/config.yml`** - Updated to:
   - Keep `blank_issues_enabled: false`
   - Replace the old documentation link with a redirect to `thorg-root-public/issues`
   - Keep the Discord community link

### Decisions

- Used `/issues` suffix on the new repo URL in `config.yml` so clicking it takes users directly to the issues page.
- Kept the deprecation notice concise and action-oriented in the README.

### No Deviations

All steps followed the task specification exactly.
