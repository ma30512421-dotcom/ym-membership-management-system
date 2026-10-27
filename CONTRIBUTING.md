# Team Workflow

This file explains how the three team members collaborate in this repository.

## Branches

- `main` always contains the latest **reviewed and approved** version of the project. Do not commit directly to it.
- Every task is done on its own branch created from `main`, using this naming pattern:

| Type of work | Branch name example |
|---|---|
| Documents | `docs/part4-architecture` |
| New feature | `feature/member-management` |
| Bug fix | `fix/expiry-date-calculation` |
| Tests | `test/payment-validation` |

## Commits

- Make small commits, each with one clear purpose.
- Write messages as `type: short description`, where the type is one of:

| Type | Use for |
|---|---|
| `docs` | Documents and diagrams |
| `feat` | A new feature |
| `fix` | A bug fix |
| `test` | Adding or changing tests |
| `chore` | Other small tasks (cleanup, file moves) |

Examples: `docs: add sequence diagram for payment`, `feat: add member search by phone number`.

## Pull Requests and Review

1. Push your branch and open a **pull request** into `main`.
2. Write a short description of what changed and which requirement it relates to (for example FR-15).
3. **At least one other member** reviews it. The author does not approve their own pull request.
4. After approval, merge the pull request and delete the branch.

## Tasks

Tasks are listed in [docs/project-plan.md](docs/project-plan.md). For each task we record the owner and the status (To do, In progress, Review, Done). When a task is finished, update the plan in the same pull request.

## Roles

| Member | Main responsibility |
|---|---|
| Moeen Rebar | Project leader, requirements, documentation |
| Shady Jamil | System design (database and interface) |
| Bilal Taha | Development, testing, and quality checks |

Everyone may work on any task, but the role owner is responsible for the final quality of that area. Every member must be able to explain the parts of the project they contributed to.

## Rules

- Pull the latest `main` before starting a new branch.
- Do not upload passwords, real member data, or temporary files.
- Use clear file names, for example `Part4_Architecture.pdf`.
- Discuss disagreements in the pull request comments or in a group meeting, then record the decision in the pull request.
