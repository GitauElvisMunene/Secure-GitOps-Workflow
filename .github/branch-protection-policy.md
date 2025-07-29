# Branch Protection Policy

| Branch Name | Who Can Push Directly | Who Can Merge PRs | Review Required |
|-------------|----------------------|-------------------|-----------------|
| feature/*   | Developers           | Developers        | Not required    |
| develop     | Developers           | Team Leads        | Required        |
| staging     | (No direct push)     | Team Leads        | Required        |
| master      | (No direct push)     | Team Leads        | Required        |

- Only users listed in CODEOWNERS ([@usfadn]) can merge PRs to protected branches.
- Direct pushes to `staging` and `master` are not allowed.
- PR reviews are required for `develop`, `staging`, and `master`. 