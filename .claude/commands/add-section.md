# Add New Section to Sovera AI Website

Add a new section to the website following the existing design system and patterns.

## Instructions

When adding a new section, I need to know:
1. **Section name** - What should this section be called?
2. **Section purpose** - What content/functionality should it have?
3. **Position** - Where should it appear in the page flow?

## Design System Reference

Follow these existing patterns:

### HTML Structure
```html
<section class="[section-name]" id="[section-name]">
    <div class="container">
        <div class="section-header">
            <span class="section-label">Label Text</span>
            <h2 class="section-title">Main Title</h2>
            <p class="section-subtitle">Optional subtitle text</p>
        </div>
        <!-- Section content here -->
    </div>
</section>
```

### CSS Variables Available
- Colors: `--color-primary`, `--color-accent`, `--color-text`, `--color-text-secondary`
- Gradients: `--gradient-primary`
- Spacing: Use existing patterns (padding, margins)
- Glass card effect: `.glass-card` class

### Animation Classes Available
- `.reveal` - Fade in on scroll
- `.stagger-children` - Stagger child animations
- `.glow-text` - Text glow effect

## Output

Provide:
1. HTML code for the new section
2. CSS styles following existing patterns
3. Any JavaScript needed for interactivity
4. Instructions for where to place the code

What section would you like to add?
