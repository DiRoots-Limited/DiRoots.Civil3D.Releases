---
layout: default
title: Profile
parent: Template Inspector User Guide
nav_order: 5
---

# Profiles
{: .no_toc }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

# Profiles

Template Inspector profiles store complete inspection and object management configurations, including object type preferences, search and filter settings, and batch operation preferences. The profile system enables efficient management and reuse of inspection settings across projects and teams.

## What's Saved in Profiles

The following settings are saved in Template Inspector profiles:

- **Object Type Preferences** - Preferred object types for inspection (layers, line types, hatch styles, etc.)
- **Search and Filter Settings** - Search criteria and filter configurations
- **Display Preferences** - Display settings for usage status and results
- **Batch Operation Settings** - Batch action preferences and default behaviors
- **Isolation Settings** - Object isolation preferences and configurations
- **Layer Management Settings** - Layer swapping and modification preferences
- **Component Configuration** - Component inspection and modification settings

## Creating Profiles

Template Inspector profiles let you save your inspection and object management settings for reuse and sharing across projects and teams.

### Steps to Create a Profile

1. **Configure Your Settings**
   - Set up object type preferences
   - Configure search and filter settings
   - Set up display preferences
   - Configure batch operation settings

2. **Save as Profile**
   - In the window header, click the save button next to the profiles list
   - Name the profile (choose a meaningful name for easy identification)
   - Choose the location to save it
   - Click "Save" to store the profile

3. **Profile Organization**
   - Use descriptive names for easy identification
   - Organize profiles by project type or inspection purpose
   - Consider versioning for different scenarios

![Template Inspector Creating profiles](../../../assets/images/TemplateInspector/TI-SaveProfile.gif)
<sub>Note: the version on the image may not reflect the latest version of Template Inspector.</sub>

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

![Template Inspector importing profiles](../../../assets/images/TemplateInspector/TI-ImportProfile.gif)
<sub>Note: the version on the image may not reflect the latest version of Template Inspector.</sub>

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

![Template Inspector delete profiles](../../../assets/images/TemplateInspector/TI-DeleteProfile.png)
<sub>Note: the version on the image may not reflect the latest version of Template Inspector.</sub>

## Advanced Profile Features

### Search and Filter Integration

Profiles can include search and filter configurations:

- **Search Criteria** - Save search settings for quick object location
- **Filter Configurations** - Store filter settings for efficient data management
- **Data Organization** - Maintain data organization preferences
- **Quick Access** - Rapid access to frequently used search/filter combinations

### Object Management Settings

Profiles store comprehensive object management settings:

- **Object Type Preferences** - Preferred object types for inspection
- **Selection Preferences** - Multi-selection and isolation preferences
- **Batch Operation Settings** - Batch action configurations and preferences
- **Layer Management** - Layer swapping and modification settings

### Display and Interface Settings

Profiles include display and interface configurations:

- **Display Preferences** - How results are displayed and organized
- **Column Configurations** - Settings and objects column preferences
- **Usage Display** - How usage information is presented
- **Interface Layout** - Interface layout and organization preferences

## Best Practices

### Profile Creation
- **Start with Standards** - Base profiles on established inspection standards
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

### Search and Filter Management
- **Save Useful Searches** - Save frequently used search configurations
- **Filter Organization** - Organize filter settings for efficiency
- **Quick Access** - Create profiles with quick access to common searches
- **Data Navigation** - Optimize data navigation with saved configurations 
