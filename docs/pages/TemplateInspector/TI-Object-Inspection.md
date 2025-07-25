---
layout: default
title: Object Inspection
parent: Template Inspector User Guide
nav_order: 2
---

# Object Inspection
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Inspecting Object Usage

Template Inspector supports inspecting multiple object types to find where they are used in your files, helping you identify dependencies and make informed decisions about deletion or modification.

### Supported Object Types
- **Layers:** Inspect layer usage across all objects and styles
- **Line Types:** Find where line types are assigned
- **Hatch Styles:** Locate hatch pattern usage
- **Dimension Styles:** Check dimension style assignments
- **Text Styles:** Find text style usage throughout the file

### Steps to Inspect Objects
1. Select the "Object Inspection" tab in the Template Inspector interface.
2. Choose the object type you want to inspect (layers, line types, etc.).
3. Select specific objects or use "Select All" to inspect all objects of that type.
4. Click "Inspect" to begin the analysis.

![Template Inspector object inspection](../../../assets/images/TemplateInspector/TI-ObjectInspection.gif)
<sub>Note: the version on the image may not reflect the latest version of Template Inspector.</sub>

### Inspection Results
- The tool displays a list of all selected objects
- Shows usage status (used/not used) for each object
- Provides details about where objects are assigned or referenced 