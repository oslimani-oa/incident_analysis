# Incident Analysis App

Interactive Sankey Diagram Generator for incident flow analysis.

## Available Versions

This repository contains three versions of the interactive Sankey diagram application:

### 1. [Incident_Flow_Sankey_Interactive.html](Incident_Flow_Sankey_Interactive.html)
**Original Version**
- Simple, clean design
- Basic functionality
- Green/blue color scheme
- Pre-selected ConfigItems

### 2. [Incident_Flow_Sankey_Colorful.html](Incident_Flow_Sankey_Colorful.html)
**Colorful Enhanced Version**
- Modern gradient backgrounds (purple/blue theme)
- Step indicator (Upload → Select → View)
- Select All / Deselect All buttons
- Incident count badges (visible only when selected)
- Improved stats display with card-based layout
- Reset button
- Animations and transitions
- Auto-scroll to diagram
- Items not pre-selected by default

### 3. [Incident_Flow_Sankey_Dark.html](Incident_Flow_Sankey_Dark.html)
**Dark Monochrome Version**
- Black and white theme
- Dark background (#1a1a1a)
- Professional monochromatic design
- All features from colorful version
- Items not pre-selected by default

## Features

All versions include:
- Drag and drop Excel file upload
- Dynamic ConfigItem detection
- Interactive Sankey diagram visualization
- UTC date parsing for consistency
- L0-L4 assignment group transformations
- November 2024 incident filtering

## Usage

1. Open any HTML file in a web browser
2. Upload your Excel file (drag & drop or click to browse)
3. Select ConfigItems to analyze
4. Click "Generate Sankey Diagram"

## Required Excel Columns

- IncidentCreationDate
- IncidentResolutionDate
- ConfigItem
- TypeOfIssue
- AssignmentGroup
- IncidentState
- CloseCode

## Live Demo

- Original: [https://oslimani-oa.github.io/incident_analysis/Incident_Flow_Sankey_Interactive.html](https://oslimani-oa.github.io/incident_analysis/Incident_Flow_Sankey_Interactive.html)
- Colorful: [https://oslimani-oa.github.io/incident_analysis/Incident_Flow_Sankey_Colorful.html](https://oslimani-oa.github.io/incident_analysis/Incident_Flow_Sankey_Colorful.html)
- Dark: [https://oslimani-oa.github.io/incident_analysis/Incident_Flow_Sankey_Dark.html](https://oslimani-oa.github.io/incident_analysis/Incident_Flow_Sankey_Dark.html)
