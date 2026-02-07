# Contributing to [Project Name]

👍🎉 First off, thanks for taking the time to contribute! 🎉👍

This project is part of the **NIT Raipur Open Source Organization**, and we're excited to have you here. Whether you're fixing a bug, adding a feature, or improving documentation, every contribution matters.

---

## 📋 Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)
- [Commit Message Guidelines](#commit-message-guidelines)
- [Issue Labels](#issue-labels)
- [Community](#community)

---

## 📜 Code of Conduct

This project adheres to our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the maintainers.

---

## 🤔 How Can I Contribute?

### 🐛 Reporting Bugs

Found a bug? Help us improve by reporting it!

1. **Check existing issues** to avoid duplicates
2. **Use the bug report template** when creating an issue
3. **Provide detailed information:**
   - Clear title and description
   - Steps to reproduce
   - Expected vs actual behavior
   - Screenshots (if applicable)
   - Your environment (OS, version, etc.)

### 💡 Suggesting Features

Have an idea? We'd love to hear it!

1. **Check existing feature requests** to avoid duplicates
2. **Use the feature request template**
3. **Explain the problem** your feature solves
4. **Describe your proposed solution**
5. **Consider alternatives** you've thought about

### 📝 Improving Documentation

Documentation is just as important as code!

- Fix typos or clarify confusing sections
- Add examples or tutorials
- Improve README or guides
- Translate documentation (if applicable)

### 💻 Contributing Code

Ready to code? Here's how:

1. **Find an issue to work on:**
   - Look for [`good first issue`](../../issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22) labels
   - Check [`help wanted`](../../issues?q=is%3Aissue+is%3Aopen+label%3A%22help+wanted%22) issues
   - Ask maintainers if you need guidance

2. **Comment on the issue** to let others know you're working on it

3. **Follow the development workflow** (see below)

---

## 🚀 Getting Started

### Prerequisites

<!-- Update based on your project -->
- [Tool/Language] version X.X+
- [Package Manager]
- Git

### Fork & Clone

```bash
# Fork the repository on GitHub (click the Fork button)

# Clone your fork
git clone https://github.com/YOUR-USERNAME/[project-name].git

# Navigate to directory
cd [project-name]

# Add upstream remote
git remote add upstream https://github.com/nitrr-oss/[project-name].git
```

### Setup Development Environment

```bash
# Install dependencies
[package-manager] install

# Copy environment variables (if applicable)
cp .env.example .env

# Run setup scripts (if any)
[setup commands]

# Verify installation
[test command]
```

---

## 🔄 Development Workflow

### 1. Create a Branch

```bash
# Update your fork with latest changes
git checkout main
git pull upstream main

# Create a new branch
git checkout -b feature/your-feature-name
# OR
git checkout -b fix/bug-description
```

**Branch naming conventions:**
- `feature/feature-name` - For new features
- `fix/bug-description` - For bug fixes
- `docs/description` - For documentation changes
- `refactor/description` - For code refactoring
- `test/description` - For test additions

### 2. Make Your Changes

- Write clean, readable code
- Follow the project's style guide (see below)
- Add tests for new functionality
- Update documentation if needed
- Test your changes thoroughly

### 3. Test Your Changes

```bash
# Run tests
[test command]

# Run linter
[lint command]

# Build project (if applicable)
[build command]
```

### 4. Commit Your Changes

```bash
# Stage your changes
git add .

# Commit with a descriptive message
git commit -m "feat: add amazing feature"
# See commit message guidelines below
```

### 5. Push to Your Fork

```bash
# Push your branch
git push origin feature/your-feature-name
```

### 6. Open a Pull Request

1. Go to the original repository on GitHub
2. Click "New Pull Request"
3. Select your fork and branch
4. Fill out the PR template
5. Submit the pull request

---

## 🔀 Pull Request Process

### Before Submitting

- ✅ Code compiles/runs without errors
- ✅ All tests pass
- ✅ Linter shows no errors
- ✅ Documentation updated (if needed)
- ✅ Commits follow commit message guidelines
- ✅ Branch is up-to-date with main

### PR Guidelines

1. **Use the PR template** - Fill out all sections
2. **Link related issues** - Use "Fixes #123" or "Closes #123"
3. **Keep PRs focused** - One feature/fix per PR
4. **Keep PRs small** - Easier to review (<400 lines preferred)
5. **Describe your changes** - What, why, and how
6. **Add screenshots** - For UI changes
7. **Be responsive** - Address review feedback promptly

### Review Process

- Maintainers will review your PR (usually within 72 hours)
- You may be asked to make changes
- Once approved, a maintainer will merge your PR
- Your contribution will be recognized! 🎉

### What to Expect

**✅ Good PRs:**
- Clear purpose and description
- Well-tested changes
- Clean, readable code
- Updated documentation
- Addresses feedback constructively

**❌ PRs That May Be Rejected:**
- Spam or trivial changes (typo-only fixes in comments)
- Breaks existing functionality
- No description or context
- Doesn't follow guidelines
- Duplicates existing work
- Out of scope for the project

---

## 🎨 Style Guidelines

### Code Style

<!-- Update based on your project's language/framework -->

**General Principles:**
- Write clean, readable code
- Use meaningful variable/function names
- Add comments for complex logic
- Keep functions small and focused
- Follow DRY (Don't Repeat Yourself)

**[Language]-Specific:**
<!-- Add language-specific guidelines -->
- Follow [PEP 8 for Python / Airbnb for JavaScript / etc.]
- Use [formatter tool] for automatic formatting
- Maximum line length: [X] characters
- Indentation: [spaces/tabs]

### Documentation Style

- Use clear, concise language
- Provide examples where helpful
- Keep line length reasonable for readability
- Use proper markdown formatting
- Check spelling and grammar

---

## 📝 Commit Message Guidelines

We follow [Conventional Commits](https://www.conventionalcommits.org/) specification.

### Format

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types

- **feat:** New feature
- **fix:** Bug fix
- **docs:** Documentation changes
- **style:** Code style changes (formatting, no logic change)
- **refactor:** Code refactoring
- **test:** Adding or updating tests
- **chore:** Maintenance tasks (dependencies, build config)
- **perf:** Performance improvements

### Examples

```bash
# Simple fix
fix: resolve login redirect issue

# Feature with scope
feat(auth): add OAuth2 authentication

# Breaking change
feat!: redesign API endpoints

BREAKING CHANGE: API endpoints now use v2 prefix

# With issue reference
fix: prevent crash on null input (#123)
```

---

## 🏷️ Issue Labels

Understanding our labels helps you find ways to contribute:

### Priority
- `priority: high` - Critical issues
- `priority: medium` - Important but not urgent
- `priority: low` - Nice to have

### Type
- `bug` - Something isn't working
- `feature` - New feature request
- `documentation` - Documentation improvements
- `enhancement` - Improve existing feature

### Status
- `good first issue` - Great for newcomers
- `help wanted` - Extra attention needed
- `in progress` - Someone is working on this
- `blocked` - Cannot proceed (dependencies, decisions needed)

### Difficulty
- `difficulty: easy` - Simple, well-defined tasks
- `difficulty: medium` - Moderate complexity
- `difficulty: hard` - Complex, requires deep knowledge

---

## 🎯 Contribution Drive Events

During fest contribution drives:

### Special Rules
- Focus on issues labeled `fest-drive`
- Points awarded based on contribution quality
- Faster review times (24-48 hours target)
- Special recognition for top contributors

### Point System
<!-- Update based on your contribution drive rules -->
- **Easy issue:** 10 points
- **Medium issue:** 20 points
- **Hard issue:** 30 points
- **Bonus:** Quality documentation, helping others

### Tips for Success
- Start with good first issues to understand the codebase
- Quality over quantity - one good PR beats five trivial ones
- Help other contributors in discussions
- Ask questions early if stuck

---

## 💬 Community

### Where to Get Help

- **GitHub Discussions:** Ask questions, share ideas
- **Discord/Slack:** [Channel link] - Real-time chat
- **Maintainer Office Hours:** [Schedule if applicable]
- **Issues:** Tag maintainers with `@maintainer-name`

### Communication Guidelines

- Be respectful and inclusive
- Ask questions - there are no stupid questions
- Help others when you can
- Share your learning journey
- Give constructive feedback

### Recognition

Contributors are recognized in:
- README contributors section
- Annual contributor highlights
- Contribution drive leaderboards
- Certificates for significant contributions
- Maintainer nominations for consistent contributors

---

## 🎓 Learning Resources

New to open source or [technology]? Check out:

- **Git & GitHub:** [GitHub Guides](https://guides.github.com/)
- **[Language]:** [Link to tutorials]
- **[Framework]:** [Link to documentation]
- **Open Source:** [First Timers Only](https://www.firsttimersonly.com/)

---

## ❓ FAQ

**Q: I'm new to coding. Can I still contribute?**  
A: Absolutely! Look for `good first issue` labels and don't hesitate to ask for help.

**Q: How long does review take?**  
A: Usually 72 hours during regular periods, 24-48 hours during contribution drives.

**Q: Can I work on multiple issues?**  
A: Start with one, then feel free to take more once you're comfortable.

**Q: My PR was rejected. What now?**  
A: Don't worry! Read the feedback, learn from it, and try again. Rejection is part of the learning process.

**Q: Can I contribute if I'm not from NIT Raipur?**  
A: Yes! We welcome external contributors. Priority for events goes to NIT Raipur students.

---

## 🙏 Thank You!

Your contributions, no matter how small, make a big difference. Thank you for being part of our community!

---

<p align="center">
  Questions? Reach out to <a href="MAINTAINERS.md">maintainers</a> or open a <a href="../../discussions">discussion</a>.
</p>
