## Common Workflow

1. Create islands using a script.
2. Create slopes on cliffs manually by smoothing a selection.
3. Create objects using a script in trial and error mode.

> [!TIP]
> Pan around by dragging the middle mouse button, and zoom in and out by rotating the mouse wheel.

## Order of Commands

It is recommended that you run commands in the following order:

1. Land Commands
2. Object Commands
    1. RSGen
    2. Build/Head
    3. Trees/Wildies

> [!CAUTION]
> Land commands after object commands may cause invalid placement of the objects.

## How to Use the Trial and Error Option

You can add the elements you envision by random generation

1. In the script window, write and compile a script which adds islands/objects.
2. In the map window, open a map to modify.
3. On the menu, check **Options** > **Trial and Error**.
    - Alternatively, start the script with `trial: on`.
4. Repeat generation until you get the desired result.
5. Uncheck the option.

## How to Create a Slope on a Cliff

1. In the sidebar, select **Command** > **Smooth**.
2. Drag the left mouse button to select the area of the slope.
3. Adjust the selection's location, size, and rotation.
4. Press the **Execute** button.

## How to Place a Marker at a Specific Location

1. In the sidebar, select **Command** > **Marker**.
2. Left-click at the location you want to place the marker.
3. Press the **Execute** button.
