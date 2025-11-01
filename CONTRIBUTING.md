# Contributing to Telster Public

Thank you for your interest in contributing to **Telster Inc.**  
This repository — `telster-public` — is the open hub for documentation, SDKs, and APIs within the Telster ecosystem.  
Our mission: to build a sustainable, intelligent digital world powered by precision and open collaboration.

---

## 🚀 Getting Started

1. **Fork this repository** to your GitHub account.
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/tess-art/telster-public.git
   cd telster-public

3. Install dependencies:

npm install


4. Run the development server:

npm run dev


5. Make your changes in a new branch and test locally before submitting.




---

🌿 Branching Model

We follow a simple, production-safe workflow:

main → Always stable and ready for deployment.

dev → Actively developed; base branch for new features.

feature/<name> → New features, docs, or SDK modules.

fix/<name> → Bug fixes or small improvements.

docs/<name> → Documentation updates.


Example:

git checkout -b feature/add-new-api


---

🧱 Coding Standards

Telster projects follow consistent patterns for clarity and maintainability.

TypeScript

Use strict typing — avoid any.

Prefer interfaces over type aliases for public contracts.

Always include JSDoc comments on exported functions and classes.


Linting & Formatting

Use the configured ESLint and Prettier rules.

Run checks before committing:

npm run lint
npm run format


Commit Messages

Follow the Conventional Commits format:

<type>(scope): short summary

Example:

feat(api): add investor portfolio endpoint
fix(docs): correct SDK usage example

Valid types: feat, fix, docs, style, refactor, test, chore.


---

🧩 Pull Request Guidelines

Before opening a PR:

1. Ensure your branch is up to date with dev.


2. Confirm your code passes all lint and test checks.


3. Provide a clear PR title and description explaining the intent.


4. Reference related issues using:

Closes #issue-number


5. Keep PRs focused — smaller, modular changes are easier to review.




---

🧪 Testing

Telster uses Jest for unit testing.
Add or update tests for any code changes and run them before pushing:

npm test

All tests must pass before merging.


---

🛡️ Security Policy

If you discover a security issue, do not open a public issue.
Instead, email our security team directly at:

📩 security@telsterinc.com

We take all disclosures seriously and will respond promptly.


---

🧠 Documentation Contributions

For updates to docs, SDK guides, or API references:

Edit files under /docs.

Keep tone technical but clear.

Include examples where possible.

Add changelog notes to /docs/changelog.md.



---

⚖️ License

By contributing, you agree that your contributions will be licensed under the same terms as the repository’s existing Apache 2.0 License.


---

<div align="center">
  <sub>© 2025 Telster Inc. — Building the future with intelligence, precision, and purpose.</sub>
</div>
'''
