# Documentation notes for DiRoots.Civil3D.Releases

Found while testing documentation PR previews on a replica of this repository (`DiRoots-Mauro/DiRoots.Sandbox.Civil3D.Releases`) and on the production site. None of these items is caused by the preview workflows; they are listed so they can be fixed separately.

## Broken images in production (6)

These references return 404 on the live site:
- `docs/pages/DrawingLayers/DL-Spreadsheet-Interface.md:71`: `../../../assets/images/GIFs/DL/DL-Add-LayerS.gif` - the file is named `assets/images/GIFs/DL/DL-Add-Layers.gif` (letter case differs); fix the link.
- `docs/pages/EarthworkTool/EW-Layer-Consideration.md:45`: `../../../assets/images/GIFs/ET/Overview-of-layer-consideration-capabilities.gif` - the file is missing from `assets/images/GIFs/ET/`; add the GIF or remove the reference.
- `docs/pages/StyleHelper/SH-Editing-Features.md:51`: `../../../assets/images/GIFs/SH/Table-customization-and-profile-management.gif` - the file is missing; the closest file in `assets/images/GIFs/SH/` is `Table Customization-.gif` (check it is the intended image), otherwise add the GIF.
- `docs/pages/TemplateInspector/TI-Batch-Actions.md:66`: `../../../assets/images/GIFs/TI/Deletion-requirements-and-verification-process.gif` - the file is missing from `assets/images/GIFs/TI/`; add the GIF or remove the reference.
- `docs/pages/TemplateInspector/TI-Object-Inspection.md:49`: `../../../assets/images/GIFs/TI/Main-interface-and-basic-navigation.gif` - the file is missing from `assets/images/GIFs/TI/`; add the GIF or remove the reference.
- `docs/pages/TransferObjectLayers/TOL-Transfer-Object-Layers.md:65`: `../../../assets/images/GIFs/TOL/Excel-file-selection-and-import-process.gif` - the file is missing from `assets/images/GIFs/TOL/`; add the GIF or remove the reference.

## Site size

The `gh-pages` branch holds about 1008 MiB of files, almost all images and GIFs. GitHub Pages recommends repositories and published sites below 1 GB.
- Previews are not affected: they reuse the live images, so a preview of this site measured 57.1 MiB instead of 1010 MiB.
- The site is close to the 1 GB published-site limit. The publisher in this repository passes `max-source-mib: 1100` because the Pages source is already above the default 800 MiB budget.
- Suggested fix: compress the largest GIFs or convert them to MP4/WebM. Largest files: `assets/images/GIFs/GP/Object-Feature-Line-Integration.gif` (45.0 MiB), `assets/images/GIFs/DL/Spreadsheet-Interface-Features-Formula-Support.gif` (38.1 MiB), `assets/images/GIFs/DL/Formula-Support.gif` (38.0 MiB), `assets/images/GIFs/TOL/Complete-export-process.gif` (34.5 MiB), `assets/images/GIFs/DL/Complete-Import-Export-Workflow.gif` (29.5 MiB).
