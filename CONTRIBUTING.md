# Contributing to project-memory

Thank you for your interest in contributing to project-memory! We welcome contributions from everyone who shares our goal of revolutionizing knowledge management in software development.

## Code of Conduct

By participating in this project, you agree to abide by our [Code of Conduct](CODE_OF_CONDUCT.md). Please read it before contributing.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When creating a bug report, please include:

- A clear and descriptive title
- Steps to reproduce the issue
- Expected behavior vs actual behavior
- Your environment (OS, version, etc.)
- Any relevant logs or error messages

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, please include:

- A clear and descriptive title
- A detailed description of the proposed enhancement
- Why this enhancement would be useful
- Possible implementation approaches

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Follow the coding style** of the project
3. **Write clear commit messages** following conventional commits:
   - `feat:` for new features
   - `fix:` for bug fixes
   - `docs:` for documentation changes
   - `test:` for test additions/changes
   - `refactor:` for code refactoring
   - `chore:` for maintenance tasks

4. **Ensure tests pass** (when we have them)
5. **Update documentation** if needed
6. **Submit a pull request** with:
   - Clear description of changes
   - Link to related issue(s)
   - Screenshots/demos if applicable

### Development Setup

```bash
# Clone your fork
git clone https://github.com/YOUR_USERNAME/project-memory.git
cd project-memory

# Add upstream remote
git remote add upstream https://github.com/ryo-morimoto/project-memory.git

# Create a feature branch
git checkout -b feature/your-feature-name
```

### Protocol Contributions

Since project-memory is a protocol specification, we especially welcome:

- Protocol design improvements
- Performance optimization ideas
- Security enhancement proposals
- Integration examples with different languages/frameworks
- Documentation improvements

### First-Time Contributors

Look for issues labeled `good first issue` or `help wanted`. These are great starting points for new contributors.

## Development Process

1. **Discussion First**: For major changes, open an issue first to discuss what you would like to change
2. **Small PRs**: Keep pull requests focused and small
3. **Test Coverage**: Add tests for new functionality
4. **Documentation**: Update relevant documentation
5. **Code Review**: All PRs require review before merging

## Performance Considerations

Given our strict performance requirements (<5ms response time), please:

- Benchmark any changes that might affect performance
- Include performance metrics in your PR
- Consider memory usage and optimization

## Questions?

Feel free to:
- Open an issue for questions
- Start a discussion in GitHub Discussions
- Reach out to maintainers

## Recognition

Contributors will be recognized in our README. We value every contribution, no matter how small!

---

Thank you for contributing to project-memory! Together, we're building the future of knowledge management in software development.