# Governance Landscape Study Portfolio

A comprehensive one-page portfolio showcase demonstrating governance landscape expertise through systematic research, analytical frameworks, and stakeholder analysis.

## Overview

This static site presents a governance research study covering:
- 23 stakeholder interviews
- 557 community votes analyzed
- 68 APAC survey respondents
- 15 future governance innovations catalogued
- Comprehensive scoring frameworks and stakeholder analysis

## Project Structure

```
governance-landscape-study/
├── index.html          # Single-page portfolio site
├── images/             # Image assets directory
│   ├── governance-pillars.png
│   ├── scoring-matrix.png
│   ├── stakeholder-pain.png
│   └── voting-models.png
└── README.md
```

## Images to Add

Extract and add the following images from your source materials:

### From Constellation Program FDS7.pptx:
1. **governance-pillars.png** - Three-pillar framework diagram (Economic/Operational/Protocol)
2. **scoring-matrix.png** - Voting model scoring comparison table
3. **voting-models.png** - Weighted vs unweighted voting comparison
4. **stakeholder-pain.png** - Pain points severity visualization

### From Notes & Structure Presentation.docx:
5. Community sentiment visualization
6. Stakeholder demographics chart

## How to Add Images

1. Extract images from PowerPoint:
   - Open `Constellation Program FDS7.pptx`
   - Right-click on the target diagrams/charts
   - Save as PNG files with the names listed above

2. Save to the `images/` directory

3. The HTML is already configured to display these images with graceful fallbacks

## Local Development

```bash
# Navigate to project directory
cd governance-landscape-study

# Start local server
python3 -m http.server 8000

# Visit http://localhost:8000
```

## Deployment to GitHub Pages

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit: Governance Landscape Study portfolio"

# Create GitHub repository
gh repo create governance-landscape-study --public --source=. --remote=origin

# Push to GitHub
git push -u origin master

# Enable GitHub Pages
gh repo edit --enable-pages --pages-branch master
```

Your site will be available at: `https://[username].github.io/governance-landscape-study/`

## Features

- **Responsive Design**: Mobile-friendly layout
- **Smooth Navigation**: Sticky nav with anchor links
- **Data Visualization**: Tables, grids, and comparison matrices
- **Clean Typography**: Professional, scannable layout
- **No Dependencies**: Pure HTML/CSS, no build step required

## Color Palette

- **Background**: #fff
- **Headings**: #111827
- **Body Text**: #4b5563
- **Accent**: #2563eb
- **Economic Pillar**: #7c3aed (purple)
- **Operational Pillar**: #059669 (green)
- **Protocol Pillar**: #d97706 (amber)
- **Card Backgrounds**: #f8fafc

## Key Sections

1. **Hero** - Overview and key metrics
2. **Research Methodology** - 4-phase process
3. **Governance Framework** - Pillars and voting taxonomy
4. **Scoring & Evaluation** - Comparison matrices
5. **Stakeholder Analysis** - Pain points mapping
6. **Future Innovations** - 15 emerging mechanisms
7. **Deliverables** - Research outputs

## Author

**Tanisha Katara**
Senior Governance Consultant, Filecoin

---

*This portfolio demonstrates systematic governance research expertise across the Web3 landscape.*
