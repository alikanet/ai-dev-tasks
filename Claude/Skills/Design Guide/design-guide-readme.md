# Design Guide Skill

A comprehensive design system skill that ensures every UI you build looks modern and professional.

## What It Does

The Design Guide skill provides Claude with a complete set of design principles and guidelines for creating clean, professional user interfaces. When you ask Claude to build any UI component, this skill will automatically apply modern design best practices.

## Installation

1. Download the `design-guide.skill` file
2. Go to your Claude settings
3. Navigate to the Skills section
4. Click "Upload Skill" and select the `design-guide.skill` file

## When It's Used

The skill automatically activates when you're working on:
- HTML artifacts and web pages
- React components
- Dashboards and data visualizations
- Forms and input elements
- Buttons, cards, and other UI components
- Any visual interface design

## Core Principles

### ✅ DO:
- Use clean, minimal designs with lots of white space
- Stick to neutral grays (90%) with ONE accent color (10%)
- Follow the 8px spacing grid (8, 16, 24, 32, 48, 64px)
- Use 16px minimum for body text
- Create clear interactive states (hover, active, disabled)
- Design mobile-first

### ❌ DON'T:
- Use rainbow gradients or multiple accent colors
- Make text smaller than 16px
- Add inconsistent spacing
- Use heavy shadows everywhere
- Mix too many design styles
- Forget hover and focus states

## Quick Examples

### Good Button
```css
padding: 12px 24px;
border-radius: 8px;
box-shadow: 0 1px 3px rgba(0,0,0,0.1);
```

### Good Card
```css
padding: 24px;
border-radius: 12px;
border: 1px solid #E5E7EB; /* OR shadow, not both */
```

### Good Typography
- Headings: 24-48px, semibold
- Body: 16px minimum, line-height 1.6
- Max 2 font families

## Example Prompts

Try asking Claude:
- "Build me a dashboard with clean, modern design"
- "Create a contact form following design best practices"
- "Make a landing page with professional styling"
- "Design a card component with proper spacing and shadows"

Claude will automatically reference this skill to ensure your UI follows modern design standards.

## What Makes This Different

Instead of generic, cluttered designs, you'll get:
- **Consistent spacing** - Everything aligns properly
- **Professional colors** - No random rainbow effects
- **Clear hierarchy** - Proper text sizing and weights
- **Subtle elegance** - Gentle shadows, not overdone
- **Mobile-friendly** - Responsive from the start
- **Accessible** - Proper contrast and interactive states

## Support

The skill includes comprehensive guidelines for:
- Color systems and palettes
- Spacing and layout grids
- Typography hierarchy
- Shadow scales
- Border radius standards
- Component patterns (buttons, cards, forms)
- Interactive state design
- Mobile responsiveness
- Common mistakes to avoid

---

**Built for modern, professional UIs. Zero design experience required.**
