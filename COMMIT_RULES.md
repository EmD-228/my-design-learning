# Git Commit Rules for my-design-learning

## Basic Principles

### Commit Related Changes
A commit should be a wrapper for **related changes only**. For example:
- ✅ **Good**: One commit for adding a new component, another for fixing a bug
- ❌ **Bad**: One commit that adds a component AND fixes a bug AND updates styles

### Commit Often
- Keep commits small and focused
- Commit when a logical component is completed
- Use `git stash` if you need a clean working copy temporarily

### Don't Commit Half-Done Work
- Only commit code when a logical component is completed
- Split features into logical chunks that can be completed quickly
- Test your code before committing

### Test Before Committing
- Test thoroughly to ensure code works and has no side effects
- Run `npm run build` to check for TypeScript errors
- Verify the component renders correctly in the browser

## Commit Message Format

### Structure
```
<type>: <subject>

<body>

<footer>
```

### Formatting Rules

1. **Subject Line** (First line)
   - **Capitalized**, short summary (50 characters or less)
   - Use imperative mood: "Add component" not "Added component" or "Adds component"
   - No period at the end
   - Start with a type prefix (see Types below)

2. **Blank Line**
   - **Always leave the second line blank**

3. **Body** (Optional but recommended)
   - Wrap text to about 72 characters
   - Explain **what** and **why**, not **how**
   - Use imperative mood
   - Can use bullet points (hyphen or asterisk)

4. **Footer** (Optional)
   - Reference issues: `Closes #123` or `Fixes #456`

### Commit Types

Use one of the following prefixes:

- **feat**: A new feature (component, section, functionality)
- **fix**: A bug fix
- **style**: Changes that don't affect code meaning (formatting, CSS, whitespace)
- **refactor**: Code change that neither fixes a bug nor adds a feature
- **perf**: Performance improvement
- **test**: Adding or updating tests
- **docs**: Documentation only changes
- **chore**: Changes to build process, dependencies, or tooling
- **ui**: UI/UX improvements (styling, layout, visual changes)

### Examples

#### Example 1: Simple feature (no body)
```
feat: add Testimonials component with horizontal scroll
```

#### Example 2: Feature with description
```
feat: enhance ImpressionItem with badges and icons overlay

- Add sale badge overlay on product image
- Add interactive icons (heart, cart, eye) at bottom of image
- Improve layout with better spacing and typography
- Add rating display with star icons
- Add price display with discount styling
```

#### Example 3: Bug fix
```
fix: center icon container in ImpressionItem

The icon container was not properly centered horizontally.
Added -translate-x-1/2 to center the flex container relative
to its left-1/2 position.
```

#### Example 4: UI improvement
```
ui: improve Testimonials scroll behavior

- Add overflow-x-scroll for horizontal scrolling
- Add flex-shrink-0 to prevent items from shrinking
- Set proper width constraints on container
```

#### Example 5: Style changes
```
style: fix typo in ImpressionItem component

Changed "Departement" to "Department" in the component title.
```

#### Example 6: Refactoring
```
refactor: extract TestimonialItem into separate component

Extract testimonial card into reusable TestimonialItem component
to improve code organization and reusability.
```

## Project-Specific Guidelines

### Component Development
- One commit per component creation
- Separate commits for styling improvements
- Separate commits for functionality additions

### File Organization
- Commit each modified file separately when possible
- Group related file changes in one commit (e.g., component + its styles)

### Vue Component Commits
- **New component**: `feat: add ComponentName component`
- **Component update**: `feat: enhance ComponentName with [feature]`
- **Component fix**: `fix: [issue] in ComponentName`
- **Component styling**: `ui: improve ComponentName styling`

### Examples for This Project

```
feat: add HeaderSection component with navigation
feat: add HeroSection with call-to-action buttons
feat: add FeaturesSection displaying key features
ui: improve ImpressionItem card layout and spacing
fix: center icons in ImpressionItem overlay
feat: add Testimonials section with scrollable items
style: update color variables in style.css
refactor: extract common button styles to CSS variables
```

## Workflow

1. **Before committing:**
   - Review your changes with `git status` and `git diff`
   - Test your code
   - Ensure TypeScript compiles: `npm run build`

2. **Staging:**
   - Stage related changes together: `git add <file>`
   - Use `git add -p` for partial staging if needed

3. **Committing:**
   - Write a clear, descriptive commit message following the format above
   - One logical change per commit

4. **After committing:**
   - Review with `git log -1` to verify your message
   - Continue working or push when ready

## Branch Strategy

- Use feature branches for new features: `feature/add-testimonials`
- Use fix branches for bug fixes: `fix/center-icons`
- Keep `main` branch stable and tested
- Merge with meaningful commit messages

## Common Mistakes to Avoid

❌ **Too vague:**
```
fix: stuff
update: things
```

✅ **Better:**
```
fix: center icon container in ImpressionItem
feat: add Testimonials component with horizontal scroll
```

❌ **Multiple unrelated changes:**
```
feat: add component and fix bug and update styles
```

✅ **Better:**
```
feat: add Testimonials component
fix: center icons in ImpressionItem
ui: improve card spacing in ImpressionSection
```

❌ **Past tense:**
```
feat: Added new component
fix: Fixed the bug
```

✅ **Better:**
```
feat: add new component
fix: center icon container
```

## References

This document is based on:
- Git best practices from the Git community
- Conventional Commits specification
- OpenStack commit message guidelines
- Vue.js project conventions

