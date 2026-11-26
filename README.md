EX-No.3 – 3D Modelling and Cut Section of Arched Pedestal Bracket

AIM

To design the 3D solid model of the Arched Pedestal Bracket in Autodesk Fusion and generate its cut section and orthographic views.

REQUIREMENTS

1. Autodesk Fusion 360
2. Windows 10 / Windows 11 (64-bit)
3. 4 GB of RAM (6 GB or more recommended)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload

COMMANDS USED

1. Create Sketch:

Draws the symmetric side profile of the 166 mm arched pedestal including the 12 mm base flanges, 2 mm × 25 mm bottom undercuts, and 43 mm inner arch clearance.

2. Extrude:

Extrudes the base flanges symmetrically to 71 mm width, the arched bridge to 61 mm width, and the top cylindrical boss (Ø50 mm) upward by 25 mm.

3. Fillet:

Applies R15 mm outer arch fillets, R6 mm inner arch fillets, and R10 mm base transition fillets along the arch legs.

4. Hole:

Cuts the central Ø25 mm through-bore through the top boss and arch, plus four Ø12 mm mounting holes on the base flanges.

5. Section Analysis & Section View:

Uses Inspect > Section Analysis in the Design workspace to visualize the cut solid, and Drawing > Views > Section View (A–A) in the Drawing workspace to produce the hatched 2D cut section.

PROCEDURE

STEP 1: Identifying the Given Model

Inspect all dimensions of the Arched Pedestal Bracket (length 166 mm, base width 71 mm, arch width 61 mm, total height 78 mm) and set Autodesk Fusion units to millimeters (mm).

STEP 2: Modelling the Stepped Base Flanges

On the XZ plane, sketch the left and right 45 mm base flanges (12 mm thick, each with a 2 mm deep × 25 mm wide bottom undercut between 10 mm pads) spanning 166 mm overall, and extrude symmetrically to 71 mm.

STEP 3: Creating the Arched Bridge Body

On the XZ plane, sketch the 10 mm thick arch profile rising to 43 mm inner height (53 mm outer height) across the 96 mm outer arch span, and extrude symmetrically to 61 mm (Join).

STEP 4: Applying Fillets

Use Modify > Fillet to apply R15 mm fillets to the upper outer arch corners, R6 mm fillets to the upper inner arch corners, and R10 mm fillets where the arch meets the base flanges.

STEP 5: Adding the Top Boss and Mounting Holes

Sketch a Ø50 mm circle centered on the arch top and extrude upward by 25 mm. Cut a concentric Ø25 mm through-hole, and drill four Ø12 mm mounting holes on the flanges.

STEP 6: Creating the Cut Section and 2D Drawing

Use Inspect > Section Analysis along the central XZ plane to view the cut solid. Select Design > Drawing > From Design (ISO, A3, mm), place the Top View, create Section View A–A across the centerline, project the Side and 3D cut-section views, add dimensions, and fill the Title Block.

INPUT
<img width="697" height="585" alt="image" src="https://github.com/user-attachments/assets/4ef8e345-cb52-4fbe-8136-8a79a17dd1bc" />

"Arched Pedestal Input Sketch" (arched-pedestal-input-sketch.png)

CUT SECTION 3D VIEW
<img width="1481" height="911" alt="image" src="https://github.com/user-attachments/assets/cf6f1d44-6981-4a81-934e-5f977995611c" />

"Arched Pedestal Cut Section 3D View" (arched-pedestal-cut-section-3d-view.png)

OUTPUT
<img width="1292" height="917" alt="image" src="https://github.com/user-attachments/assets/d88fe39b-e198-49af-84de-89a15d7a5dd2" />

"Arched Pedestal Sectional Orthographic Drawing" (arched-pedestal-sectional-orthographic-drawing.png)

RESULT

Thus, the 3D solid model and cut section of the Arched Pedestal Bracket have been designed in Autodesk Fusion and converted into sectional orthographic views.

CREATED BY: BUTHATI BALASUBRAHMANYAM
