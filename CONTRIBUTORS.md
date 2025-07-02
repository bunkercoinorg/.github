# Contributing to BunkerCoin

## Commit Convention

All commits must follow [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
<type>(<scope>): <subject>

<body>

<footer>
```

### Types
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, semicolons, etc)
- `refactor`: Code refactoring
- `perf`: Performance improvements
- `test`: Adding or updating tests
- `build`: Build system or dependencies
- `ci`: CI configuration
- `chore`: Other changes that don't modify src or test files

### Examples
```
feat(radio): implement shortwave packet compression
fix(consensus): resolve node synchronization issue
docs(api): update radio protocol documentation
```

## Pull Request Process

1. Fork the repository
2. Create a feature branch from `main`
3. Write clean, documented code
4. Add tests for new functionality
5. Ensure all tests pass
6. Submit PR with clear description

## Development Standards

- Follow existing code style
- Add unit tests for new features
- Update documentation as needed
- Keep PRs focused and atomic
- Radio-specific code must include bandwidth considerations

## Testing

- Run full test suite before submitting PR
- Test radio simulation when modifying consensus
- Verify changes work in bandwidth-constrained environments

## Questions

Open an issue for questions or discussions about contributions. 