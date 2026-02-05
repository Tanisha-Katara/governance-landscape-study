# Image Assets Instructions

This directory should contain the following images extracted from your source materials:

## Required Images

### From "Constellation Program FDS7.pptx":

1. **governance-pillars.png**
   - The three-pillar framework diagram showing Economic, Operational, and Protocol governance
   - Should clearly show the categorization and examples for each pillar

2. **scoring-matrix.png**
   - The 4×6 comparison table with color-coded scores
   - Voting models (Vote Escrow, Reputation, Quadratic, Representative) vs criteria
   - Color coding: Green (5), Yellow (3-4), Red (2)

3. **voting-models.png**
   - Weighted vs unweighted voting power distribution comparison
   - Visual showing how different models distribute voting power

4. **stakeholder-pain.png**
   - Pain points severity/priority visualization
   - Chart showing FIP Editors, Implementers, Core Devs, Storage Providers issues

### From "Notes & Structure Presentation.docx" (optional):

5. **community-sentiment.png**
   - Community sentiment visualization from surveys

6. **stakeholder-demographics.png**
   - Geographic or role-based stakeholder breakdown

## How to Extract Images

### From PowerPoint (.pptx):

1. Open "Constellation Program FDS7.pptx" in PowerPoint
2. Navigate to the slide with the target diagram
3. Right-click on the image/chart
4. Select "Save as Picture..."
5. Choose PNG format
6. Save with the filename listed above
7. Move to this `images/` directory

### From Word (.docx):

1. Open "Notes & Structure Presentation.docx" in Word
2. Right-click on the image
3. Select "Save as Picture..."
4. Choose PNG format
5. Save with the filename listed above
6. Move to this `images/` directory

## After Adding Images

1. Commit the images:
   ```bash
   cd governance-landscape-study
   git add images/
   git commit -m "Add governance research visualization assets"
   git push origin master
   ```

2. Verify on the live site (GitHub Pages may take 1-2 minutes to rebuild):
   - Visit: https://tanisha-katara.github.io/governance-landscape-study/
   - Check that all images display correctly
   - Verify responsive layout on mobile

## Image Specifications

- **Format**: PNG (preferred for charts/diagrams)
- **Resolution**: At least 1200px wide for clarity
- **File Size**: Keep under 500KB each for fast loading
- **Background**: Transparent or white background preferred

## Current Status

The HTML is already configured to:
- Display these images in the appropriate sections
- Show graceful fallbacks if images are missing
- Include descriptive captions
- Maintain responsive scaling on all devices

**Next Step**: Extract and add the 4 key images listed above to make the portfolio visually complete.
