# Contributing to Mindful Journal

Thank you for your interest in contributing to Mindful Journal! We welcome contributions from everyone.

## 🚀 Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/yourusername/mindful-journal.git
   cd mindful-journal
   ```
3. **Install dependencies**:
   ```bash
   npm install
   ```
4. **Start the development server**:
   ```bash
   npm run dev
   ```

## 🛠️ Development Workflow

### Creating a Feature Branch

```bash
git checkout -b feature/your-feature-name
```

### Making Changes

1. Make your changes in the appropriate files
2. Test your changes thoroughly
3. Ensure your code follows our style guidelines
4. Add or update tests if necessary

### Committing Changes

We follow conventional commit messages:

```bash
git commit -m "feat: add new mood tracking feature"
git commit -m "fix: resolve date formatting issue"
git commit -m "docs: update README with new features"
```

### Submitting a Pull Request

1. Push your changes to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```
2. Create a Pull Request on GitHub
3. Fill out the PR template with details about your changes
4. Wait for review and address any feedback

## 📋 Code Style Guidelines

### TypeScript
- Use TypeScript for all new code
- Define proper interfaces and types
- Avoid `any` types when possible

### React Components
- Use functional components with hooks
- Follow the existing component structure
- Use descriptive prop names and types

### CSS/Tailwind
- Use Tailwind CSS classes consistently
- Follow the existing color palette (sage theme)
- Ensure responsive design principles

### File Organization
- Keep components in the `src/components/` directory
- Place utility functions in `src/utils/`
- Define types in `src/types/`

## 🧪 Testing

Before submitting a PR:

1. **Test your changes** manually in the browser
2. **Check for TypeScript errors**:
   ```bash
   npm run build
   ```
3. **Run the linter**:
   ```bash
   npm run lint
   ```

## 🐛 Bug Reports

When reporting bugs, please include:

1. **Clear description** of the issue
2. **Steps to reproduce** the problem
3. **Expected behavior** vs actual behavior
4. **Browser and OS** information
5. **Screenshots** if applicable

Use this template:

```markdown
**Bug Description**
A clear description of what the bug is.

**To Reproduce**
1. Go to '...'
2. Click on '...'
3. See error

**Expected Behavior**
What you expected to happen.

**Screenshots**
If applicable, add screenshots.

**Environment**
- Browser: [e.g. Chrome 91]
- OS: [e.g. macOS 11.4]
```

## 💡 Feature Requests

We welcome feature suggestions! Please:

1. **Check existing issues** to avoid duplicates
2. **Describe the feature** clearly
3. **Explain the use case** and benefits
4. **Consider the scope** - keep it focused

## 🎯 Areas for Contribution

We especially welcome contributions in these areas:

### 🌟 High Priority
- Accessibility improvements
- Performance optimizations
- Mobile responsiveness enhancements
- Data export/import features

### 🔧 Medium Priority
- Dark mode implementation
- Advanced mood analytics
- Notification system
- Keyboard shortcuts

### 🎨 Design & UX
- Animation improvements
- Icon enhancements
- Color scheme variations
- User experience optimizations

## 📚 Resources

- [React Documentation](https://reactjs.org/docs)
- [TypeScript Handbook](https://www.typescriptlang.org/docs)
- [Tailwind CSS Documentation](https://tailwindcss.com/docs)
- [Lucide React Icons](https://lucide.dev)

## 🤝 Code of Conduct

### Our Pledge

We are committed to making participation in this project a harassment-free experience for everyone, regardless of age, body size, disability, ethnicity, gender identity and expression, level of experience, nationality, personal appearance, race, religion, or sexual identity and orientation.

### Our Standards

Examples of behavior that contributes to creating a positive environment include:

- Using welcoming and inclusive language
- Being respectful of differing viewpoints and experiences
- Gracefully accepting constructive criticism
- Focusing on what is best for the community
- Showing empathy towards other community members

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported by contacting the project team. All complaints will be reviewed and investigated promptly and fairly.

## 📞 Getting Help

If you need help with contributing:

1. Check the [README](README.md) for basic setup
2. Look through existing [Issues](https://github.com/yourusername/mindful-journal/issues)
3. Create a new issue with the "question" label
4. Join our community discussions

## 🙏 Recognition

Contributors will be recognized in:
- The project README
- Release notes for significant contributions
- Special thanks in documentation

Thank you for helping make Mindful Journal better for everyone! 🌿