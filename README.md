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
2. Replace all Sean Xiang content with [NEW SUBJECT NAME] content.
3. Keep all original styles, layouts, and functionality intact
4. Update ALL files including index.html and all data files
5. Make sure to read and modify every file in the project.
6. After the modification, you should review at least three times. You can refer to README.md for more information.


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

---

## Reference: Successful Conversion Example

A successful conversion was completed in commit `89ee2dcde56ca155793af1ccd56bcb518492cd58`, which demonstrates the proper approach to adapting this template while maintaining all styles and functionality.

---

## Live forks built from this template

These are the chronicles that have been adapted from this template. Each is a live GitHub Pages site:

| Subject | Repository | Live site |
|---------|------------|-----------|
| Sean Xiang (original) | [ktwu01/sean-xiang-chronicle](https://github.com/ktwu01/sean-xiang-chronicle) | [ktwu01.github.io/sean-xiang-chronicle](https://ktwu01.github.io/sean-xiang-chronicle/) |
| Chen Ning Yang (杨振宁) | [ut01/chen-ning-yang-chronicle](https://github.com/ut01/chen-ning-yang-chronicle) | [ut01.github.io/chen-ning-yang-chronicle](https://ut01.github.io/chen-ning-yang-chronicle/) |
| Daniella Rempe | [ut01/daniella-rempe-chronicle](https://github.com/ut01/daniella-rempe-chronicle) | [ut01.github.io/daniella-rempe-chronicle](https://ut01.github.io/daniella-rempe-chronicle/) |
| Ashley Matheny | [ut01/ashley-matheny-chronicle](https://github.com/ut01/ashley-matheny-chronicle) | [ut01.github.io/ashley-matheny-chronicle](https://ut01.github.io/ashley-matheny-chronicle/) |
| Gengchen Mai | [ut01/gengchen-mai-chronicle](https://github.com/ut01/gengchen-mai-chronicle) | [ut01.github.io/gengchen-mai-chronicle](https://ut01.github.io/gengchen-mai-chronicle/) |
| Marc Hesse | [ut01/marc-hesse-chronicle](https://github.com/ut01/marc-hesse-chronicle) | [ut01.github.io/marc-hesse-chronicle](https://ut01.github.io/marc-hesse-chronicle/) |
| Geeta Persad | [ut01/geeta-persad-chronicle](https://github.com/ut01/geeta-persad-chronicle) | [ut01.github.io/geeta-persad-chronicle](https://ut01.github.io/geeta-persad-chronicle/) |
| Kehan Dong | [ut01/kehan-dong-chronicle](https://github.com/ut01/kehan-dong-chronicle) | [ut01.github.io/kehan-dong-chronicle](https://ut01.github.io/kehan-dong-chronicle/) |
| Koutian Wu | [ut01/koutian-wu-chronicle](https://github.com/ut01/koutian-wu-chronicle) | [ut01.github.io/koutian-wu-chronicle](https://ut01.github.io/koutian-wu-chronicle/) |
| Juan Santiago | [qijiang-yoyo/juan-santiago-chronicle](https://github.com/qijiang-yoyo/juan-santiago-chronicle) | [qijiang-yoyo.github.io/juan-santiago-chronicle](https://qijiang-yoyo.github.io/juan-santiago-chronicle/) |
| Zong-Liang Yang | [ktwugoat/zong-liang-yang-chronicle](https://github.com/ktwugoat/zong-liang-yang-chronicle) | [ktwugoat.github.io/zong-liang-yang-chronicle](https://ktwugoat.github.io/zong-liang-yang-chronicle/) |
| Eric C. Greene | [yzliu03/Eric-Greene-chronicle](https://github.com/yzliu03/Eric-Greene-chronicle) | [yzliu03.github.io/Eric-Greene-chronicle](https://yzliu03.github.io/Eric-Greene-chronicle/) |

If you've forked this template, open a PR adding your chronicle here so other contributors can find it.
