# Claude Code Configuration

## Project Overview
This project contains custom Claude Code skills for creating interactive presentations, animations, data visualizations, and animated UI components.

## Available Skills

### 🎬 Frontend Slides
Create interactive presentations with smooth transitions and multiple layouts.
- **File**: `.claude/skills/frontend-slides/SKILL.md`
- **Use it by saying**: "Make slides about [topic]"
- **Features**: Multiple layouts, smooth transitions, keyboard navigation, themes

### ✨ Animation
Create smooth, engaging animations and motion effects.
- **File**: `.claude/skills/animation/SKILL.md`
- **Use it by saying**: "Create an animation of [description]"
- **Features**: Spinners, hover effects, motion graphics, particles

### 📊 Data Charts
Create interactive data visualizations and charts.
- **File**: `.claude/skills/data-charts/SKILL.md`
- **Use it by saying**: "Create a chart of [data]"
- **Features**: Bar, line, pie, scatter, heatmaps

### 📈 Animated Charts
Create animated data visualizations with smooth transitions.
- **File**: `.claude/skills/animated-charts/SKILL.md`
- **Use it by saying**: "Create an animated chart of [data]"
- **Features**: Entry animations, transitions, playback controls

### 🧩 Animated HTML Components
Create reusable animated UI components and elements.
- **File**: `.claude/skills/animated-html-components/SKILL.md`
- **Use it by saying**: "Create an animated [button/card/modal/etc]"
- **Features**: Buttons, cards, dropdowns, carousels, modals

## How to Use These Skills

1. **In Claude Code CLI**:
   ```bash
   claude-code
   ```
   Then ask me to create content using any skill.

2. **In Claude Web** (claude.ai/code):
   - Open this repository
   - Ask me to create slides, animations, charts, or components
   - The skills will be automatically applied

3. **Direct Usage Examples**:
   - "Make slides about web development"
   - "Create a loading spinner animation"
   - "Make a bar chart of Q1 sales"
   - "Build an animated dashboard"
   - "Create an animated button component"

## Skill Integration

All skills are located in `.claude/skills/` directory:
```
.claude/
└── skills/
    ├── frontend-slides/
    │   └── SKILL.md
    ├── animation/
    │   └── SKILL.md
    ├── data-charts/
    │   └── SKILL.md
    ├── animated-charts/
    │   └── SKILL.md
    └── animated-html-components/
        └── SKILL.md
```

## For Your Presentation Slides

When working on presentation slides:

1. **Ask me to make slides** with any topic
2. **I'll automatically apply** the `frontend-slides` skill
3. **Get an interactive presentation** ready to use

Example:
```
You: "Make slides about React hooks with 8 slides"
→ I create an interactive presentation using the frontend-slides skill
→ You get HTML artifact with working slides
```

## Workflow

### Creating Slides
1. Describe what you want
2. I apply the frontend-slides skill
3. You get an interactive HTML presentation
4. Customize colors, content, or layout as needed

### Adding Animations
1. Describe the animation effect
2. I apply the animation skill
3. You get smooth, performant animations
4. Use in your presentations or projects

### Visualizing Data
1. Provide your data
2. I apply data-charts or animated-charts skill
3. You get beautiful, interactive charts
4. Embed in presentations or dashboards

### Creating Components
1. Describe the UI component
2. I apply animated-html-components skill
3. You get copy-paste ready code
4. Customize and integrate into your project

## Quick Reference

| Need | Skill | Command |
|------|-------|---------|
| Presentation slides | frontend-slides | "Make slides about [topic]" |
| Animations | animation | "Create an animation of [effect]" |
| Data charts | data-charts | "Create a chart of [data]" |
| Animated charts | animated-charts | "Create an animated chart" |
| UI components | animated-html-components | "Create an animated [component]" |

## Skills Showcase

View all skills and their capabilities in the interactive showcase:
- **Location**: Skills showcase website (interactive HTML)
- **Features**: Detailed descriptions, examples, usage tips
- **Access**: Open `skills-showcase.html` in your browser

## Best Practices

### For Slides
- Keep text concise and use bullet points
- Use visuals to enhance content
- One main idea per slide
- 5-10 slides for short presentations

### For Animations
- Use to enhance UX, not distract
- Match animation speed to content
- Respect user's motion preferences
- Test on different devices

### For Charts
- Choose chart type based on data
- Label everything clearly
- Use accessible color schemes
- Include data sources

### For Components
- Keep components focused
- Provide keyboard navigation
- Make components customizable
- Document usage

## Repository Information

- **Repo**: `ig-ga/for-claude`
- **Branch**: `claude/frontend-slides-skill-ojyw1c`
- **Skills Created**: 5 custom interactive skills
- **Status**: Ready to use

## Getting Started

1. **Clone the repository** with this branch
2. **Open Claude Code** in your terminal or web
3. **Ask me to create** slides, animations, or components
4. **Skills activate automatically** and create your content
5. **Customize** the output as needed

## Examples to Try

### Create a Presentation
```
"Make slides about machine learning fundamentals with 6 slides"
```

### Create an Animation
```
"Create a bouncing ball animation with physics"
```

### Create a Chart
```
"Make a pie chart showing market share data"
```

### Create Animated Components
```
"Build an animated loading spinner component"
```

## Support & Customization

All skills are fully customizable:
- Colors and themes
- Animation speed and easing
- Chart types and styling
- Component sizes and variations

Just describe what you want and I'll apply the appropriate skill!

---

**Ready to create amazing content? Just ask!** ✨
