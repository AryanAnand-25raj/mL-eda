# Contributing

Contributions that make the notebooks clearer, more reproducible, or more
beginner-friendly are welcome.

## Before You Start

1. Open an issue describing the improvement or bug.
2. Create a focused branch from `main`.
3. Install the dependencies listed in `requirements.txt`.

## Notebook Guidelines

- Keep each notebook focused on one learning objective.
- Add short Markdown explanations before major code sections.
- Restart the kernel and run all cells before committing.
- Remove accidental outputs that contain local paths or personal data.
- Do not commit course-provided or restricted datasets. Document their expected
  filenames in `data/README.md` instead.
- Prefer small examples that run with the existing dependencies.

## Pull Requests

- Use a descriptive title and explain what a learner gains from the change.
- Keep unrelated formatting or generated notebook metadata out of the diff.
- Confirm that the notebook runs from top to bottom without errors.
- Update `README.md` when adding, removing, or renaming a notebook.

By contributing, you agree that your contribution will be licensed under this
repository's MIT License.
