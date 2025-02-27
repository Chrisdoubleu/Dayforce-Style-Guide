# Complete Policy Document Stylesheet (v1.0)

A comprehensive CSS for creating consistent, professional HR policy documents within our Ceridian Dayforce environment. It unifies typography, spacing, headings, sections, lists, and interactive components to streamline policy presentation.

---

## Overview

- **Purpose**: Provide a single, maintainable stylesheet for HR policy documentation to ensure uniform formatting and branding.  
- **Scope**: Covers color variables, fonts, layout, specialized list styles, panels, and print-friendly rules.  
- **Last Updated**: February 27, 2025

---

## Key Features

1. **Theming**: Custom properties for colors, spacing, and typography, plus theme variants for different policy types (legal, HR, security).
2. **Responsive & Print-Friendly**: Media queries for various device sizes, plus optimized print layouts.
3. **Rich Typography & Layout**: Hierarchical headings, utility classes for spacing and alignment, decorative transitions.
4. **Advanced Lists & Panels**: Multi-level lists (`.secondary-list`, `.tertiary-list`), callouts (`.policy-notice`, `.policy-warning`), and more.
5. **Interactive Elements**: Custom checkboxes (`.custom-checkbox`), date pickers, and comment boxes for forms or advanced interactivity.

---

## Usage

1. **Include the CSS**  
   Add this line to any HTML (or Dayforce custom code editor) in the `<head>`:
   ```html
   <link rel="stylesheet"
         href="https://chrisdoubleu.github.io/Dayforce-Style-Guide/HR-Policy-Document-Stylesheet-v1.0.css">
