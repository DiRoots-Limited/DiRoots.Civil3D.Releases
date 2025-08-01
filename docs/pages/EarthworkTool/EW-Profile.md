---
layout: default
title: Profile
parent: Earthwork Tool User Guide
nav_order: 6
---

# Profiles
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Profiles

Earthwork Tool profiles store complete calculation configurations including surface selections, region definitions, stripping parameters, and volume unit preferences. The profile system enables efficient management and reuse of calculation settings across projects.

## What's Saved in Profiles

The following settings are saved in Earthwork Tool profiles:

- **Surface Selections** - Existing and proposed surface configurations
- **Region Definitions** - Defined calculation regions and boundaries
- **Stripping Parameters** - Topsoil stripping thickness and configurations
- **Volume Unit Preferences** - m³, yd³, ft³, acre-ft settings
- **Calculation Parameters** - All calculation settings and configurations
- **Object Associations** - Associated elements and their relationships

## Creating Profiles

Earthwork Tool profiles let you save your calculation settings and reuse them later. This is ideal for standardizing workflows and sharing settings across teams.

### Steps to Create a Profile

1. **Configure Your Settings**
   - Set up surfaces, regions, and stripping parameters
   - Configure volume units and calculation preferences
   - Test the configuration to ensure it works correctly

2. **Save as Profile**
   - In the window header, click the save button next to the profiles list
   - Name the profile (choose a meaningful name for easy identification)
   - Choose the location to save it
   - Click "Save" to store the profile

3. **Profile Organization**
   - Use descriptive names for easy identification
   - Organize profiles by project type or standard
   - Consider versioning for different scenarios

![Earthwork Tool Creating profiles](../../../assets/images/EarthworkTool/EW-SaveProfile.gif)
<sub>Note: the version on the image may not reflect the latest version of Earthwork Tool.</sub>

```yaml
Tip for BIM Managers!
Create profiles in a network location to allow other users to import them.
See the "Importing Profiles" section for details.
```

## Importing Profiles

Import existing profiles to stay compliant with company standards and maintain consistency across projects.

### Steps to Import Profiles

1. **Access Import Function**
   - Click the Import button next to the profiles list
   - Navigate to the profile file location

2. **Select Profile**
   - Use File Explorer to find the profile (shared folder, network, or local)
   - Browse to the desired profile file
   - Click "Open" to import the profile

3. **Apply Profile**
   - The imported profile will be available in your profile list
   - Select the profile to apply its settings to your current project
   - Modify settings as needed for the current project requirements

![Earthwork Tool importing profiles](../../../assets/images/EarthworkTool/EW-ImportProfile.gif)
<sub>Note: the version on the image may not reflect the latest version of Earthwork Tool.</sub>

## Deleting Profiles

Remove unwanted or outdated profiles from your profile library.

### Steps to Delete Profiles

1. **Select Profile**
   - Select the profile from the profile dropdown list
   - Ensure you're selecting the correct profile to delete

2. **Delete Profile**
   - Click the Delete icon next to the profiles list
   - Confirm deletion when prompted
   - The profile will be permanently removed

![Earthwork Tool delete profiles](../../../assets/images/EarthworkTool/EW-DeleteProfile.png)
<sub>Note: the version on the image may not reflect the latest version of Earthwork Tool.</sub>

## Advanced Profile Features

### Object Association Management

Manage and isolate associated calculation elements:

#### Select Objects
- **Choose Associated Elements** - Select objects related to calculations
- **Element Identification** - Identify which elements are associated with profiles
- **Relationship Management** - Manage relationships between elements and calculations
- **Context Awareness** - Understand how elements relate to calculation results

#### Isolate Elements
- **Focus on Components** - Isolate specific elements for detailed analysis
- **Element Filtering** - Filter elements to focus on specific components
- **Detailed Review** - Review isolated elements in detail
- **Quality Control** - Verify element associations are correct

#### Remove Items
- **Delete Unwanted Elements** - Remove elements from calculations
- **Clean Up Associations** - Remove incorrect or outdated associations
- **Update Calculations** - Calculations update when elements are removed
- **Maintain Integrity** - Ensure calculation integrity after removals

### Real-time Updates

All calculations and associations update automatically:

- **Dynamic Updates** - Changes reflect immediately in calculations
- **Automatic Recalculation** - Totals update when elements are modified
- **Hierarchical Updates** - Parent and grand totals update simultaneously
- **Validation** - Verify calculations remain accurate after changes

## Best Practices

### Profile Creation
- **Start with Standards** - Base profiles on established calculation standards
- **Test Thoroughly** - Verify profiles work across different scenarios
- **Document Purpose** - Clearly document what each profile is for
- **Version Control** - Maintain different versions for different needs

### Profile Management
- **Organize Systematically** - Use consistent naming and organization
- **Regular Reviews** - Periodically review and update profiles
- **User Training** - Train team members on profile usage
- **Feedback Loop** - Collect feedback to improve profiles

### Profile Sharing
- **Centralized Storage** - Store profiles in a central, accessible location
- **Access Control** - Control who can modify shared profiles
- **Change Management** - Establish processes for profile updates
- **Communication** - Notify team members of profile changes

### Object Association
- **Verify Associations** - Ensure correct elements are associated
- **Regular Cleanup** - Remove outdated or incorrect associations
- **Documentation** - Document element associations for future reference
- **Quality Assurance** - Verify associations meet project requirements 
