# Lesson 2: From CAD Model to FDM Print

## Learning goals

By the end of this lesson, you will be able to:

- Describe the workflow that transforms an engineering idea into an FDM-printed object.
- Explain the difference between a CAD model, an STL or 3MF file, slicer software, and G-code.
- Identify the major systems and components of an FDM printer.
- Explain why first-layer inspection is essential.
- Identify likely print problems from a slicer preview or printer condition.
- Follow lab safety expectations near operating printers.

## Vocabulary

Copy these terms and definitions into your engineering notebook.

| Term | Definition |
|---|---|
| CAD | Computer-Aided Design; digital design software used to create parts |
| STL | A common file type that describes the outside geometry of a 3D model |
| 3MF | A modern 3D-manufacturing file type that can include more manufacturing information than an STL |
| Slicer | Software that converts a 3D model into layers and printer movements |
| G-code | Machine instructions that tell a printer where and how to move |
| Toolpath | The path the printer nozzle will follow |
| Extruder | The mechanism that grips and pushes filament toward the hot end |
| Hot end | The heated assembly that melts filament |
| Nozzle | The opening through which melted filament is deposited |
| Build plate | The surface on which the print is built |
| Bed adhesion | The ability of the first layer to stay attached to the build plate |
| Layer height | The thickness of each printed layer |
| Infill | Internal material placed inside a printed object |
| Support | Temporary material printed under overhangs |
| Brim | A thin, wide outline attached to the first layer to improve adhesion |
| Print orientation | The way a model is positioned on the build plate |

## Safety expectations

Copy these safety expectations into your engineering notebook.

- Do not touch the nozzle, hot end, heated build plate, or freshly printed object unless you are told it has cooled.
- Keep hands, hair, clothing, jewelry, and tools away from moving printer components.
- Do not reach into a printer while it is moving.
- Do not remove a build plate or another group’s print.
- Do not change another group’s file, material, printer profile, or settings.
- Report unusual sounds, odors, smoke, filament tangles, grinding, layer shifts, or extrusion problems immediately.
- Use only approved materials and slicer profiles.
- Observe the first layer before leaving a print unattended.
- Keep food and drinks away from printers, filament, and build surfaces.

## Engineering notebook

Create a new page titled:

```text
Lesson 2: From CAD Model to FDM Print
```

Write your name, date, and class period below the title.

### Part 1: Sequence the workflow

Copy the following items into your engineering notebook. Number them in the correct order.

- Printed object
- G-code
- CAD model in Onshape
- Slicer preview
- STL or 3MF file
- Engineering problem or need
- Printer setup
- Testing and revision

Check your work using the workflow below.

```text
Engineering Problem or Need
        ↓
CAD Model in Onshape
        ↓
STL or 3MF Export
        ↓
Slicer Setup and Preview
        ↓
G-code / Toolpaths
        ↓
Printer Setup
        ↓
Printed Object
        ↓
Testing and Revision
```

Answer these questions in complete sentences:

1. At what point does the printer receive instructions?
2. Why does a printer need G-code instead of only an Onshape model?
3. Why is testing and revision part of the manufacturing workflow?

### Part 2: Explain the digital-to-physical workflow

Copy and complete the table below in your engineering notebook.

| Stage | What happens | Common problem to avoid |
|---|---|---|
| Define the problem | Identify user needs, criteria, and constraints | Printing an object without a useful purpose |
| Model the part | Create a dimensioned CAD model in Onshape | Designing features that are too thin or unsupported |
| Export the model | Export STL or 3MF | Exporting the wrong version or wrong part |
| Slice the model | Set orientation and print parameters | Assuming default settings are always correct |
| Inspect preview | Review layers, supports, and toolpaths | Sending a file without checking it |
| Prepare the printer | Load correct material and check printer condition | Using tangled, wet, or incorrect filament |
| Inspect first layer | Confirm adhesion and extrusion | Walking away immediately after starting |
| Print and test | Evaluate function and quality | Treating the first print as final |

Copy the analogy table below.

| Manufacturing step | Analogy |
|---|---|
| CAD model | The engineering drawing or digital blueprint |
| STL or 3MF file | The shape data prepared for manufacturing |
| Slicer | The production planner and translator |
| G-code | The machine’s step-by-step instruction list |
| Printer | The machine carrying out the plan |

Below the tables, explain the difference between:

1. A CAD model and an STL or 3MF file
2. An STL or 3MF file and G-code
3. A slicer and the FDM printer

### Part 3: Identify printer systems

Work with your printer team to locate the printer components below.

Copy and complete this chart in your engineering notebook.

