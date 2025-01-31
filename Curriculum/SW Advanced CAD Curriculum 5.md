# Lesson 5: More 3D Modeling Tools

## Setup (~1 minute):
- Open a new SW project.
- Save inside the “My Projects Folder”.

## Introduction (~5 minutes):
- What part was made last week and how was it made?
- What does extrude do? 
- What does cut extrude do? 
- What does revolve do?

## Sweep Tool:
1. Create a sketch of a centerline on the top plane.
![image](https://github.com/user-attachments/assets/763b84c8-26a7-4c92-a545-0464725008b8)
2. Exit the sketch and click "Sweep" and select the circular cross-section option.
3. **Loft** creates a 3D shape by sweeping a 2D profile along a predefined path.
   - Example uses include pipes, wires, handlebars.
   - Useful for creating objects with complex curves or varying cross-sections.
4. **Circular Cross-section** is simply a shortcut for a circular cross-section.
5. Sketch on the front plane a random cross-section (ellipse, circle, square).
6. Select **Sketch Profile** and select your sketch.

## Loft Tool:
1. Create a new file.
2. Create a circular profile on the top plane.
3. Create a sketch plane offset from the top plane.
4. Create a larger circular profile on the new plane.
5. Repeat these steps but instead of a larger circular profile, use **Convert Entities** to clone the bottom profile.
6. Move the green arrow around and see how the loft extrusion changes as a result.
7. **Loft tool** extrudes material between two cross-sectional surfaces that can be guided using guide curves.

## Thin Option/Shell Tool:
1. Click the top and bottom of the vase.
2. Click **Shell** and select the shell thickness.
3. **Shell** hollows out an extrusion leaving open the faces that are selected.
4. Select **Section View** to see the cross-section of the vase.
