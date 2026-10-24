---
layout: post
title: "Parametric Workstation & Desk Assembly (WIP)"
description: "Designing a multi-piece modular desk and workstation assembly in SolidWorks, focusing on structural stability, surface mating, and parametric dimensioning."
skills: 
  - SolidWorks & CAD
  - Parametric Modeling
  - Assembly Mates & Clearances
  - Structural Design
  - Technical Documentation

main-image: /desktopkey.png
---
## Design Workflow
1. **Part Design:** Modeling all individual parts based on my **real-life desk**, such as framing brackets and fasteners.
2. **Sub-Assembly:** Grouping structural supports into **sub-assemblies** before final integration.
3. **Verification:** Checking for interference and clearance issues across all movable or connecting joints, and **hand-measured every part** to be identical to its real-life counterpart.
4. **Keyboard Assembly:** Precision-mounted all unique mechanical keys and custom switches onto the keyboard base, replicating standard key matrices to achieve an evenly spaced, fully populated desktop layout.

## Project Gallery

<div class="gallery-grid" style="display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 20px; margin-top: 20px;">

  {% assign folder_path = page.path | split: "/" | slice: 0, 2 | join: "/" %}

  <figure style="text-align: center; margin: 0; background-color: #1e1e1e; border-radius: 8px; padding-bottom: 12px; overflow: hidden;">
    <img src="/{{ folder_path }}/keybase.png" alt="Keyboard Base View" style="width: 100%; height: 280px; object-fit: contain; background-color: #1e1e1e; display: block;">
    <figcaption style="margin-top: 10px; font-size: 14px; color: #f0f0f0; padding: 0 10px;">
      Keyboard base structure with extruded connectors, adequate length and width for 5 rows of keys of various sizes
    </figcaption>
  </figure>

  <figure style="text-align: center; margin: 0; background-color: #1e1e1e; border-radius: 8px; padding-bottom: 12px; overflow: hidden;">
    <img src="/{{ folder_path }}/connect.png" alt="Connector Design" style="width: 100%; height: 280px; object-fit: contain; background-color: #1e1e1e; display: block;">
    <figcaption style="margin-top: 10px; font-size: 14px; color: #f0f0f0; padding: 0 10px;">
      Keycap to Keybase connector view
    </figcaption>
  </figure>

</div>
