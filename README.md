# Agentic Blueprint — Design Token Studio

A robust, interactive design token system and theme editor. Build, preview, and export your design system seamlessly with a smart color engine and a real-time "Kitchen Sink" component preview.

## Features

- **Theme Editor**: Real-time manipulation of colors, typography, border radius, and spacing variables.
- **Smart Color Engine**: Automatically derives complementary secondary colors, interaction states, and smart inversion logic for dynamic dark mode support.
- **Kitchen Sink Demo**: Live preview of your design system directly applied to various UI components (swatches, buttons, typography specimens, data cards).
- **Dark Mode Integration**: Seamlessly toggle between light and dark themes with intelligent contrast adjustments.
- **Export & Import**: Save your curated design tokens to JSON presets

## Quick Start

1. Clone or download the repository.
2. Open `index.html` in your modern web browser or serve it using a local development server (like VS Code Live Server).
3. Use the sidebar controls on the right to customize the design tokens.
4. View real-time changes applied instantly in the Kitchen Sink demo space.

## File Structure

- `index.html`: The main Application (Theme Editor and Kitchen Sink demo).
- `docs.html`: Documentation page outlining system usage and components.
- `tokens.css`: Core CSS custom properties defining the starting design system variables.

## How to Apply to Your Project

Once you have tweaked the tokens to your satisfaction, simply export the CSS variables generated from the studio and drop them into the `:root` of your web project's CSS baseline. All elements consuming these semantic variables will automatically adopt your new design.

## contact: stepan.dev@outlook.cz
## licence: CC BY-NC 4.0
