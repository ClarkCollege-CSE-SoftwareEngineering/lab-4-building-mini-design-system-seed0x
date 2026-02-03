# Lab 4: Building a Mini Design System

**Name:** Vladislav Kolesnik  
**Date:** Feb 2, 2026
---
## Reflection 
Building the alert molecule from atoms such as icon, text, and button shows why foster wrote what he wrote about atomic design. The real value is once those pieces are built, I do not have to keep rebuilding the molecule every time I need an alert, allowing me to reuse and keep my Alert consistent throughout the UI. The nice part is if I decide the icon size is off or the button padding feels weird, I fix it once and every Alert in the app gets the update.
Design tokens play the role of default settings/config for the UI. For example, the main colors/branding, spacing, and font sizes. This becomes critical when following a theme or design or if you value maintainability and value your time a little. Using design tokens keeps everything matching and consistent since every component pulls from the same config. 
Additionally, Dark mode is a good example for design tokens and answering the third reflection question. To add dark mode, I would add design token color values and make text white/ligther for when dark mode is needed. The components would keep using the same token names, but with new values.
---
## Key Concepts
Component Heiarchy: Atoms, molecules, organisms
Building molecules from atoms
Design tokens and their value 
Reusing parts so you don’t rewrite code
