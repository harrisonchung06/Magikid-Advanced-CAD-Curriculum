# Lesson 1: Nameplate 

During this lesson you will create a 3D model of your name with a 1 mm thick base plate in SolidWorks.

## Step 1: Create a New Part
1. Launch SolidWorks and create a new part file.
2. Select `File` > `New` > `Part` > `OK`.

![](images 2/Untitled-1.png "Step 1")

## Step 2: Sketch Your Name on the Front Plane
1. In the FeatureManager, select the `Front Plane`.
2. Click `Sketch` > `Text` from the sketch toolbar.
3. In the text dialog box:
   - Type your name
   - Select your preferred font and size
   - Position the text at the origin
4. Click `OK` to confirm.

[image here: Text tool with name entered]

## Step 3: Extrude Your Name
1. Exit the sketch and select the `Extruded Boss/Base` feature.
2. Set the extrusion depth to your desired height (e.g., 5 mm).
3. Click `OK` to create the 3D text.

[image here: Extrusion dialog with parameters]

## Step 4: Create the Base Plate
1. Select the bottom face of your extruded name.
2. Click `Sketch` > `Convert Entities` to project the outline.
3. Use the `Offset Entities` tool to create an offset around your name (e.g., 5 mm).
4. Exit the sketch and use `Extruded Boss/Base`:
   - Set direction to `Up To Surface` and select the bottom face
   - Set thickness to 1 mm
   - Check `Merge result` option

[image here: Base plate creation process]

## Step 5: Final Touches
1. Apply appearances if desired:
   - Right-click the name → `Appearance` → Choose material
   - Right-click the plate → `Appearance` → Choose material
2. Save your file.

[image here: Final rendered model]

## Tips:
- Use simple fonts for easier extrusion
- Consider adding fillets to sharp edges for a smoother look
- For complex names, you may need to use the `Intersect` tool

[image here: Example of completed model]
