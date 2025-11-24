# SIA Timeline Graph

An interactive timeline visualization component with a modern, visually appealing design.

## Features

- 🎨 Modern UI with gradient backgrounds and glassmorphism effects
- ✨ Smooth animations and transitions
- 🖱️ Interactive year selection with hover effects
- 📊 Visual representation of strategy periods
- 🎯 Current year indicator
- 📱 Responsive design

## Demo

Visit the live demo: [https://gaetanopiazzolla.github.io/sia-timeline-graph/](https://gaetanopiazzolla.github.io/sia-timeline-graph/)

## Usage

The timeline graph is a reusable JavaScript component that can be easily integrated into any web project.

```javascript
const timeline = new TimelineGraph({
    containerId: 'timeline-graph-container',
    startYear: 2023,
    endYear: 2030,
    strategyInitYear: 2024,
    targetYear: 2029,
    currentYear: 2025,
    height: 200,
    onChange: (targetYear) => {
        console.log('Target year changed to:', targetYear);
    }
});
```

## Configuration Options

- `containerId`: ID of the container element
- `startYear`: Starting year of the timeline
- `endYear`: Ending year of the timeline
- `strategyInitYear`: Year when strategy period begins
- `targetYear`: Target/goal year
- `currentYear`: Current year (defaults to current date)
- `height`: Canvas height in pixels
- `onChange`: Callback function when target year changes

## Visual Design

- **Purple Gradient Background**: Modern gradient with glassmorphism card effects
- **Enhanced Timeline**: Gradient-colored timeline with thicker strategy period segments
- **Interactive Markers**: Different shapes for different year types (triangles, squares, circles)
- **Smooth Animations**: Entrance animations and hover effects throughout
- **Professional Typography**: Clean, modern font with gradient text effects

## License

MIT
