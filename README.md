# Python-Data-Science-and-Machine-Learning-Bootcamp
Repo for Python Data Science and Machine Learning Bootcamp

## 🔀 Branching Strategy

To keep this project organized and maintain clean workflows, please follow the recommended branch naming conventions below:

| Branch Name       | Purpose                                                                 |
|-------------------|-------------------------------------------------------------------------|
| `main`            | Stable production-ready code. Only merge tested and approved releases.  |
| `develop`         | Active development branch. Integrate features and bugfixes here first.  |
| `test`            | Used for testing workflows, CI setups, or experimental refactors.       |
| `feature/<name>`  | For new features or experiments (e.g., `feature/data-cleaning`)         |
| `bugfix/<name>`   | For fixing specific bugs (e.g., `bugfix/missing-values`)                |
| `hotfix/<name>`   | For urgent fixes to `main` (e.g., `hotfix/broken-import`)               |
| `release/<ver>`   | For prepping a versioned release (e.g., `release/v1.0`)                 |

### 🧠 Notes
- Always create a pull request when merging into `main`, `develop`, or `test`.
- Protected branches require approval from code owners before merging.
- Use descriptive branch names to keep history clean and searchable.
