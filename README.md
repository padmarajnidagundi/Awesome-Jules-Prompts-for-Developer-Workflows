# Awesome-Jules-Prompts-for-Developer-Workflows
A practical, field-tested list of ready-to-use prompts for Jules (by Google Labs)—focused on real developer workflows like refactoring, documentation, testing, CI/CD, and AI-native tasks.

# 🛠️ Everyday Developer Tasks
// Refactor {module/file} to improve readability, modularity, and add explanatory comments.

// Split large functions in {file} into smaller, 
single-responsibility functions.

// Convert callback-based functions to async/await in {file}.

// Migrate deprecated APIs in {file} to recommended newer APIs.

// Identify and remove dead or unused code in {folder/file}.

// Rename variables and functions in {file} to improve semantic clarity.

// Generate sample JSON or YAML config for {service/component}.

// Detect and fix off-by-one errors or boundary condition bugs in {file}.

# 🔍 Debugging & Performance
// Analyze the following error and suggest fixes: "{error message}" in {file} at line {X}.

// Suggest ways to optimize performance hotspots in {function} inside {file}.

// Add defensive coding checks to prevent runtime errors in {file}.

// Review this code block for potential concurrency or race condition issues.

// Add strategic debug-level log statements to help trace flow in {file}.

// Optimize SQL queries used in {function} for performance and readability.

# ✅ Software Testing & quality Assurance
// Generate unit tests for {function} in {file} using {testing_framework}.

// Create integration tests for {feature/module}.

// Write end-to-end (E2E) tests for {user journey/flow}.

// Mock external service calls for test isolation in {file}.

// Improve test coverage for the {module} to reach {desired_coverage}% coverage.

// Convert existing tests in {file} to use {framework} test style (e.g., Jest → Vitest, Pytest → Unittest).

// Add boundary and edge case tests for {function}.

// Generate property-based tests (fuzz tests) for inputs of {function}.

# 📚 Documentation & Knowledge Sharing
// Generate README.md with installation, usage, and contribution instructions for this project.

// Write high-level architecture summary for this repo.

// Auto-generate API docs for {file/module}.

// Add inline docstrings to all public methods in {class} following Google style.

//Summarise the latest commit history into a changelog entry for the next release.

// Generate developer onboarding instructions for this repo.

# ⚙️ CI/CD & Automation
// Create a GitHub Actions workflow to run unit tests on each push.

// Add a CI step for linting with {linter} (e.g., ESLint, Flake8).

// Set up build automation for this {Node/Python/Go} project.

// Add deployment pipeline config for {platform} (e.g., Vercel, Netlify, GCP Cloud Run).

// Write a job in GitHub Actions to automatically label PRs with affected areas (e.g., "backend", "frontend").

// Generate a release workflow that bumps the semantic version based on Conventional Commits.

# 🧑‍💻 Developer Code Modernization & Migration
// Migrate this code from Python 2 to Python 3 syntax and libraries.

// Convert this React class component to a functional component using hooks.

// Rewrite this Express.js route in Fastify.

// Modernize JavaScript codebase by replacing var with let/const and using arrow functions where applicable.

// Update all dependencies and resolve breaking changes (major version upgrades).

// Replace lodash functions with native JavaScript equivalents.

# 🤖 AI-Native + Jules-Specific
// Generate an audio changelog summarizing changes from the past {X} commits.

// Summarize the latest PRs and pending reviews as a Slack-ready status update.

// Propose the next engineering task based on the open issues and recent commits.

// Draft a pull request description for the following branch: {branch_name}.

// Automatically generate missing code comments in this diff before submitting PR.

// Suggest backlog grooming actions based on stale issues and PRs.

// Create a project progress summary for non-technical stakeholders.

# 🔐 Security & Compliance
// Scan this project for common security vulnerabilities.

// Add input validation and sanitization for user inputs in {file}.

// Suggest how to prevent SQL injection in {function}.

// Check for usage of outdated cryptographic algorithms in {file}.

// Add missing authorization checks for protected routes in {API module}.

# 📈 Analytics & Metrics Instrumentation
// Add OpenTelemetry traces to {function/module}.

// Instrument performance metrics for {API endpoint}.

// Insert Google Analytics/GTM event tracking for {frontend feature}.

# 📂 Project Bootstrap & Boilerplate
// Generate a minimal Python CLI tool using Typer.

// Scaffold a React + Vite + TypeScript project with Tailwind CSS.

// Set up a Flask REST API with basic CRUD endpoints.

// Create a .gitignore suitable for a {language/framework} project.

# Prompting Best Practices (for Jules)
✅ Be explicit: State file names, functions, or error messages.

✅ Be action-oriented: Start with verbs like “Refactor”, “Add tests”, “Fix”, “Document”.

✅ Be scoped: Focus on one file/module or clear task per prompt.

✅ Review the Jules plan output before accepting and triggering PRs.

