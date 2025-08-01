---
layout: default
title: Profile
parent: Transfer Object Layers User Guide
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

Transfer Object Layers profiles store complete transfer configurations and settings, enabling you to save and reuse transfer setups for different workflows and projects. The profile system allows you to create, save, and switch between different transfer configurations efficiently.

## What's Saved in Profiles

The following settings are saved in Transfer Object Layers profiles:

- **Transfer Configurations** - Complete transfer source and destination settings
- **Import Preferences** - Import options and file selection preferences
- **Data Editing Settings** - Data modification and editing preferences
- **Batch Transfer Settings** - Batch operation configurations and preferences
- **Excel Export/Import Settings** - Excel template and format preferences
- **Layer Validation Settings** - Layer validation and warning preferences
- **UI Display Settings** - Interface display and organization preferences
- **Workflow Configurations** - Workflow-specific settings and preferences

## Creating Profiles

Transfer Object Layers profiles let you save your transfer settings, import configurations, and workflow preferences for reuse and sharing across projects and teams.

### Steps to Create a Profile

1. **Configure Your Settings**
   - Set up transfer source and destination preferences
   - Configure import options and file selection
   - Set up data editing preferences
   - Configure batch transfer settings

2. **Save as Profile**
   - In the window header, click the save button next to the profiles list
   - Name the profile (choose a meaningful name for easy identification)
   - Choose the location to save it
   - Click "Save" to store the profile

3. **Profile Organization**
   - Use descriptive names for easy identification
   - Organize profiles by workflow or project type
   - Consider versioning for different scenarios

![Transfer Object Layers Creating profiles](../../../assets/images/TransferObjectLayers/TOL-SaveProfile.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Object Layers.</sub>

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

![Transfer Object Layers importing profiles](../../../assets/images/TransferObjectLayers/TOL-ImportProfile.gif)
<sub>Note: the version on the image may not reflect the latest version of Transfer Object Layers.</sub>

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

![Transfer Object Layers delete profiles](../../../assets/images/TransferObjectLayers/TOL-DeleteProfile.png)
<sub>Note: the version on the image may not reflect the latest version of Transfer Object Layers.</sub>

## Advanced Profile Features

### Transfer Configuration Storage

Profiles store comprehensive transfer configurations:

- **Source Settings** - Source file and import method preferences
- **Destination Settings** - Target file and transfer method preferences
- **Import Options** - Import from open file, closed file, or Excel preferences
- **Data Editing Settings** - Data modification and editing preferences

### Workflow Optimization

Profiles optimized for different workflows:

- **Project-Specific Profiles** - Profiles tailored to specific project types
- **Workflow Profiles** - Profiles optimized for specific workflows
- **User Preferences** - Profiles customized for individual user preferences
- **Team Standards** - Profiles that enforce team standards

### Standard Configuration Management

Manage standard configurations efficiently:

- **Standard Creation** - Create standard configurations for reuse
- **Standard Distribution** - Share standard configurations across teams
- **Standard Application** - Apply standard configurations to projects
- **Standard Maintenance** - Update and maintain standard configurations

## Profile Management

### Profile Switching

Efficient profile switching:

- **Quick Switching** - Switch between profiles quickly
- **Configuration Application** - Apply saved configurations immediately
- **Workflow Adaptation** - Adapt to different workflows with profile switching
- **Consistency Maintenance** - Maintain consistency across different projects

### Profile Organization

Organize profiles efficiently:

- **Descriptive Naming** - Use descriptive names for easy identification
- **Category Organization** - Organize profiles by category or workflow
- **Version Control** - Maintain different versions for different needs
- **Access Control** - Control access to shared profiles

### Profile Sharing

Share profiles across teams:

- **Network Storage** - Store profiles in network locations for sharing
- **Team Access** - Allow team members to access shared profiles
- **Standardization** - Standardize workflows with shared profiles
- **Collaboration** - Enable collaboration through shared configurations

## Best Practices

### Profile Creation
- **Start with Standards** - Base profiles on established workflow standards
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

### Standard Configuration Management
- **Save Useful Configurations** - Save configurations for common workflows
- **Test Configurations** - Test configurations before sharing
- **Document Configurations** - Document what each configuration includes
- **Regular Updates** - Update configurations as workflows evolve 
