# CLAUDE.md - AI Assistant Guide

## Repository Overview

This is a simple static website project containing a "Hello World" page with Korean language support. The repository demonstrates basic HTML/CSS development with custom typography using the D2Coding font.

**Repository Name**: 202511
**Primary Language**: Korean (ko)
**Project Type**: Static HTML Website
**Last Updated**: 2025-11-20

## Project Structure

```
202511/
├── .git/              # Git version control
├── index.html         # Main HTML page (single entry point)
└── CLAUDE.md          # This file - AI assistant guide
```

### Key Files

- **index.html**: The main and only HTML page displaying a two-line greeting message

## Technology Stack

- **HTML5**: Semantic markup with Korean language support
- **CSS3**: Inline styles with flexbox layout
- **Typography**: D2Coding font from CDN (https://cdn.jsdelivr.net/gh/wan2land/d2coding/d2coding-full.css)
- **No JavaScript**: Pure HTML/CSS implementation
- **No Build Process**: Direct static file serving

## Development History

Based on git history, the project evolved through these phases:

1. **Initial Creation** (e941528): Basic "Hello World" HTML page
2. **Styling Phase** (7bf1727): Added white background, black text, D2Coding font
3. **Content Update** (b896faa): Extended text content to multiple lines
4. **Layout Fix** (78f3db7): Fixed layout to properly display text in two lines

## Design Conventions

### Visual Design
- **Background**: White (`white`)
- **Text Color**: Black (`black`)
- **Font Family**: D2Coding (monospace) - a popular Korean coding font
- **Font Size**: 4rem for headings
- **Layout**: Centered flexbox container with vertical stacking
- **Viewport**: Full viewport height (100vh)

### Code Style
- **HTML Indentation**: 4 spaces
- **Language**: Korean (lang="ko")
- **CSS Approach**: Inline `<style>` tags (no external CSS files)
- **Font Loading**: CDN-based font delivery

## Git Workflow

### Branch Structure
- **Main Branch**: Standard main branch for production-ready code
- **Feature Branches**: Use `claude/claude-md-*` pattern for AI-assisted development

### Current Development Branch
```bash
claude/claude-md-mi7955cweh7vk883-0123G8iYjXSKxdw9dfcrkKZY
```

### Git Commands Reference
```bash
# Check current branch and status
git status

# Create and switch to feature branch
git checkout -b <branch-name>

# Stage changes
git add <file>

# Commit with descriptive message
git commit -m "Description of changes"

# Push to remote (with upstream tracking)
git push -u origin <branch-name>

# View commit history
git log --oneline
```

## Making Changes

### When Modifying Content

1. **Text Changes**: Update the `<h1>` elements in index.html:27-28
2. **Styling Changes**: Modify the `<style>` block in index.html:8-23
3. **Structure Changes**: Update the HTML structure while maintaining Korean language support

### Commit Message Conventions

Based on the repository's commit history, use clear, imperative mood messages:
- ✅ "Add Hello World HTML page"
- ✅ "Update styling: white background, black text, D2Coding font"
- ✅ "Fix layout to display text in two lines"
- ❌ "Added some changes"
- ❌ "Update"

### Testing Locally

To test the page locally:

```bash
# Option 1: Python HTTP server
python3 -m http.server 8000

# Option 2: PHP built-in server
php -S localhost:8000

# Then open: http://localhost:8000
```

## AI Assistant Guidelines

### When Asked to Make Changes

1. **Always Read First**: Use the Read tool to view index.html before making changes
2. **Use Edit Tool**: Prefer Edit over Write for existing files to maintain history
3. **Commit with Context**: Include what changed and why in commit messages
4. **Push to Feature Branch**: Always push to the designated `claude/` branch
5. **Test Assumptions**: Verify the current state before assuming structure

### Common Tasks

#### Updating Text Content
```html
<!-- Current location: index.html:26-27 -->
<h1>Hello World!!!</h1>
<h1>Claude Code & Github & BulleEopseum</h1>
```

#### Changing Colors
```css
/* Current location: index.html:9-23 */
body {
    background: white;  /* Update here for background */
}
h1 {
    color: black;       /* Update here for text color */
}
```

#### Changing Font Size
```css
/* Current location: index.html:21 */
h1 {
    font-size: 4rem;    /* Update here for size */
}
```

### What to Avoid

- ❌ Don't create additional files unless explicitly requested
- ❌ Don't remove the D2Coding font (it's important for Korean text display)
- ❌ Don't change the language attribute without confirmation
- ❌ Don't add JavaScript unless specifically asked
- ❌ Don't push to main/master branches without permission
- ❌ Don't use `git commit --amend` unless explicitly requested

## Deployment Considerations

### Static Hosting Options

This site can be deployed to:
- **GitHub Pages**: Enable in repository settings
- **Netlify**: Drag-and-drop deployment
- **Vercel**: Connect repository for auto-deployment
- **Any static hosting**: No build process required

### No Build Required

- No compilation or transpilation needed
- No dependencies to install
- No package.json or build tools
- Direct deployment of index.html

## Character Encoding

The page uses UTF-8 encoding (`<meta charset="UTF-8">`) which properly supports:
- Korean characters (한글)
- English text
- Special characters and symbols

## Accessibility Notes

Current accessibility considerations:
- ✅ Semantic HTML (`<h1>` tags)
- ✅ Proper language declaration (`lang="ko"`)
- ✅ Viewport meta tag for responsive design
- ⚠️ Consider adding more semantic structure for screen readers
- ⚠️ Consider adding ARIA labels if interactive elements are added

## Future Enhancement Suggestions

Potential improvements to consider:
1. Add README.md for human developers
2. Extract CSS to external stylesheet
3. Add favicon
4. Include Open Graph meta tags for social sharing
5. Add more semantic HTML5 elements
6. Consider responsive font sizes (clamp, vw units)
7. Add basic SEO meta tags

## Questions to Ask Before Major Changes

1. **Language**: Should Korean language support be maintained?
2. **Font**: Is D2Coding font required, or can it be changed?
3. **Simplicity**: Should the single-file approach be maintained?
4. **Styling**: Should styles remain inline or move to external CSS?
5. **Content**: What is the purpose of content changes (demo, portfolio, educational)?

## Contact and Context

This appears to be a demonstration or educational project showcasing:
- Basic web development
- Git version control workflow
- Integration with Claude Code
- GitHub collaboration
- Korean language web development

## Version History

- **2025-11-20**: CLAUDE.md created
- **Previous**: Four commits establishing the base HTML page

---

**Note to AI Assistants**: Always verify the current state of the repository before making assumptions. This file represents a snapshot in time and should be updated when significant changes occur to the project structure or conventions.
