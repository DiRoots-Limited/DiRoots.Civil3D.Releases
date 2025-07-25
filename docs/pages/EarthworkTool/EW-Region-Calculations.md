---
layout: default
title: Region Calculations
parent: Earthwork Tool User Guide
nav_order: 3
---

# Region Calculations
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Multiple Region Surface Calculations

The Earthwork Tool enables you to define multiple regions within your project and calculate cut and fill volumes for each region separately. This is useful for phased construction, zones, or areas with different grading requirements.

### Steps to Calculate by Region
1. Select the "Region Calculations" tab in the Earthwork Tool interface.
2. Use the region drawing tool to define one or more regions on your site.
3. Assign surfaces (existing, proposed, subgrade, etc.) to each region as needed.
4. Click "Calculate" to compute cut and fill for each region.

![Earthwork Tool region calculations](../../../assets/images/EarthworkTool/EW-RegionCalculations.gif)
<sub>Note: the version on the image may not reflect the latest version of Earthwork Tool.</sub>

### Output
- The tool displays a table with cut and fill volumes for each region.
- Results are shown in your preferred units.
- Export the table for reporting or further analysis.

```yaml
# Example Output Table
| Region | Cut (m³) | Fill (m³) |
|--------|----------|-----------|
| 1      | 500      | 300       |
| 2      | 700      | 650       |
``` 
