---
layout: default
title: Depth Scan
parent: Template Inspector User Guide
nav_order: 2
---

# Depth Scan
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Depth Scan for Object Usage

Template Inspector performs comprehensive depth scans to find where objects are used throughout your files, including nested dependencies and indirect references.

### How Depth Scan Works
- **Primary Usage:** Direct assignments of objects (e.g., layer assigned to a line)
- **Secondary Usage:** Objects used within styles or other objects
- **Nested Dependencies:** Objects referenced through multiple levels of dependencies
- **Indirect References:** Objects used in complex relationships

### Steps to Perform Depth Scan
1. Select the objects you want to scan in the inspection interface.
2. Choose the scan depth level (shallow, medium, or deep).
3. Click "Perform Depth Scan" to begin the analysis.
4. Review the scan results showing all usage locations.

![Template Inspector depth scan](../../../assets/images/TemplateInspector/TI-DepthScan.gif)
<sub>Note: the version on the image may not reflect the latest version of Template Inspector.</sub>

### Scan Results
- Complete list of where objects are used
- Dependency hierarchy showing relationships
- Risk assessment for deletion or modification
- Recommendations for safe batch operations 
