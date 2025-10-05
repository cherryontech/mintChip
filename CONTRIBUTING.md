# Contributing Guide 🛠️

Thank you for your interest in contributing to this project! We value all contributions, from new features ✨ and bug fixes 🐛 to documentation improvements 📚.

## Before You Start 🚦

Please, before investing time in a significant contribution, **discuss the change** you wish to make with the repository maintainers via an **issue** 💬 or email 📧. This ensures your work aligns with the project's vision.

---

## Pull Request (PR) Process 📤

To maintain code quality and consistency, please follow these steps when submitting a Pull Request:

### Requirements ✅

1.  **Build Cleanup**: Ensure any install or build dependencies are **removed** 🗑️ before the end of the layer when doing a build.
2.  **Documentation**: **Update the `README.md`** 📝 with details of changes to the interface. This includes new environment variables, exposed ports, useful file locations, and container parameters.
3.  **Versioning**: **Increase the version numbers** 🔢 in any example files and the `README.md`. The versioning scheme we use is [SemVer](http://semver.org/).

## 🏷️ Commit Conventions

We strictly follow the **[Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)** standard for our messages. The commit header is the most crucial part and must adhere to this format: `<type>(<optional scope>): <concise description>`

⚠️ **Important:** Ensure your header is within the **50-character limit** and is written in the **imperative mood** ("Add," "Fix," "Refactor," etc.).

| Part | Description | React/Front-End Example |
| :--- | :--- | :--- |
| **`<type>`** | Defines the **category of the change** (e.g., `feat`, `fix`, `refactor`). This dictates the intent and helps with automated changelogs. | `feat:` or `fix:` |
| **`(<optional scope>)`** | (Optional) Specifies the **area of the codebase** affected. Use component, hook, or module names. | `(UserProfile)` or `(useAuth)` |
| **`<concise description>`** | A brief, clear summary of what the change does. Must be in the imperative mood. | `prevent infinite loop on profile fetch` |

**Full Example:** `fix(useAuth): prevent infinite loop on profile fetch`

---

Please use the appropriate type for each change:

| Type | Purpose | Example (with scope) | Simple Example |
| :--- | :--- | :--- | :--- |
| **`feat`** ✨ | Introduces a new feature or user-facing functionality. | `feat(header): add dark mode toggle button` | `feat: implement user preference settings page` |
| **`fix`** 🐛 | Corrects a user-facing bug or unintended behavior. | `fix(auth): redirect user after successful login` | `fix: prevent layout shift on mobile menu open` |
| **`refactor`** 🔨 | Code change that improves internal structure **without altering behavior**. | `refactor(components): convert class component to hook` | `refactor: simplify prop drilling using Context` |
| **`perf`** ⚡ | Changes that improve performance, rendering speed, or bundle size. | `perf(lazy): use React.lazy for all route components` | `perf: optimize expensive calculation in useMemo` |
| **`style`** 🎨 | Changes that **do not alter code logic** (formatting, CSS, etc.). | `style(css): remove unused classes from main stylesheet` | `style: standardize indentation to 2 spaces` |
| **`test`** 🧪 | Adds missing tests or corrects existing tests. | `test(utils): add unit tests for date formatter hook` | `test: mock API responses for Profile component` |
| **`docs`** 📚 | Changes limited to documentation (README, JSDoc comments, etc.). | `docs(readme): update testing instructions section` | `docs: correct component prop descriptions` |



### Approval and Merging 🤝

For a PR to be merged, it must meet the following approval rules:

* **Required Approvals**: Sign-off from **two other developers** is required.
* **Merging Responsibility**:
    * You **may merge the Pull Request** in once you have the sign-off of the two reviewers.
    * If you do not have permission to do that, you may request the **second reviewer to merge it** for you. 🚀

---

## Code of Conduct 🌟

To foster a positive and productive collaboration environment, all participants must adhere to our Code of Conduct.

### Our Pledge ✋

We pledge to making participation in our project and our community a **harassment-free experience** 😇 for everyone, regardless of age, body size, disability, ethnicity, gender, experience, or any other personal characteristic.

### Our Standards 👍

Examples of behavior that contributes to creating a positive environment include:

* Using welcoming and inclusive language 💖
* Being respectful of differing viewpoints and experiences 🤔
* Gracefully accepting **constructive criticism** 👂
* Focusing on what is best for the community 🎯
* Showing empathy towards other community members 🤗



*This Code of Conduct is adapted from the Contributor Covenant.*
