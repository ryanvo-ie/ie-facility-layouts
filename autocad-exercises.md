# AutoCAD Technical Competency Exercises

This section of the repository archives foundational engineering graphics work completed as target preparation for facilities and industrial engineering methodologies utilized at **The Boeing Company**. 

These technical drills directly track the structured curriculum from the [CAD in Black Beginner Tutorial](https://www.youtube.com/watch?v=MUgZDUdv60A), focusing on geometric precision, rapid workflow modification, and blueprint accuracy.

## Core Technical Skills Practiced
* **Coordinate Drafting**: Utilizing polar (`@length<angle`) and relative coordinates for absolute positional accuracy.
* **Geometric Modification**: Implementing `OFFSET`, `MIRROR`, `TRIM`, and solid `HATCH` boundaries to optimize drafting efficiency.
* **Dimensioning Standards**: Applying standardized `DIMLINEAR`, `DIMALIGNED`, and `DIMANGULAR` constraints across architectural and decimal scales.

### Exercise 1: Basic T-Shape Profile

* **Objective**: Learn the basics of drawing shapes with exact dimensions.
* **Commands Used**: `POLYLINE` (`PLINE`) and `Ortho Mode` (`F8`).
* **What I Learned**: 
  * How to lock lines to a perfectly straight 90-degree angle using Ortho Mode.
  * How to follow blueprint dimensions to trace a continuous path.
  * How to use the 'Close' command to complete the shape cleanly at the starting point.

![AutoCAD Exercise #1](autocad-exercise-1.png)

### Exercise 2: Multi-Shape Profile Layout

* **Objective**: Practice drawing more complex combinations of shapes and managing internal layout spaces.
* **Commands Used**: `LINE`, `RECTANGLE` (`REC`), and `Ortho Mode` (`F8`).
* **What I Learned**:
  * How to transition from a basic single-line shape to drawing multiple standalone objects in one workspace.
  * How to use tracking vectors to leave exact spacing gaps (like the 20' paths) between separate shapes.
  * How to efficiently use the standard Rectangle command alongside precise manual coordinates to build vertical columns.

![AutoCAD Exercise 2 Layout](autocad-exercise-2.png)

### Exercise 3: Angular Profile & Roof Layout

* **Objective**: Learn how to draw precise diagonal lines using lengths and specific degree constraints.
* **Commands Used**: `POLYLINE` (`PLINE`), `DIMALIGNED`, and `DIMANGULAR`.
* **What I Learned**:
  * How to input precise relative polar coordinates using the `@length<angle` format to construct symmetrical sloped geometry.
  * How to toggle Ortho Mode off to successfully draft complex angular paths without losing precision.
  * How to apply Aligned Dimensions (`DIMALIGNED`) for accurate true-length slanted measurements and Angular Dimensions (`DIMANGULAR`) to display roof pitch degrees.

![AutoCAD Exercise 3 Layout](autocad-exercise-3.png)

### Exercise 4: Advanced Multi-Feature Layout

* **Objective**: Manage complex internal geometry with precise dimensional alignment across a large ($100'$) base footprint.
* **Commands Used**: `LINE`, `OFFSET`, and `DIMLINEAR`.
* **What I Learned**:
  * How to coordinate multiple vertical profiles while maintaining a unified, solid base floor plan.
  * **Troubleshooting & Precision Control**: Encountered a minor fractional precision variance (`9'-11.6400"` instead of a clean `10'`), highlighting the critical importance of exact object snapping (`OSNAP`) and unit tolerance verification in complex blueprints.

![AutoCAD Exercise 4 Layout](autocad-exercise-4.png)

### Exercise 5: Complex Symmetrical Truss Layout

* **Objective**: Practice using duplication tools to build a complex, symmetrical structural frame.
* **Commands Used**: `LINE`, `COPY`, `MIRROR`, and `DIMALIGNED`.
* **What I Learned**:
  * How to use the **COPY** and **MIRROR** tools to instantly replicate the smaller inner triangles instead of drawing them from scratch.
  * **Precision Analysis**: Noticed a minor fractional variance (`19'-10.5025"` instead of a clean `20'`), which helps practice identifying where object snaps can catch tiny angle offsets over long distances.

![AutoCAD Exercise 5 Layout](autocad-exercise-5.png)

### Exercise 6: Curvilinear Intersecting Profile

* **Objective**: Master arc/circle generation and practice cleaning up overlapping curved boundaries.
* **Commands Used**: `CIRCLE`, `TRIM` (`TR`), and `DIMRADIUS` (`DRA`).
* **What I Learned**:
  * How to create precise concentric and intersecting circular geometry using exact radius constraints ($R20$ and $R40$).
  * How to use the **Trim** tool to cut away internal overlapping paths to merge multiple circles into a single fluid outline.
  * **Precision Analysis**: Observed a minor fractional alignment shift on the linear measurements (`19'-11.1307"` and `39'-11.3107"`), highlighting how linear dimension snaps interact with curved quadrant object anchors.

![AutoCAD Exercise 6 Layout](autocad-exercise-6.png)

### Exercise 7: Thick-Walled Angular Enclosure

* **Objective**: Combine precise angular drafting with uniform boundary offsetting across mixed linear and slanted profiles.
* **Commands Used**: `LINE`, `OFFSET`, `DIMLINEAR`, and `DIMALIGNED`.
* **What I Learned**:
  * How to create uniform internal clearance paths (the 5' spacing) using parallel offset tracking.
  * How to combine vertical/horizontal linear dimensions (`DIMLINEAR`) with slanted true-length measurements (`DIMALIGNED`) on the same complex part footprint.
  * How to manage multi-directional tracking vectors where a fixed-degree diagonal wall transitions back into a sharp horizontal plane.

![AutoCAD Exercise 7 Layout](autocad-exercise-7.png)

### Exercise 8: Advanced Symmetrical Enclosure & Angled Profile
* **Objective**: Combine advanced geometric modification with precise angular drafting to build a complex, completely symmetrical layout.
* **Commands Used**: `LINE`, `MIRROR`, `TRIM`, `DIMRADIUS`, `DIMANGULAR`, and `DIMALIGNED`.
* **What I Learned**:
  * How to construct only the left half of a highly detailed, complex layout and instantly mirror a perfect copy to complete the right side.
  * How to accurately measure and display oblique surfaces using Aligned Dimensions (`DIMALIGNED`) alongside Angular Dimensions (`DIMANGULAR`) to show exact pitch slopes (like the $60^\circ$ indicator).
  * **Precision Verification**: Noticed a minor trailing precision variance at the very top line (`23'-0.0300"` instead of a flat `23'`), practicing how to audit and identify microscopic offset variances in large multi-segment paths.

![AutoCAD Exercise 8 Layout](autocad-exercise-8.png)
