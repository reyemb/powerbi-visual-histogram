# Power BI Histogram Visual

A custom histogram visual for Power BI with cross-filtering, statistical overlays, and extensive formatting options.

## Features

- **Cross-filtering**: Click on bars to filter other visuals
- **Statistical analysis**: Display mean, median, standard deviation, and variance lines
- **Configurable bins**: Set bin count or bin size
- **Custom vertical lines**: Draw reference lines based on input data with JSON-based color configuration
- **Multi-language support**: English, German, French, Spanish, Italian
- **Extensive formatting**: Customize colors, margins, fonts, and line styles

## Installation

1. Download the `.pbiviz` file from the `dist/` folder
2. In Power BI Desktop, go to the Visualizations pane
3. Click the ellipsis (...) and select "Import a visual from a file"
4. Select the downloaded `.pbiviz` file

## Usage

1. Add the visual to your report
2. Drag a numeric field to the "Values" data role
3. Optionally add fields to "Vertical Lines" for reference markers
4. Use the Format pane to customize appearance and enable statistical overlays

Demo videos are available in the `/demo` folder.

## Development

```bash
# Install Power BI visual tools
npm install -g powerbi-visuals-tools

# Install dependencies
npm install

# Start development server
npm run start

# Build the visual
npm run package
```

To test, enable the Developer visual in Power BI service under Settings > Developer settings.

## Dependencies

- D3.js for chart rendering
- Power BI Visuals API 5.3.0
- powerbi-visuals-utils (formatting, interactivity, tooltips)

## License

GNU GPLv3
