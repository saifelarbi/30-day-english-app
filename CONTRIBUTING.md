# Contributing to 30-Day English Learning App

First off, thank you for considering contributing to the 30-Day English Learning App! It's people like you that make this app such a great tool.

## Code of Conduct

This project and everyone participating in it is governed by our Code of Conduct. By participating, you are expected to uphold this code.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the issue list as you might find out that you don't need to create one. When you are creating a bug report, please include as many details as possible:

* **Use a clear and descriptive title**
* **Describe the exact steps which reproduce the problem**
* **Provide specific examples to demonstrate the steps**
* **Describe the behavior you observed after following the steps**
* **Explain which behavior you expected to see instead and why**
* **Include screenshots and animated GIFs if possible**
* **Include your environment details** (OS, app version, device model)

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

* **Use a clear and descriptive title**
* **Provide a step-by-step description of the suggested enhancement**
* **Provide specific examples to demonstrate the steps**
* **Describe the current behavior and expected behavior**
* **Explain why this enhancement would be useful**

### Pull Requests

* Fill in the required template
* Follow the Dart/TypeScript/JavaScript styleguide
* Include appropriate test cases
* End all files with a newline
* Avoid platform-dependent code
* Document new code based on our style guide

## Styleguides

### Git Commit Messages

* Use the present tense ("Add feature" not "Added feature")
* Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
* Limit the first line to 72 characters or less
* Reference issues and pull requests liberally after the first line
* Consider starting the commit message with an applicable emoji:
  * 🎨 when improving the format/structure of the code
  * 🐎 when improving performance
  * 📝 when writing docs
  * 🐛 when fixing a bug
  * ✨ when adding a new feature
  * 🔒 when dealing with security
  * ⬆️ when upgrading dependencies
  * ⬇️ when downgrading dependencies

### Dart/Flutter Code Styleguide

* Follow [Dart Style Guide](https://dart.dev/guides/language/effective-dart/style)
* Use meaningful variable and function names
* Write comments for complex logic
* Keep functions small and focused
* Use type annotations consistently

### TypeScript Code Styleguide

* Follow [TypeScript Best Practices](https://www.typescriptlang.org/docs/handbook/declaration-files/do-s-and-don-ts.html)
* Use `const` instead of `let` or `var`
* Use meaningful variable names
* Keep functions small and focused
* Always include proper type annotations

### Documentation Styleguide

* Use [Markdown](https://daringfireball.net/projects/markdown) for all documentation
* Reference other documentation with relative links
* Reference code with inline code comments
* Use clear and concise language
* Keep sentences short and simple

## Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/saifelarbi/30-day-english-app.git
   cd 30-day-english-app
   ```

2. **Install dependencies**
   ```bash
   # For mobile
   cd mobile
   flutter pub get
   
   # For backend
   cd backend
   npm install
   ```

3. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

4. **Run the app**
   ```bash
   # Mobile
   flutter run
   
   # Backend
   npm run dev
   ```

5. **Run tests**
   ```bash
   # Mobile
   flutter test
   
   # Backend
   npm test
   ```

## Testing

* Write tests for new features
* Ensure all tests pass before submitting a PR
* Maintain or improve code coverage
* Test on both Android and iOS (if mobile changes)

## Documentation

* Update README.md if needed
* Update API documentation if adding endpoints
* Add comments for complex logic
* Document new features in the changelog

## Review Process

1. At least one code review from maintainers
2. All CI/CD checks must pass
3. No merge conflicts
4. Approval from project lead for major changes

## Community

* Use the discussions page for questions and ideas
* Be respectful and constructive in feedback
* Help other contributors with their PRs
* Share knowledge and best practices

## Recognition

We recognize and appreciate all contributors! Your name will be added to:
* The contributors list in README.md
* The CONTRIBUTORS.md file
* Monthly contributor shoutout in our newsletter

## Questions?

Feel free to:
* Create a discussion on GitHub
* Open an issue with the question tag
* Email: support@30dayenglish.app
* Contact the maintainer directly

---

Thank you for making 30-Day English Learning App better! 🎉
