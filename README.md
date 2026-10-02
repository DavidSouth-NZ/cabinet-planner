# Data Cabinet Planner

A browser-based 3D planner for 19" data cabinets. It covers outdoor Dynamix ROD freestanding cabinets and indoor Dynamix D-Series wall cabinets.

## What it does
- Place labelled RU placeholders (1U, 2U, 3U, 4U or custom) and accessories such as cable managers, shelves, PDUs and blanking panels.
- Reserve rack space for the UPS.
- Position access control panels and other fixtures anywhere in X / Y / Z, with required clearances.
- Check for clashes between equipment, fixtures, rails, the UPS space and the cabinet walls.
- Export an A3 drawing (left side, front and right side, with dimensions, legend, schedules and a company logo) as PDF or SVG.
- Save named projects. They are kept in this browser, and project files (.json) can be saved and opened to share or back up layouts.

## Using it
Open `index.html` in any modern browser, or visit the GitHub Pages address for this repository.

An internet connection is needed to load three.js, jsPDF and svg2pdf from public CDNs and the web fonts. Your layouts never leave your browser unless you save a project file.

## Data notes
Cabinet presets are based on Dynamix datasheets (ROD outdoor 03072026/ND and the D-Series swing-frame cabinets). Some internal clearances are estimates and are marked as such in the app and on drawings. Verify them against manufacturer drawings before installing.
