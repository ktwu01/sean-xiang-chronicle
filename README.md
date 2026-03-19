# Animated Chronicle Template

An animated founder/professional chronicle project featuring:
- Research dossier
- Milestone timeline
- Geographic journey map
- Landing page / tribute page
- TimelineJS + StoryMapJS integration

Originally created for Sean Xiang / Bloombase by Koutian Wu <https://github.com/ktwu01/>

---

## Customization Guide

This template can be adapted to create a chronicle for any person. Follow these instructions when working with your coding agent to transform the content.


### Example Prompt for Your Agent

```
I want to adapt this chronicle from Sean Xiang to [NEW SUBJECT NAME].

[NEW SUBJECT NAME] this should be very clear. You should make sure you are 100% sure about this (because different people can have same names). Otherwise you should ask me clarifying questions.

1. Search for [NEW SUBJECT NAME]'s timeline on LinkedIn and other public records
2. Replace all Sean Xiang content with [NEW SUBJECT NAME] content
3. Keep all original styles, layouts, and functionality intact
4. Update ALL files including index.html, news-index.html, and all data files
5. Make sure to read and modify every file in the project

Please read all files first, then systematically update each one.
```

### Instructions for Your Coding Agent

**Mode:** Use `vibe` mode (direct conversation) - do not use spec mode.

**Core Principle:** Keep all original styles and structure. Only change the content from the current subject to your new subject.

### Step-by-Step Process

1. **Create a new branch** from a working commit (e.g., `08f2f2538f089fe85a1f29b9a2cab98615a861f6`)

Then follow the conversion such as the conversion from Sean Xiang to Eric C. Greene in  `89ee2dcde56ca155793af1ccd56bcb518492cd58`.

2. **Research your subject:**
   - Search LinkedIn for professional timeline
   - Gather information from public records
   - Collect biographical data, milestones, and locations

3. **Update all content files:**
   - Read ALL files in the project, including:
     - `index.html`
     - `news-index.html`
     - All JSON files in `/data/` directory
     - All markdown files in `/research/` directory
   - Replace subject-specific content while preserving:
     - HTML structure and CSS styles
     - JavaScript functionality
     - JSON data schemas
     - Layout and design elements

4. **Verify completeness:**
   - Double-check that ALL files have been updated
   - Ensure map points are displaying correctly
   - Test timeline functionality
   - Verify chapter navigation works properly


### Testing Locally

Run a local server to preview your changes:
```bash
python -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.

### Known Issues to Watch For

- **Banner overlap:** If you have many chapters (e.g., 12+), the banner may overlap chapter headings. Adjust banner height or chapter positioning if needed.
- **Map functionality:** Ensure geographic points display correctly after content changes.

Here is the prompt to fix it:
```
now its not rendering correctly: the website map only show the same place/cannot change/always be at florida whenever I click a chapter/the map just does not move. You should help me fix it using the correct format like the commit ID = `89ee2dcde56ca155793af1ccd56bcb518492cd58` 
```

- **Timeline rendering:** Verify all timeline events render properly with new data.

---

## Project Structure

- `/data/` - JSON data files for timeline, locations, artifacts, etc.
- `/research/` - Markdown research documents and dossiers
- `index.html` - Main chronicle page
- `news-index.html` - News/updates index page

---

## Reference: Successful Conversion Example

A successful conversion was completed in commit `89ee2dcde56ca155793af1ccd56bcb518492cd58`, which demonstrates the proper approach to adapting this template while maintaining all styles and functionality.
