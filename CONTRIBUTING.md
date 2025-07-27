# Contributing to AI Resume Analyzer

Thank you for your interest in contributing to AI Resume Analyzer! This document provides guidelines and information for contributors.

## 🤝 How to Contribute

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When creating a bug report, include:

- **Clear and descriptive title**
- **Steps to reproduce the issue**
- **Expected behavior**
- **Actual behavior**
- **Screenshots (if applicable)**
- **Environment details** (OS, browser, Node.js version)
- **Console errors (if any)**

### Suggesting Enhancements

We welcome feature requests! When suggesting enhancements:

- **Describe the feature clearly**
- **Explain why this feature would be useful**
- **Provide examples of how it would work**
- **Consider implementation complexity**

### Code Contributions

#### Prerequisites

- Node.js 20+
- npm or yarn
- Git
- Basic knowledge of React, TypeScript, and Tailwind CSS

#### Development Setup

1. **Fork the repository**
2. **Clone your fork**
   ```bash
   git clone https://github.com/darvinpatel/resume-analyzer.git
   cd resume-analyzer
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Set up environment variables**
   ```bash
   cp .env.example .env
   # Edit .env with your configuration
   ```

5. **Start development server**
   ```bash
   npm run dev
   ```

#### Making Changes

1. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**
   - Follow the existing code style
   - Write meaningful commit messages
   - Add tests for new features
   - Update documentation as needed

3. **Test your changes**
   ```bash
   npm run typecheck
   npm run build
   ```

4. **Commit your changes**
   ```bash
   git add .
   git commit -m "feat: add new feature description"
   ```

5. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Create a Pull Request**

## 📋 Development Guidelines

### Code Style

- **TypeScript**: Use strict TypeScript with proper typing
- **React**: Follow React best practices and hooks
- **CSS**: Use Tailwind CSS utility classes
- **Naming**: Use descriptive names for variables, functions, and components
- **Comments**: Add comments for complex logic

### Commit Message Format

We follow the [Conventional Commits](https://www.conventionalcommits.org/) specification:

```
type(scope): description

[optional body]

[optional footer]
```

**Types:**
- `feat`: New feature
- `fix`: Bug fix
- `docs`: Documentation changes
- `style`: Code style changes (formatting, etc.)
- `refactor`: Code refactoring
- `test`: Adding or updating tests
- `chore`: Maintenance tasks

**Examples:**
```bash
feat(upload): add drag and drop file upload
fix(auth): resolve authentication token issue
docs(readme): update installation instructions
style(components): improve button styling
```

### File Structure

```
app/
├── components/          # Reusable UI components
│   ├── index.ts        # Component exports
│   └── ComponentName/
│       ├── index.tsx   # Component implementation
│       └── types.ts    # Component types
├── routes/             # Page components
├── lib/                # Utility functions and services
├── constants/          # Application constants
└── types/              # Global type definitions
```

### Testing

- Write unit tests for utility functions
- Test component behavior with user interactions
- Ensure responsive design works on different screen sizes
- Test accessibility features

### Performance

- Optimize bundle size
- Use React.memo for expensive components
- Implement proper loading states
- Optimize images and assets

## 🔍 Review Process

1. **Automated Checks**: All PRs must pass CI/CD checks
2. **Code Review**: At least one maintainer must approve
3. **Testing**: Ensure all tests pass
4. **Documentation**: Update docs if needed

## 🐛 Bug Fixes

When fixing bugs:

1. **Identify the root cause**
2. **Write a test that reproduces the bug**
3. **Fix the issue**
4. **Ensure the test passes**
5. **Update documentation if needed**

## 🚀 Feature Development

When adding new features:

1. **Discuss the feature** in an issue first
2. **Plan the implementation**
3. **Create a prototype** if needed
4. **Implement the feature**
5. **Add comprehensive tests**
6. **Update documentation**

## 📚 Documentation

- Keep README.md up to date
- Add JSDoc comments for functions
- Update API documentation
- Include usage examples

## 🎨 UI/UX Contributions

- Follow the existing design system
- Ensure accessibility compliance
- Test on different devices and browsers
- Consider mobile-first design

## 🔒 Security

- Never commit sensitive information
- Follow security best practices
- Report security vulnerabilities privately
- Validate user inputs

## 📞 Getting Help

- **Issues**: [GitHub Issues](https://github.com/darvinpatel/resume-analyzer/issues)
- **Email**: contact@darvinpatel.com

## 🙏 Recognition

Contributors will be recognized in:
- README.md contributors section
- Release notes
- Project documentation

## 📄 License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.

---

Thank you for contributing to AI Resume Analyzer! 🚀 