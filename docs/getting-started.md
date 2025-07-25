---
layout: default
title: Getting Started
nav_order: 2
---

# Getting Started
{: .no_toc }

DiCivil has several Autodesk Civil 3D Productivity Tools for Data Management, Filtering, Model Checking, Drawing Production, Point Clouds, etc. Includes Piping Engineer, FamilyReviser, OneFilter, TableGen, SheetGen, ReOrdering, ParaManager, PointKit, QuickViews, and OneParameter.
Not permitted:
-	Sell/resell
-	make modifications to the software.
{: .fs-6 .fw-300 }

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Download

Download the [latest version of DiCivil](https://diroots.com/civil3d-plugins/dicivil/).


## Install

### Compatibility
- Windows 7, 8, 10 and 11.
- Civil 3D 2018, 2019, 2020, 2021, 2022, 2023, 2024, 2025, and 2026.

### Standard Installation

```yaml
This method is ideal for individuals who want to install DiCivil in one computer.
```

1. Run DiCivil installer.

2. Select the Civil 3D versions and click 'Install'.

![DiCivil Installation First Step](..\assets\images\One-Installer.gif)

3. Wait for the installation to complete and click 'Finish'.

![DiCivil Installation Finish](..\assets\images\One-Installer-Finished.png)

### Silent Installation

```yaml
This method is ideal for IT administrators who want to deploy DiCivil to multiple computers.
```

- Install for all compatible Civil 3D versions.

```yaml
# This method will silently install DiCivil for all compatible Civil 3D versions.
<installer-name>.exe /i // /qn accept_eula=1
```

- Disable automatic check for update (i.e., users won't be prompt to install updates).

```yaml
# In this example DiCivil will NOT be installed for Civil 3D 2017, 2018, and 2019.
<installer-name>.exe /i // /qn accept_eula=1 UPDATER="FALSE"
```

- Exclude specific Civil 3D versions.

```yaml
# In this example DiCivil will NOT be installed for Civil 3D 2017, 2018, and 2019.
<installer-name>.exe /i // /qn accept_eula=1 civil3d2017="" civil3d2018="" civil3d2019=""
```

## Uninstall

### Using the installer User Interface

1. Run DiCivil installer.

2. Select and click 'Remove'.

![DiCivil Uninstall](..\assets\images\One-Installer-Finished.png)

3 . Wait for the uninstallation to complete and click 'Finish'.

### Using the installer silently

Uninstall DiCivil without user interaction.

```yaml
# This method will remove DiCivil from your computer.
<installer-name>.exe /x // /qn
```

### From the control panel

1. In the search box on the taskbar, type Control Panel and select it from the results.

2. Select Programs > Programs and Features.

3. Press and hold (or right-click) on the program you want to remove and select Uninstall or Uninstall/Change. Then follow the directions on the screen.

## Updates

DiCivil includes an updater to help you keep it up to date. 
The updater will:
- notify you whenever a new version is released (the action is triggered on Civil 3D close event).
- ask you to install now or to remind you tomorrow.

![DiCivil Updater UI](../assets\images\DiCivil-Updates.png)

### Updater Settings

The following Update Options can be tweaked:
- activate automatic updates.
- check for updates frequency (the default value is 2 days). 
- change the downloads folder.

```yaml
# Pro Tip for Users
By default the automatic updates can't be disabled.
To go around it, you can set up the check for updates frequency to 365 days, for example.
# Keep in mind that it' recommended to keep your apps updated. Plus, we do not provide support for outdated applications.
```

```yaml
# Pro Tip for IT Administrators
By default the automatic updates can't be disabled.
To go around it, there's a configuration file that can be tweaked.

# Steps required
- go to %programdata%\DiRoots.DiCivil\Settings
- open the 'updater.ini' file
- Search for the line 'CheckFrequency=2' and change the value to 365, for example.

# Keep in mind that it' recommended to keep your apps updated. Plus, we do not provide support for outdated applications.
```

<button class="btn js-toggle-dark-mode">Preview dark color scheme</button>
