# Contributing to QA Skills Marketplace

Thank you for considering contributing to QA Skills Marketplace! This document provides guidelines and instructions for contributing.

## How to Contribute

### Reporting Bugs

1. Check if the issue already exists
2. Provide:
   - Clear description of the bug
   - Steps to reproduce
   - Expected behavior
   - Actual behavior
   - Screenshots or examples if applicable

### Suggesting Enhancements

1. Use the issue tracker to propose new skills or commands
2. Describe the use case and why it would benefit QA professionals
3. Provide examples or reference materials if possible

### Submitting Pull Requests

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/your-feature-name`
3. Make your changes
4. Test your changes with Claude Code or Cowork
5. Commit with clear messages: `git commit -m "Add new XYZ skill"`
6. Push to your fork: `git push origin feature/your-feature-name`
7. Submit a pull request with:
   - Clear title and description
   - Reference to related issues
   - Test results

### Adding New Skills

1. Create a new file: `plugin-name/skills/skill-name.md`
2. Follow the skill template structure
3. Include:
   - Clear description
   - Use cases and examples
   - Step-by-step guidance
   - Related frameworks or methodologies
4. Update the plugin's README.md
5. Test with Claude Code/Cowork

### Adding New Commands

1. Commands should chain multiple skills
2. Define in the plugin's manifest
3. Document in the plugin's README.md
4. Test the workflow end-to-end

## Code of Conduct

Be respectful and constructive. This is a community project.

## Questions?

Open an issue with the `question` label.

## License

By contributing, you agree that your contributions will be licensed under its MIT License.
