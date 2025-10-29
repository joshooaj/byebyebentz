# Images Directory

This directory contains visual assets for the Oregon Deserves Better website.

## Directory Structure

- `/voting-records/` - Screenshots of official voting records
- `/news-coverage/` - News articles and headlines about Bentz's failures  
- `/town-halls/` - Documentation of empty town halls or protests
- `/infographics/` - Custom graphics showing impact data
- `/portraits/` - Professional photos for context

## File Naming Convention

Use descriptive filenames that include:
- Date (if applicable): `YYYY-MM-DD_`
- Subject: `bentz-`
- Topic: `healthcare-vote`, `townhall-cancelled`, etc.
- File type: `.jpg`, `.png`, `.svg`

### Examples
- `2023-03-15_bentz-healthcare-vote.jpg`
- `2023-06-20_bend-townhall-cancelled.png`
- `rural-hospital-closures-infographic.svg`

## Image Requirements

### Technical Specifications
- **Web optimization**: Compress for fast loading
- **Responsive**: Include multiple sizes if needed
- **Accessibility**: Always include descriptive alt text
- **Format**: JPG for photos, PNG for graphics with transparency, SVG for scalable graphics

### Content Guidelines
- **Professional quality**: Clear, well-lit, properly framed
- **Copyright compliance**: Only use images with proper licensing
- **Context**: Include source information and dates
- **Accuracy**: Ensure images accurately represent the facts

## Alt Text Guidelines

Always provide descriptive alt text for accessibility:

### Good Examples
- `Screenshot of congressional voting record showing Cliff Bentz voted Yes on HR-1234 healthcare bill`
- `News headline from East Oregonian: Bentz Cancels Town Hall After Protest Concerns`
- `Infographic showing 3 rural hospitals closed in Oregon District 2 since 2020`

### Poor Examples  
- `Bentz vote`
- `News article`
- `Chart`

## Usage in Website

Images are referenced in HTML with proper alt text:
```html
<img src="./images/voting-records/2023-03-15_bentz-healthcare-vote.jpg" 
     alt="Screenshot of congressional voting record showing Cliff Bentz voted Yes on HR-1234 healthcare bill">
```

---
*Add image files to the appropriate subdirectories*