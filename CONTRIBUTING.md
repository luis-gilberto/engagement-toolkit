# Contributing Guidelines

This is a private, proprietary project. Contributions are limited to authorized collaborators only.

## For Authorized Contributors

### Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/partnership-toolkit.git
   cd partnership-toolkit
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run dev
   ```

### Code Standards

#### HTML
- Use semantic HTML5 elements
- Include proper ARIA labels
- Maintain accessibility standards

#### CSS
- Follow BEM naming convention where applicable
- Use CSS custom properties for theming
- Maintain mobile-first responsive design
- Keep animations performant (use transforms)

#### JavaScript
- Use vanilla JavaScript (no frameworks)
- Follow ES6+ standards
- Include error handling
- Comment complex logic
- Use meaningful variable names

### File Organization

```
partnership-toolkit/
├── index.html          # Main HTML
├── styles.css          # All styles
├── script.js           # All JavaScript
├── data.json          # Content data
├── assets/            # Static assets
└── docs/              # Documentation
```

### Content Updates

All content should be managed through `data.json`:
- Services information
- Investment packages
- Pricing details

### Asset Management

- Optimize all images before committing
- Use WebP format when possible
- Include alt text for all images
- Maintain consistent naming conventions

### Testing Checklist

Before submitting changes:
- [ ] Test in Chrome, Firefox, Safari, Edge
- [ ] Verify mobile responsiveness
- [ ] Check accessibility with screen reader
- [ ] Validate HTML and CSS
- [ ] Test JavaScript functionality
- [ ] Verify print styles work correctly

### Commit Guidelines

Use conventional commit format:
```
type(scope): description

feat(cards): add flip animation to service cards
fix(mobile): resolve touch interaction issues
docs(readme): update installation instructions
style(css): improve button hover effects
```

### Pull Request Process

1. Create feature branch from `main`
2. Make changes following code standards
3. Test thoroughly across browsers
4. Update documentation if needed
5. Submit pull request with clear description

### Asset Requirements

When adding new assets:
- Provide multiple formats (SVG, PNG, WebP)
- Include proper attribution
- Optimize file sizes
- Update asset documentation

### Performance Guidelines

- Maintain Lighthouse score 90+
- Keep bundle size minimal
- Use efficient animations
- Optimize images and fonts
- Test on slower devices

### Security Considerations

- Validate all user inputs
- Use HTTPS for all external resources
- Keep dependencies updated
- Follow content security policy

### Documentation

Update relevant documentation when making changes:
- README.md for setup changes
- IMPLEMENTATION.md for technical changes
- ASSET_REQUIREMENTS.md for asset changes

## Questions?

For questions about contributing, contact the project maintainer.

---

**Note**: This project is under active development. Guidelines may be updated as the project evolves.