| Printer component | Function | What could happen if it fails or is set up incorrectly? |
|---|---|---|
| Filament spool | Supplies printing material | Tangles can stop or interrupt the print |
| Extruder | Pushes filament toward the hot end | Under-extrusion, slipping, or filament grinding |
| Hot end | Melts filament | Incorrect temperature or clogging |
| Nozzle | Deposits melted filament | Clogs, poor detail, inconsistent extrusion |
| Build plate | Supports the first layer and print | Warping, detachment, poor adhesion |
| Cooling fan | Controls cooling of deposited plastic | Drooping overhangs or poor bridges |
| X-axis | Moves the printhead side to side | Positional errors or layer shifts |
| Y-axis | Moves the printhead or bed front to back | Positional errors or layer shifts |
| Z-axis | Moves the printhead or bed vertically | Incorrect layer height or banding |
| Belts or lead screws | Transfer motor movement to axes | Skipped movement, layer shifts, inaccurate dimensions |
| Display or control interface | Allows users to control and monitor the printer | Incorrect job selection or inability to stop a problem |
| Filament sensor, if present | Detects filament runout | Print may continue without material if sensor fails |

Add a simple labeled sketch of the printer. Use arrows and labels to identify at least six components.

Answer these questions below your sketch:

1. Trace the path of filament from the spool to the printed part.
2. What must happen before melted plastic can stick to the build plate?
3. What would you expect to see if the nozzle were clogged?
4. How might a loose belt appear in a finished print?
5. Why might a print fail even if the CAD model itself is correct?

### Part 4: Analyze the print plan

As you examine a slicer preview, record the settings below.

| Slicer setting | Setting shown | Why it matters |
|---|---|---|
| Printer selection |  |  |
| Material selection |  |  |
| Nozzle diameter |  |  |
| Layer height |  |  |
| Print orientation |  |  |
| Wall or perimeter count |  |  |
| Infill percentage and pattern |  |  |
| Supports |  |  |
| Brim or raft |  |  |
| Nozzle temperature |  |  |
| Build-plate temperature |  |  |
| Print speed |  |  |
| Estimated print time |  |  |
| Estimated filament mass |  |  |

Answer this question in complete sentences:

> If a part is rotated on the build plate, what might change?

Include at least four of the following ideas in your response:

- Layer direction and part strength
- Amount of support required
- Surface quality
- Print duration
- Likelihood of warping or poor adhesion
- Accuracy of holes, flat surfaces, and mating features

### Part 5: Calculate material cost

A slicer estimates that a print will use 18 g of filament. A 1 kg spool costs $24.

Copy and complete the calculation in your engineering notebook.

```text
Cost per gram = $24 ÷ 1,000 g
Cost per gram = ____________________ per gram

Print material cost = 18 g × ____________________ per gram
Print material cost = ____________________

Rounded material cost = ____________________
```

Answer these questions:

1. What is the raw filament cost of this print?
2. Why is raw filament cost not the total cost of a print?
3. Identify at least three additional costs or resources involved in making a print.

### Part 6: Inspect a print plan

Work with your team to analyze the assigned slicer screenshot or printing scenario.

Copy and answer these questions in your engineering notebook.

1. What material is selected?
2. What is the estimated print time?
3. How much filament will the print use?
4. Does the design require supports?
5. Is the orientation reasonable? Explain.
6. What could go wrong?
7. What should the operator inspect before starting?

Use the scenarios below as reference examples.

#### Scenario A: Tall and narrow

A tall, narrow object is printed upright with only a small contact area on the build plate.

Possible concerns:

- Poor bed adhesion
- Tipping or detachment
- Warping
- Excessive height and long print time
- Need for a brim, wider base, or different orientation

#### Scenario B: Unsupported overhang

A part has a large horizontal overhang, but supports are turned off.

Possible concerns:

- Sagging or drooping
- Poor surface finish
- Failed layers
- Need for supports, a chamfer, a redesign, or a different orientation

#### Scenario C: Material-profile mismatch

A PETG spool is loaded, but the slicer is set to a PLA profile.

Possible concerns:

- Incorrect nozzle temperature
- Incorrect bed temperature
- Poor layer adhesion
- Excessive stringing
- Inconsistent extrusion
- Incorrect cooling behavior

### Part 7: Safety check

Copy the table below into your engineering notebook. Label each statement **Safe**, **Unsafe**, or **Needs Teacher Approval**.

| Statement | Your response |
|---|---|
| I can touch the nozzle briefly if I am careful. |  |
| I should observe the first layer before leaving a print. |  |
| I can modify another group’s printer settings if I notice a problem. |  |
| I should report a grinding noise from the extruder. |  |
| I should use only approved filament profiles. |  |
| I can remove a print immediately after it finishes. |  |
| I should check the filament spool for tangles before starting a print. |  |
| I should keep loose clothing and hair away from moving parts. |  |

### Part 8: Reflection

Answer each question in complete sentences.

1. Put these terms in the correct order: slicer, CAD model, G-code, printed part.
2. What is the slicer’s job?
3. Why is the first layer important?
4. Identify one printer component and explain its function.
5. Identify one action that improves safety or print success.

## Before you submit

Make sure your engineering notebook includes:

- Vocabulary terms and definitions
- Workflow sequence and responses
- Completed digital-to-physical workflow table
- Printer-system chart and labeled printer sketch
- Slicer-setting analysis
- Material-cost calculation and responses
- Print-plan analysis
- Safety check
- Reflection responses
