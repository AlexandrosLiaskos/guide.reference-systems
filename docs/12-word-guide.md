# Microsoft Word Citations Guide

## Overview

Microsoft Word has built-in citation and bibliography tools. This guide covers Word 365/2019/2021.

---

## Accessing Citation Tools

**Location:** References tab → Citations & Bibliography group

Key buttons:
- **Insert Citation** - Add inline citation
- **Manage Sources** - View/edit all sources
- **Style** - Change citation format
- **Bibliography** - Insert reference list

---

## Adding a New Source

### Method 1: While Writing
1. Place cursor where citation goes
2. References → Insert Citation → Add New Source
3. Select source type from dropdown
4. Fill in fields and click OK
5. Citation inserts automatically

### Method 2: From Source Manager
1. References → Manage Sources
2. Click "New" button
3. Select source type
4. Fill in required fields
5. Click OK

---

## Source Types Available

| Type | Use For |
|------|---------|
| Book | Single or multi-author books |
| Book Section | Chapter in edited book |
| Journal Article | Academic journal papers |
| Article in Periodical | Magazine/newspaper articles |
| Conference Proceedings | Conference papers |
| Report | Technical/research reports |
| Website | Web pages |
| Document from Website | Online documents/PDFs |
| Electronic Source | Digital media |
| Film | Movies, documentaries |
| Interview | Published interviews |
| Sound Recording | Music, podcasts, audio |
| Performance | Plays, concerts |
| Art | Artwork, photographs |
| Patent | Patents |
| Case | Legal cases |
| Misc | Anything else |

---

## Filling in Source Details

### Required Fields (vary by type)

**Book:**
- Author (Last, First)
- Title
- Year
- City
- Publisher

**Journal Article:**
- Author
- Title
- Journal Name
- Year
- Pages
- Volume (optional)
- Issue (optional)

**Website:**
- Author (or organization)
- Name of Web Page
- Year
- URL
- Year Accessed, Month Accessed, Day Accessed

### Tips for Author Field
- Single author: `Smith, John`
- Two authors: `Smith, John; Jones, Mary`
- Organization: `World Health Organization`
- Check "Corporate Author" box for organizations

---

## Inserting Citations

### Single Source
1. Position cursor in text
2. References → Insert Citation
3. Select source from dropdown
4. Citation appears: (Smith, 2024)

### Same Source Again
- Click Insert Citation → Select same source from list
- Word reuses the existing source

### Multiple Sources in One Citation
1. Insert first citation normally
2. Click inside the citation
3. Insert Citation → Add another source
4. Both appear: (Smith, 2024; Jones, 2023)

### Citation with Page Number
1. Click on existing citation
2. Small dropdown arrow appears
3. Click arrow → Edit Citation
4. Enter page number in "Pages" field
5. Result: (Smith, 2024, p. 45)

### Suppress Author or Year
1. Click on citation → dropdown → Edit Citation
2. Check boxes:
   - "Suppress Author" → (2024)
   - "Suppress Year" → (Smith)

---

## Changing Citation Style

### Quick Style Change
1. References tab → Style dropdown
2. Select style:
   - APA
   - Chicago
   - Harvard
   - IEEE
   - MLA
   - And others...

### All Citations Update Automatically
- Changing style reformats all citations
- Bibliography also updates

---

## Creating the Bibliography

### Insert Bibliography
1. Position cursor at end of document
2. References → Bibliography
3. Choose format:
   - **Bibliography** - Titled "Bibliography"
   - **References** - Titled "References"
   - **Works Cited** - Titled "Works Cited"

### Update Bibliography
After adding/removing citations:
1. Click anywhere in bibliography
2. Click "Update Citations and Bibliography"

Or right-click bibliography → Update Field

---

## Managing Sources

### Source Manager
References → Manage Sources

Two lists:
- **Master List** - All sources ever created (stored in Word)
- **Current List** - Sources in this document

### Copy Sources Between Lists
1. Select source in Master List
2. Click "Copy →" to add to current document
3. Or select in Current List → "← Copy" to Master List

### Edit a Source
1. Select source in either list
2. Click "Edit"
3. Make changes
4. Click OK
5. Citations in document update

### Delete a Source
1. Select source
2. Click "Delete"
3. ⚠️ Citations using this source will show as errors

---

## Importing/Exporting Sources

### Export Sources
1. Sources stored in: `%appdata%\Microsoft\Bibliography\Sources.xml`
2. Copy this file to back up your sources
3. Or share with colleagues

### Import Sources
1. Copy Sources.xml to the same location on new computer
2. Or: Manage Sources → Browse → Select XML file

---

## Common Issues & Fixes

### Citation Shows as {Author, Year}
- Field codes are showing
- Press Alt + F9 to toggle view
- Or: Right-click → Toggle Field Codes

### Source Not in Dropdown
1. Manage Sources
2. Check if source is in "Current List"
3. If in Master List only, click "Copy →"

### Wrong Citation Format
- Check Style dropdown is set correctly
- Some styles not built-in - need download or reference manager

### Bibliography Not Updating
1. Click inside bibliography
2. Press F9 to refresh
3. Or right-click → Update Field

### Duplicate Sources
1. Manage Sources
2. Look for duplicates in Current List
3. Delete extra copies
4. Update citations manually if needed

---

## Keyboard Shortcuts

| Action | Shortcut |
|--------|----------|
| Insert citation | Alt + Shift + I (after References tab) |
| Update field (bibliography) | F9 |
| Toggle field codes | Alt + F9 |
| Select entire field | Click citation + F9 |

---

## Quick Workflow

```
1. SET STYLE
   └── References → Style → Select format

2. ADD SOURCES
   └── Insert Citation → Add New Source (as you write)

3. INSERT CITATIONS
   └── Insert Citation → Select from list

4. ADD PAGE NUMBERS
   └── Click citation → Edit Citation → Add pages

5. INSERT BIBLIOGRAPHY
   └── References → Bibliography → Choose format

6. UPDATE AS NEEDED
   └── Click bibliography → Update Citations and Bibliography
```

---

## Word vs. Reference Managers

| Feature | Word Built-in | Reference Manager (Mendeley, Zotero) |
|---------|---------------|-------------------------------------|
| Basic citations | ✓ | ✓ |
| Citation styles | ~15 built-in | 2000+ |
| PDF storage | ✗ | ✓ |
| Browser import | ✗ | ✓ |
| Cloud sync | Via OneDrive | Built-in |
| Collaboration | Limited | Better |
| Annotations | ✗ | ✓ |
| Large projects | Can slow down | Better performance |

**Recommendation:**
- Small projects (< 30 sources): Word built-in is fine
- Larger projects or ongoing research: Use a reference manager

---

## Tips for Large Documents

1. **Save frequently** - Large bibliographies can slow Word
2. **Use Master Document** feature for multi-chapter works
3. **Lock field codes** before final formatting
4. **Consider reference manager** for 50+ sources
5. **Back up Sources.xml** regularly

---

*Previous: [Mendeley Guide](11-mendeley-guide.md)*
