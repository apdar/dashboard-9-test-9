# Dashboard Project

This repository contains UI components for creating data dashboards.

## Available Components

- **Table**: Display data in tabular format
- **Charts**: Visualize data with various chart types (bar, line, pie, etc.)
- **Cards**: Show summaries and key metrics
- **Navigation**: Dashboard navigation menu
- **Overview**: Summary statistics section
- **Comparison**: Compare data fields

## Usage

Create a single HTML file that includes:
1. The necessary UI components from the `components/` directory
2. Your data embedded in the HTML
3. JavaScript to initialize and populate the components with your data

## Customization

You can customize the look and feel by:
- Modifying the CSS in `components/styles.css`
- Changing colors, fonts, and spacing
- Adding custom styling to match your brand

## Example

```html
<!DOCTYPE html>
<html>
<head>
    <title>My Dashboard</title>
    <link rel="stylesheet" href="components/styles.css">
</head>
<body>
    <!-- Include navigation -->
    <!-- Include overview -->
    <!-- Include charts -->
    <!-- Include data table -->
    
    <script>
        // Your data
        const data = [...];
        
        // Initialize components
        createTable(data, ['column1', 'column2']);
        createChart('bar', labels, datasets, 'Chart Title');
        createOverview(stats);
    </script>
</body>
</html>
```
