# Three Demo Backend Answers

> **Generated at:** 2026-05-25T23:08:14  
> **Session ID:** `three-demo-backend-check`  
> **API URL:** `http://127.0.0.1:8000/api/chat`

***

## Question 1 — Carb Air Temp Sensor Probe Part Number

**Q:** What is the part number of the carb air temp sensor probe?

**HTTP Status:** `200 OK`

### Answer

I found one relevant IPC entry for the carb air temp sensor probe:

| Field | Value |
|-------|-------|
| **Part Number** | A058-10 |
| **Description** | Carb Air Temp Probe (Includes items 77 and 78) |
| **What it is/does** | Probe used to measure the temperature of the air entering the carburetor, crucial for engine performance and efficiency |
| **Parts Avail Code** | X |
| **Qty per Assy** | 1 |

> Is there a specific assembly or maintenance task you are working on that requires this part?

### Sources

| File | Display Page | PDF Page | Element Type | Score |
|------|-------------|----------|--------------|-------|
| HELICOTER ILLUSTRATED PART CATALOG.pdf | 71.7 | 599 | `ipc_keyword_page` | 2111.0 |
| HELICOTER ILLUSTRATED PART CATALOG.pdf | 71.4 | 596 | `ipc_figure_start_page` | — |

***

## Question 2 — Forward Door Installation on the R44

**Q:** How do I install a new forward door on the R44?

**HTTP Status:** `200 OK`

### Answer

#### 1. Procedure Title and Primary Source

- Forward Door Installation Procedure  
  *[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 27.1, PDF Page 797]*

#### 2. Warnings / Cautions

> ⚠️ **WARNING:** Failure to install a ring in each door's two hinge pins may allow the door to depart the aircraft in flight.

> 🔶 **CAUTION:** Use proper respiratory protection when handling fiberglass.

> 🔶 **CAUTION:** Protect door windows and paint from scratches or scuff marks when door maintenance is performed on a workbench.

#### 3. Required References

- Refer to Figures 27-1 and 27-2 for visual guidance.
- Adjust weight and balance per applicable Pilot's Operating Handbook Section 6.

#### 4. A. Removal

- Remove rings from door hinge pins, lift pins up from door frame hinge assemblies, and remove the door.
- Forward Doors: Pull D573-4 rod up and off of arm assembly ball joint.

#### 5. B. Installation

1. Align and insert door hinge pins in door frame hinge assemblies.
2. Align forward door D573-4 rod with arm assembly ball joint and push down to lock.
3. Install rings in door hinge pins.
4. Adjust weight and balance per applicable Pilot's Operating Handbook Section 6.

#### 6. Final Checks

- Verify doors open and close smoothly and latch correctly.

#### 7. Related IPC / Parts / Materials

- Forward Door Assembly parts such as **D573-4 Rod**, **D575-2 Ball Joint**, and **C394-2 Ball Stud** are detailed in the Illustrated Parts Catalog  
  *[Source: HELICOTER ILLUSTRATED PART CATALOG.pdf, PDF Page 356, Display Page 52.4]*

#### 8. Related Source-Supported References

- **C394-1** — present in the retrieved door/hinge/gas-spring context  
  *[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 27.1]*
- **B270-10, D575-3, A257-20, MS51861-37C, C683-4, D793-2** — present in the retrieved door/hinge/gas-spring context  
  *[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 23.9]*
- **D573-5, D575-1, C119-3** — present in the retrieved door/hinge/gas-spring context  
  *[Source: HELICOTER ILLUSTRATED PART CATALOG.pdf, Page 356]*
- **Section cross-references:** 23-33, 23-32, 23-72, 23-73, 23-74, 50-50, 27-00, 27-10, 27-30, 23-10, 23-70  
  *[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 23.9]*
- **POH reference:** the retrieved procedure points to the POH (Pilot's Operating Handbook) Section 6 for weight and balance  
  *[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 27.1]*

### Sources

| File | Display Page | PDF Page | Element Type |
|------|-------------|----------|--------------|
| HELICOTER MAINTENANCE MANUAL.pdf | 27.1 | 797 | `procedure_section_page` |
| HELICOTER MAINTENANCE MANUAL.pdf | 27.2 | 798 | `procedure_section_page` |
| HELICOTER MAINTENANCE MANUAL.pdf | 23.9 | 727 | `work_package_page` |
| HELICOTER MAINTENANCE MANUAL.pdf | 23.33 | 751 | `work_package_page` |
| HELICOTER MAINTENANCE MANUAL.pdf | 23.34 | 752 | `work_package_page` |
| HELICOTER MAINTENANCE MANUAL.pdf | 27.3 | 799 | `work_package_page` |
| HELICOTER ILLUSTRATED PART CATALOG.pdf | 52.9 | 361 | `ipc_keyword_page` |
| HELICOTER ILLUSTRATED PART CATALOG.pdf | 52.4 | 356 | `ipc_keyword_page` |
| HELICOTER ILLUSTRATED PART CATALOG.pdf | 52.1 | 353 | `ipc_keyword_page` |

***

## Question 3 — Clutch Engagement Delay (8 Seconds)

**Q:** The pilot told me that as he was proceeding to engage the clutch on the aircraft, it took him about 8 seconds before the rotor started to turn. What is the maximum time limit before it starts turning and what could I do to repair this problem?

**HTTP Status:** `200 OK`

### Answer

**Direct answer:** the rotor should start turning with a delay of **less than 5 seconds** when the clutch actuator is engaged at startup, so an 8-second delay is outside the AMM limit.  
*[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 10.19]*

**Diagnosis:** the source-supported adjustment area is the actuator down-limit/retraction limit stop screw and drive-belt deflection; the AMM also states that no field adjustment of actuator-engaged belt tension is permitted.  
*[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 10.19]*

**Corrective action:** adjust the retraction/down-limit stop screw to maintain proper belt deflection with the actuator fully disengaged, then recheck clutch engagement timing at startup.  
*[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 7.49]*

**Required tools:** the AMM lists a long **3/8-inch open-end wrench** or `MT357-6`, and a **1/4-inch box-end wrench** or `MT357-7`, for the retraction limit stop screw adjustment.  
*[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 7.49]*

> ⚠️ If maximum engaged extension is encountered, the AMM says the **drive V-belts must be replaced**.  
> *[Source: HELICOTER MAINTENANCE MANUAL.pdf, Page 7.49]*

### Sources

| File | Display Page | PDF Page |
|------|-------------|----------|
| HELICOTER MAINTENANCE MANUAL.pdf | 7.49 | — |
| HELICOTER MAINTENANCE MANUAL.pdf | 10.19 | — |
| HELICOTER MAINTENANCE MANUAL.pdf | — | 277 |
| HELICOTER PILOT HANDBOOK.pdf | — | 215 |
| helicopter-maintenance explinatin .pdf | — | 203 |
| HELICOTER MAINTENANCE MANUAL.pdf | — | 67 |
| HELICOTER PILOT HANDBOOK.pdf | — | 211 |
| HELICOTER PILOT HANDBOOK.pdf | — | 109 |
| HELICOTER PILOT HANDBOOK.pdf | — | 41 |
| helicopter-maintenance explinatin .pdf | — | 261 |

***
