# Contributing to AI Chatbot Assistant

Thank you for your interest in contributing! This document provides guidelines for contributing to the project.

## Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally
3. Create a new branch for your feature/fix

```bash
git clone https://github.com/YOUR_USERNAME/ai-chatbot.git
cd ai-chatbot
git checkout -b feature/your-feature-name
```

## Development Guidelines

### Code Style

- Use clear, descriptive variable names
- Add JSDoc comments to all functions
- Keep functions focused and single-purpose
- Use ES6+ features (arrow functions, const/let, template literals)

### Testing

1. Test thoroughly in multiple browsers
2. Test on mobile devices
3. Check keyboard navigation (Tab, Enter, Shift+Enter)
4. Verify accessibility with screen readers

### Commit Messages

Write clear commit messages following this format:

```
[Type] Brief description

Detailed explanation if needed.

Examples:
- [Feature] Add localStorage persistence
- [Fix] Correct XSS vulnerability in input handling
- [Docs] Update README with new examples
```

Types: Feature, Fix, Docs, Style, Refactor, Test

## Pull Request Process

1. Update README.md if adding new features
2. Add comments explaining complex logic
3. Test your changes thoroughly
4. Submit pull request with clear description

### PR Description Template

```markdown
## Description
Brief description of changes

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update

## Testing
- [ ] Tested on Chrome
- [ ] Tested on Firefox
- [ ] Tested on Safari
- [ ] Mobile tested

## Related Issues
Fixes #123
```

## Feature Ideas for Contributors

Looking to contribute? Here are some ideas:

1. **localStorage Support** - Save chat history
2. **Dark Mode** - Theme toggling
3. **Export Feature** - Download as JSON/PDF
4. **Sentiment Analysis** - Emotion detection
5. **Multiple Languages** - i18n support
6. **API Integration** - Real AI backends
7. **Voice Input** - Speech recognition
8. **Chat Templates** - Pre-loaded scenarios

## Reporting Issues

Found a bug? Please open an issue with:

1. Clear title describing the problem
2. Steps to reproduce
3. Expected vs actual behavior
4. Browser/OS information
5. Screenshots if applicable

### Issue Template

```markdown
## Bug Description
Clear description of the issue

## To Reproduce
1. Step 1
2. Step 2
3. ...

## Expected Behavior
What should happen

## Actual Behavior
What actually happens

## Environment
- Browser: Chrome 120
- OS: Windows 10
- Device: Desktop
```

## Code Review

All submissions will be reviewed by maintainers. We may request:

- Code changes for clarity/consistency
- Additional documentation
- New tests or verification
- Performance improvements

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

## Questions?

Feel free to ask questions by opening an issue or discussion!

Thank you for contributing! 🎉
