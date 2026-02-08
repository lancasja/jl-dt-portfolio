# Contributing Guide

Thank you for your interest in this project! We welcome all forms of contribution.

## How to Contribute

### Reporting Bugs

If you find a bug, please:

1. Check [Issues](https://github.com/ricocc/ricoui-portfolio/issues) to make sure it hasn’t already been reported
2. If it’s a new bug, open a new Issue with:
   - A clear description of the problem
   - Steps to reproduce
   - Expected behavior
   - Actual behavior
   - Screenshots (if applicable)
   - Environment details (browser, OS, etc.)

### Suggesting New Features

If you have ideas for improvements or new features:

1. Check existing Issues to ensure there isn’t a similar proposal
2. Open a new Feature Request Issue describing:
   - The feature
   - Use cases
   - Possible implementation (optional)

### Submitting Code

1. **Fork the project**
   ```bash
   git clone https://github.com/your-username/ricoui-portfolio.git
   cd ricoui-portfolio
   ```

2. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

3. **Install dependencies**
   ```bash
   pnpm install
   ```

4. **Make your changes**
   - Write your code
   - Ensure it passes checks: `pnpm check`
   - Test your changes

5. **Commit your changes**
   ```bash
   git add .
   git commit -m "feat: add new feature description"
   # or
   git commit -m "fix: fix bug description"
   ```

   Follow [Conventional Commits](https://www.conventionalcommits.org/) for commit messages:
   - `feat:` New feature
   - `fix:` Bug fix
   - `docs:` Documentation update
   - `style:` Code style (no functional change)
   - `refactor:` Code refactor
   - `perf:` Performance improvement
   - `test:` Tests
   - `chore:` Build/tooling

6. **Push and open a Pull Request**
   ```bash
   git push origin feature/your-feature-name
   ```

   Then open a Pull Request on GitHub.

## Code Standards

- Use Biome for linting and formatting
- Run `pnpm check` to ensure code meets the standards
- Keep code clear and readable
- Add comments where helpful

## Development Environment

- Node.js >= 18
- pnpm (recommended) or npm/yarn
- A modern browser (Chrome, Firefox, Safari, Edge)

## Testing

Before submitting a PR, please ensure:

- [ ] Code passes `pnpm check`
- [ ] Local run with `pnpm dev` works as expected
- [ ] Build succeeds with `pnpm build`
- [ ] You’ve tested on different browsers and devices

## Questions?

If you run into issues, you can:

- Browse [Issues](https://github.com/ricocc/ricoui-portfolio/issues)
- Open a new Issue with your question
- Contact the maintainers: hello@ricoui.com

Thanks again for contributing! 🎉
