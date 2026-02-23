<!-- omit in toc -->
# Contributing to machine-learning

First off, thanks for taking the time to contribute! ❤️

All types of contributions are encouraged and valued. See the [Table of Contents](#table-of-contents) for different ways to help and details about how this project handles them. Please make sure to read the relevant section before making your contribution. It will make it a lot easier for us maintainers and smooth out the experience for all involved. The community looks forward to your contributions. 🎉

> And if you like the project, but just don't have time to contribute, that's fine. There are other easy ways to support the project and show your appreciation, which we would also be very happy about:
> - Star the project
> - Tweet about it
> - Refer this project in your project's readme
> - Mention the project at local meetups and tell your friends/colleagues

<!-- omit in toc -->
## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [I Have a Question](#i-have-a-question)
- [I Want To Contribute](#i-want-to-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
  - [Improving The Documentation](#improving-the-documentation)
- [Styleguides](#styleguides)
  - [Commit Messages](#commit-messages)
- [Join The Project Team](#join-the-project-team)

## Code of Conduct

This project and everyone participating in it is governed by the
[machine-learning Code of Conduct](https://github.com/ptrvsrg/machine-learning/blob/master/CODE_OF_CONDUCT.md).
By participating, you are expected to uphold this code. Please report unacceptable behavior
to .

## I Have a Question

> If you want to ask a question, we assume that you have read the available [Documentation](https://ptrvsrg.github.io/machine-learning).

Before you ask a question, it is best to search for existing [Issues](https://github.com/ptrvsrg/machine-learning/issues) that might help you. In case you have found a suitable issue and still need clarification, you can write your question in this issue. It is also advisable to search the internet for answers first.

If you then still feel the need to ask a question and need clarification, we recommend the following:

- Open an [Issue](https://github.com/ptrvsrg/machine-learning/issues/new).
- Provide as much context as you can about what you're running into.
- Provide project and platform versions (nodejs, npm, etc), depending on what seems relevant.

We will then take care of the issue as soon as possible.

## I Want To Contribute

> ### Legal Notice <!-- omit in toc -->
> When contributing to this project, you must agree that you have authored 100% of the content, that you have the necessary rights to the content and that the content you contribute may be provided under the project licence.

### Reporting Bugs

<!-- omit in toc -->
#### Before Submitting a Bug Report

A good bug report shouldn't leave others needing to chase you up for more information. Therefore, we ask you to investigate carefully, collect information and describe the issue in detail in your report. Please complete the following steps in advance to help us fix any potential bug as fast as possible.

- Make sure that you are using the latest version.
- Determine if your bug is really a bug and not an error on your side e.g. using incompatible environment components/versions (Make sure that you have read the [documentation](https://ptrvsrg.github.io/machine-learning). If you are looking for support, you might want to check [this section](#i-have-a-question)).
- To see if other users have experienced (and potentially already solved) the same issue you are having, check if there is not already a bug report existing for your bug or error in the [bug tracker](https://github.com/ptrvsrg/machine-learning/issues?q=label%3Abug).
- Also make sure to search the internet (including Stack Overflow) to see if users outside of the GitHub community have discussed the issue.
- Collect information about the bug:
  - Stack trace (Traceback)
  - OS, Platform and Version (Windows, Linux, macOS, x86, ARM)
  - Version of the interpreter, compiler, SDK, runtime environment, package manager, depending on what seems relevant.
  - Possibly your input and the output
  - Can you reliably reproduce the issue? And can you also reproduce it with older versions?

<!-- omit in toc -->
#### How Do I Submit a Good Bug Report?

> You must never report security related issues, vulnerabilities or bugs including sensitive information to the issue tracker, or elsewhere in public. Instead sensitive bugs must be sent by email to .

We use GitHub issues to track bugs and errors. If you run into an issue with the project:

- Open an [Issue](https://github.com/ptrvsrg/machine-learning/issues/new). (Since we can't be sure at this point whether it is a bug or not, we ask you not to talk about a bug yet and not to label the issue.)
- Explain the behavior you would expect and the actual behavior.
- Please provide as much context as possible and describe the *reproduction steps* that someone else can follow to recreate the issue on their own. This usually includes your code. For good bug reports you should isolate the problem and create a reduced test case.
- Provide the information you collected in the previous section.

Once it's filed:

- The project team will label the issue accordingly.
- A team member will try to reproduce the issue with your provided steps. If there are no reproduction steps or no obvious way to reproduce the issue, the team will ask you for those steps and mark the issue as `needs-repro`. Bugs with the `needs-repro` tag will not be addressed until they are reproduced.
- If the team is able to reproduce the issue, it will be marked `needs-fix`, as well as possibly other tags (such as `critical`), and the issue will be left to be [implemented by someone](#your-first-code-contribution).

### Suggesting Enhancements

This section guides you through submitting an enhancement suggestion for machine-learning, **including completely new features and minor improvements to existing functionality**. Following these guidelines will help maintainers and the community to understand your suggestion and find related suggestions.

<!-- omit in toc -->
#### Before Submitting an Enhancement

- Make sure that you are using the latest version.
- Read the [documentation](https://ptrvsrg.github.io/machine-learning) carefully and find out if the functionality is already covered, maybe by an individual configuration.
- Perform a [search](https://github.com/ptrvsrg/machine-learning/issues) to see if the enhancement has already been suggested. If it has, add a comment to the existing issue instead of opening a new one.
- Find out whether your idea fits with the scope and aims of the project. It's up to you to make a strong case to convince the project's developers of the merits of this feature. Keep in mind that we want features that will be useful to the majority of our users and not just a small subset. If you're just targeting a minority of users, consider writing an add-on/plugin library.

<!-- omit in toc -->
#### How Do I Submit a Good Enhancement Suggestion?

Enhancement suggestions are tracked as [GitHub issues](https://github.com/ptrvsrg/machine-learning/issues).

- Use a **clear and descriptive title** for the issue to identify the suggestion.
- Provide a **step-by-step description of the suggested enhancement** in as many details as possible.
- **Describe the current behavior** and **explain which behavior you expected to see instead** and why. At this point you can also tell which alternatives do not work for you.
- You may want to **include screenshots or screen recordings** which help you demonstrate the steps or point out the part which the suggestion is related to. You can use [LICEcap](https://www.cockos.com/licecap/) to record GIFs on macOS and Windows, and the built-in [screen recorder in GNOME](https://help.gnome.org/users/gnome-help/stable/screen-shot-record.html.en) or [SimpleScreenRecorder](https://github.com/MaartenBaert/ssr) on Linux.
- **Explain why this enhancement would be useful** to most machine-learning users. You may also want to point out the other projects that solved it better and which could serve as inspiration.

### Your First Code Contribution

Ready to contribute code? Here's how to get started:

#### Setting Up the Development Environment

1. **Fork the repository** — click the «Fork» button at the top right of the [repository page](https://github.com/ptrvsrg/machine-learning).

2. **Clone your fork** locally:

   ```bash
   git clone https://github.com/<your-username>/machine-learning.git
   cd machine-learning
   ```

3. **Add the upstream remote** so you can keep your fork in sync:

   ```bash
   git remote add upstream https://github.com/ptrvsrg/machine-learning.git
   ```

4. **Install dependencies.** Make sure you have Python 3.x installed, then create a virtual environment and install the required packages:

   ```bash
   python -m venv .venv
   source .venv/bin/activate   # on Windows: .venv\Scripts\activate
   pip install -r requirements.txt
   ```

5. **Verify the setup** by running the existing tests or examples to make sure everything works:

   ```bash
   pytest
   ```

#### GitHub Flow Workflow

We follow the **GitHub Flow** branching model. All changes go through short-lived feature branches and pull requests into `master`.

1. **Sync your local `master`** with upstream before starting any work:

   ```bash
   git checkout master
   git pull upstream master
   ```

2. **Create a feature branch** from `master`. Use a descriptive name:

   ```bash
   git checkout -b feature/short-description
   ```

   Branch naming conventions:
   | Prefix | Purpose |
   |---|---|
   | `feature/` | New feature or enhancement |
   | `fix/` | Bug fix |
   | `docs/` | Documentation changes |
   | `refactor/` | Code refactoring |
   | `test/` | Adding or updating tests |

3. **Make your changes.** Keep commits small and focused. Write or update tests for any new functionality.

4. **Run linting and tests** before pushing:

   ```bash
   # Lint
   flake8 .
   # Tests
   pytest
   ```

5. **Push your branch** to your fork:

   ```bash
   git push origin feature/short-description
   ```

6. **Open a Pull Request (PR)** against the `master` branch of the upstream repository:
   - Give the PR a clear, descriptive title.
   - In the description, reference the related issue (e.g., `Closes #42`).
   - Describe **what** was changed and **why**.
   - If the PR is still in progress, open it as a **Draft Pull Request**.

7. **Participate in the code review.** A maintainer will review your PR. Be ready to discuss your changes and make adjustments if requested.

8. **Once approved**, a maintainer will merge your PR. Do not merge your own pull requests unless explicitly told to do so.

#### Tips for a Good Contribution

- Keep pull requests focused — one logical change per PR.
- Write meaningful tests that cover both the happy path and edge cases.
- Follow the existing code style and project conventions.
- Update documentation if your change affects public APIs or user-facing behavior.
- If your contribution is non-trivial, consider opening an issue first to discuss the approach.

### Improving The Documentation

Good documentation is just as important as good code. Here are ways you can help:

- **Fix typos, grammar, and formatting** — even small corrections make a difference.
- **Clarify existing content** — if you found something confusing when reading the docs, others likely did too. Rewrite sections to be clearer.
- **Add missing documentation** — document undocumented features, functions, classes, or modules. Include usage examples where appropriate.
- **Improve docstrings** — make sure public functions and classes have clear, complete docstrings following the project's conventions (e.g., [NumPy-style](https://numpydoc.readthedocs.io/en/latest/format.html) or [Google-style](https://google.github.io/styleguide/pyguide.html#38-comments-and-docstrings) docstrings).
- **Add or update tutorials and examples** — practical examples help users understand how to use the library effectively.

#### How to Contribute Documentation Changes

1. Follow the same [GitHub Flow workflow](#github-flow-workflow) described above.
2. Use a branch with the `docs/` prefix (e.g., `docs/improve-getting-started`).
3. If the project uses a documentation generator (e.g., Sphinx, MkDocs), build the docs locally and verify your changes render correctly:

   ```bash
   # Example for MkDocs
   mkdocs serve
   # Then open http://127.0.0.1:8000 in your browser
   ```

4. Open a Pull Request with a clear description of what was changed and why.

## Styleguides

### Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification. This leads to a readable commit history and enables automated changelog generation.

#### Format

```
<type>(<optional scope>): <short summary>

<optional body>

<optional footer(s)>
```

#### Type

Must be one of the following:

| Type | Description |
|---|---|
| `feat` | A new feature |
| `fix` | A bug fix |
| `docs` | Documentation only changes |
| `style` | Changes that do not affect the meaning of the code (formatting, missing semicolons, etc.) |
| `refactor` | A code change that neither fixes a bug nor adds a feature |
| `perf` | A code change that improves performance |
| `test` | Adding missing tests or correcting existing tests |
| `build` | Changes that affect the build system or external dependencies |
| `ci` | Changes to CI configuration files and scripts |
| `chore` | Other changes that don't modify src or test files |
| `revert` | Reverts a previous commit |

#### Rules

- Use the **imperative, present tense** in the summary: «add feature», not «added feature» or «adds feature».
- **Do not** capitalize the first letter of the summary.
- **Do not** end the summary with a period.
- Keep the summary line to **72 characters or fewer**.
- Use the body to explain **what** and **why**, not **how**.
- Reference issues and pull requests in the footer (e.g., `Closes #123`).

#### Examples

```
feat(knn): add weighted distance voting

Implement weighted k-nearest neighbors where closer neighbors
have a larger influence on the prediction.

Closes #27
```

```
fix(regression): handle singular matrix in OLS

Add a check for singular matrices before inversion and fall back
to pseudo-inverse when necessary.

Fixes #45
```

```
docs: update installation instructions in README
```

```
refactor(tree): extract node splitting logic into separate module
```

## Join The Project Team

Interested in becoming a regular contributor or maintainer? Here's how:

1. **Start by contributing.** Open several quality pull requests, participate in issue discussions, and help review other contributors' PRs.
2. **Be consistent.** Regular, reliable contributions over time demonstrate commitment to the project.
3. **Show initiative.** Help triage issues, answer questions from other users, improve CI/CD pipelines, or propose architectural improvements.
4. **Reach out.** Once you've built a track record, open an issue or send an email to expressing your interest in joining the team. Include links to your contributions.

Maintainers are chosen based on:

- Quality and consistency of contributions.
- Understanding of the project's goals and codebase.
- Ability to provide constructive, respectful code reviews.
- Willingness to help other contributors.

Current roles:

| Role | Responsibilities |
|---|---|
| **Contributor** | Submit PRs, report bugs, suggest features |
| **Triager** | Label and categorize issues, identify duplicates |
| **Maintainer** | Review and merge PRs, manage releases, guide project direction |

<!-- omit in toc -->
## Attribution
This guide is based on the [contributing.md](https://contributing.md/generator)!