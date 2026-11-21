# Contributing Guidelines

Thank you for helping improve this educational agentic design patterns repository.

## Ways to Contribute

- Report bugs or broken notebook cells.
- Improve explanations and documentation.
- Add or improve architecture diagrams.
- Add practical examples or framework implementations.
- Fix dependencies or environment setup instructions.
- Suggest experiments and additional test cases.

## Before Submitting

1. Keep changes focused on one chapter or feature.
2. Do not commit API keys, credentials, private data, or generated secrets.
3. Preserve attribution to Antonio Gulli and Save the Children.
4. Use relative paths and keep notebook filenames consistent.
5. Clear sensitive or environment-specific notebook outputs when appropriate.
6. Run or validate the affected notebooks before submitting a pull request.

## Pull Request Process

1. Fork the repository.
2. Create a focused feature branch:

   ```bash
   git checkout -b docs/improve-chapter-one
   ```

3. Make the smallest useful change.
4. Commit it with a clear Conventional Commit message:

   ```bash
   git commit -m "docs: clarify prompt chaining examples"
   ```

5. Push the branch and open a pull request.

## Commit Message Format

Use a short Conventional Commit prefix:

- `docs:` for documentation changes
- `feat:` for new features
- `fix:` for bug fixes
- `test:` for tests
- `refactor:` for code restructuring
- `chore:` for maintenance

Example:

```text
fix: correct MCP server notebook setup
```
