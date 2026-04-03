# Contributing to DevCamp

First off, thank you for considering contributing to DevCamp! It's people like you that make DevCamp such a great project.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Enhancements](#suggesting-enhancements)
  - [Your First Code Contribution](#your-first-code-contribution)
  - [Pull Requests](#pull-requests)
- [Style Guides](#style-guides)
  - [Git Commit Messages](#git-commit-messages)
  - [Code Style](#code-style)
  - [Documentation Style](#documentation-style)
- [Development Setup](#development-setup)
- [Testing](#testing)
- [Additional Notes](#additional-notes)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to the project maintainers.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

**Bug Report Template:**

```markdown
**Describe the bug**
A clear and concise description of what the bug is.

**To Reproduce**
Steps to reproduce the behavior:
1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Environment:**
 - OS: [e.g. Ubuntu 20.04]
 - Browser [e.g. chrome, safari] (if applicable)
 - Version [e.g. 22]

**Additional context**
Add any other context about the problem here.
```

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- **Use a clear and descriptive title**
- **Provide a detailed description of the suggested enhancement**
- **Explain why this enhancement would be useful**
- **Include examples** of how the enhancement would be used
- **List any alternative solutions** you've considered

### Your First Code Contribution

Unsure where to begin contributing? You can start by looking through `beginner` and `help-wanted` issues:

- **Beginner issues** - issues that should only require a few lines of code
- **Help wanted issues** - issues that might be more involved

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Make your changes** following our style guides
3. **Add tests** if you've added code that should be tested
4. **Ensure all tests pass** before submitting
5. **Update documentation** as needed
6. **Write a clear commit message** following our conventions
7. **Submit a pull request** with a comprehensive description

**Pull Request Template:**

```markdown
## Description
Brief description of what this PR does.

## Related Issue
Fixes #(issue number)

## Type of Change
- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update
- [ ] Refactoring (no functional changes)
- [ ] Performance improvement
- [ ] Test updates

## How Has This Been Tested?
Describe the tests you ran and how to reproduce them.

## Checklist
- [ ] My code follows the style guidelines of this project
- [ ] I have performed a self-review of my own code
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] I have made corresponding changes to the documentation
- [ ] My changes generate no new warnings
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes
- [ ] Any dependent changes have been merged and published

## Screenshots (if applicable)
Add screenshots to demonstrate visual changes.

## Additional Notes
Any additional information that would be helpful for reviewers.
```

## Style Guides

### Git Commit Messages

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

**Format:**
```
<type>(<scope>): <subject>

<body>

<footer>
```

**Types:**
- `feat:` - A new feature
- `fix:` - A bug fix
- `docs:` - Documentation only changes
- `style:` - Changes that do not affect the meaning of the code (white-space, formatting, etc)
- `refactor:` - A code change that neither fixes a bug nor adds a feature
- `perf:` - A code change that improves performance
- `test:` - Adding missing tests or correcting existing tests
- `chore:` - Changes to the build process or auxiliary tools

**Examples:**
```
feat(auth): add user login functionality

Implement JWT-based authentication system with login endpoint.
Includes password hashing and token generation.

Closes #123
```

```
fix(api): correct endpoint response format

The API was returning inconsistent data formats. This fix
standardizes all responses to follow the API specification.

Fixes #456
```

### Code Style

- **Consistency**: Follow the existing code style in the file you're editing
- **Formatting**: Use the project's configured formatter (e.g., Prettier, Black)
- **Naming**: Use descriptive and meaningful names for variables, functions, and classes
- **Comments**: Write clear comments for complex logic, but prefer self-documenting code
- **DRY Principle**: Don't Repeat Yourself - extract reusable code into functions/modules
- **SOLID Principles**: Follow object-oriented design principles where applicable

### Documentation Style

- Use **Markdown** for all documentation
- Keep line length to **80-100 characters** for readability
- Use **clear and concise language**
- Include **code examples** where appropriate
- Use **headings** to organize content hierarchically
- Add **links** to related documentation

## Development Setup

### Prerequisites

*To be defined based on project technology stack*

### Setup Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/displacedalarm9/DevCamp.git
   cd DevCamp
   ```

2. **Install dependencies:**
   ```bash
   # Commands to be added based on project setup
   ```

3. **Configure environment:**
   ```bash
   # Copy example environment file
   # cp .env.example .env
   # Edit .env with your local configuration
   ```

4. **Run the application:**
   ```bash
   # Commands to be added
   ```

## Testing

### Running Tests

```bash
# Run all tests
# Command to be added

# Run specific test file
# Command to be added

# Run with coverage
# Command to be added
```

### Writing Tests

- Write tests for all new features
- Maintain test coverage above 80%
- Use descriptive test names
- Follow the Arrange-Act-Assert pattern
- Mock external dependencies

**Example Test Structure:**
```javascript
// Example - actual syntax will depend on testing framework
describe('Feature Name', () => {
  it('should do something specific', () => {
    // Arrange: Set up test data and conditions
    
    // Act: Execute the code being tested
    
    // Assert: Verify the results
  });
});
```

## Additional Notes

### Branch Naming Conventions

- `feature/description` - New features
- `bugfix/description` - Bug fixes
- `hotfix/description` - Urgent fixes
- `docs/description` - Documentation changes
- `refactor/description` - Code refactoring

### Code Review Process

1. All code changes require review before merging
2. Address all review comments or explain why changes aren't needed
3. Ensure CI checks pass before requesting review
4. Keep PRs focused and reasonably sized
5. Be respectful and constructive in reviews

### Getting Help

- Check the [documentation](docs/)
- Search existing [issues](https://github.com/displacedalarm9/DevCamp/issues)
- Ask questions by opening a new issue with the "question" label
- Join community discussions

### Recognition

Contributors will be recognized in:
- The project README
- Release notes
- GitHub contributors page

Thank you for contributing to DevCamp! 🎉
