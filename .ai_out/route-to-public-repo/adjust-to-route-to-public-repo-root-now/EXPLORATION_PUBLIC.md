# Exploration: Route to Public Repo

## Repository State
- Repo: `Thorg-App/issues-thorg-vscode` - currently used for VSCode extension issue tracking
- Branch: `adjust-to-route-to-public-repo-root-now`
- Status: Clean working tree

## Files to Modify
1. **README.md** - Currently describes this as the issue submission place for Thorg VSCode extension
2. **`.github/ISSUE_TEMPLATE/config.yml`** - Has `blank_issues_enabled: false`, links to old docs and Discord
3. **`.github/ISSUE_TEMPLATE/bug_report.md`** - Bug report template (to be removed)
4. **`.github/ISSUE_TEMPLATE/feature_request.md`** - Feature request template (to be removed)
5. **`.github/ISSUE_TEMPLATE/question.md`** - Question template (to be removed)

## Target
Redirect all issue submissions to: `https://github.com/Thorg-App/thorg-root-public`

## Approach
1. Update README.md with deprecation notice pointing to new repo
2. Remove individual issue templates (bug_report.md, feature_request.md, question.md)
3. Update config.yml to only have a contact link redirecting to the new repo
