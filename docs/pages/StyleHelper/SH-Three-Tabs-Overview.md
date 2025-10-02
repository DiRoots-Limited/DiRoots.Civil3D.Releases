---
layout: default
title: Three Tabs Overview
parent: Style Helper User Guide
nav_order: 2
---

# Tabs Overview
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Tabs Overview

Style Helper provides three main tabs that correspond to the different types of styles available in Civil 3D. Each tab displays data in a table format where you can view and edit style properties directly.

## Overview

The three tabs correspond to Civil 3D's style structure:

- **Object Styles Tab** - Civil 3D object styles (surfaces, alignments, corridors, etc.)
- **Label Styles Tab** - Civil 3D label styles (point labels, parcel labels, etc.)  
- **Table Styles Tab** - Civil 3D table styles (quantity takeoff, surface tables, etc.)

> **GIF Placeholder:** Show the three-tab interface and navigation between tabs and structure from C3D

## Object Styles Tab

### Civil 3D Object Styles Structure

In Civil 3D Settings, the objects have three main structure types. The Object Styles tab focuses on the object styles:

- **Surface Styles** - Display and analysis styles for surfaces
- **Alignment Styles** - Display and annotation styles for alignments
- **Corridor Styles** - Display and component styles for corridors
- **Profile Styles** - Display and annotation styles for profiles
- **Section Styles** - Display and annotation styles for sections
- **Pipe Styles** - Display styles for pipes and structures


## Label Styles Tab

### Civil 3D Label Styles Structure

Label styles in Civil 3D have their own structure and properties:

- **Point Label Styles** - Annotation styles for points
- **Line Label Styles** - Label styles for lines and curves
- **Area Label Styles** - Label styles for areas and regions
- **General Label Styles** - General annotation styles
- **Profile Label Styles** - Label styles for profiles
- **Section Label Styles** - Label styles for sections


## Table Styles Tab

### Civil 3D Table Styles Structure

Table styles in Civil 3D have their own structure for different table types:

- **Quantity Takeoff Tables** - Styles for quantity takeoff tables
- **Surface Tables** - Styles for surface analysis tables
- **Alignment Tables** - Styles for alignment tables
- **Profile Tables** - Styles for profile tables
- **Section Tables** - Styles for section tables
- **Pipe Tables** - Styles for pipe and structure tables

> **GIF Placeholder:** Show Table Styles tab with component structure

## Component Column Reference

The **Component column** is the fundamental object identification that applies to all three tabs. It uses a naming structure similar to the Civil 3D tree structure, making it easy to locate objects you're working on in Civil 3D.

### Component Path Structure

**Example Component Path:**
```
Alignment Styles/Roadway Centerline Alignment Proposed - ATG/Display/Plan/Line
```

This path structure shows:
- **Object Type** - "Alignment Styles" (matches Civil 3D tree)
- **Object Name** - "Roadway Centerline Alignment Proposed - ATG" (matches Civil 3D tree)
- **Subcomponents** - "Display/Plan/Line" (internal object structure)

### Component Column Examples

#### Object Styles Example
```
Alignment Styles/Roadway Centerline Alignment Proposed - ATG/Display/Plan/Line
Alignment Styles/Roadway Centerline Alignment Proposed - ATG/Display/Plan/Curve
Alignment Styles/Roadway Centerline Alignment Proposed - ATG/Display/Plan/Spiral
```

#### Label Styles Example
```
Point Label Styles/Point Label Style/Text/Text Contents
Point Label Styles/Point Label Style/Line/Leader
Point Label Styles/Point Label Style/Border/Background
```

#### Table Styles Example
```
Surface Table Styles/Surface Table Style/Table Layout/Header
Surface Table Styles/Surface Table Style/Column Properties/Data
Surface Table Styles/Surface Table Style/Data Properties/Formatting
```

### How Component Column Works

The Component column helps you:
- **Locate Objects** - Find exactly which object you're editing in Civil 3D
- **Identify Subcomponents** - Understand the internal structure of objects
- **Navigate Hierarchy** - Follow the parent-child relationships
- **Match Civil 3D Structure** - Directly correlate with Civil 3D's tree structure

> **GIF Placeholder:** Show Component column structure across all three tabs and Show how to use Component column to navigate Civil 3D tree structure
