# OSU Subcritical Assembly

This repository contains an OpenMC model of the subcritical assembly at Oregon State University's Radiation Center. The assembly is composed of graphite bricks, UO_2 fuel rods, a concrete reflector, and a plutonium–beryllium neutron source.

## Overview

The subcritical assembly is designed to teach students about nuclear reactions and how to take measurements for a reactor. The main components of the assebmbly are as follows:

- **Graphite Bricks:** Serve as both structural support and neutron moderator.
- **UO_2 Fuel:** Annular fuel rods with natural uranium enrichment (0.072% U-235) and aluminum cladding.
- **Concrete Reflector:** Enhances neutron economy by reflecting neutrons back into the assembly.
- **Plutonium–Beryllium Neutron Source:** Initiates the neutron population required for the assembly's operation.

## Assembly Dimensions

### UO₂ Fuel Rods
- **Type:** Annular rods with aluminum cladding.
- **Enrichment:** Natural uranium (0.072% U-235).
- **Dimensions:** 
  - **Fuel Length in z-direction:** 45 cm
  - **Innermost Air Hole Radii:** 0.46 cm
  - **Clad Inner Radii:** 0.61875 cm
  - **Radii of the UO_2 Fuel:** 1.76125 cm
  - **Radii of Outermost Clad:** 1.92 cm

### Graphite Bricks
- **Dimensions:**
  - **Length in x-direction:** 50 cm
  - **Height in y-direction:** 15 cm
  - **Width in z-direction:** 15 cm
- **Fuel Arrangement:**  
  Each brick features a central hole for fuel placement that is the same radii as the outermost cladding of the fuel. Along the z-axis of the brick, three UO_2 fuel rods are inserted. The combined length of these rods is 135 cm, with an additional 15 cm gap filled by air.

### Concrete Reflector
- **Dimensions:**
  - **Length in x-direction:** 15.24 cm
  - **Height in y-direction:** 180 cm
  - **Width in z-direction:** 150 cm
- **Placement:**  
  Positioned to the right of the assembly, the concrete wall functions as a reflector to bounce neutrons back into the reactor core. This concrete reflector's leftmost side is touching the rightmost side of the assembly.

### Graphite Floor
- **Dimensions:**
  - **Length in x-direction:** 150 cm
  - **Height in y-direction:** 30 cm
  - **Width in z-direction:** 150 cm

### Neutron Source
- **Type:** Plutonium–Beryllium.
- **Location:**  
  Centrally located on the graphite floor at coordinates (75, -15, 75) with a raii of 2 cm within the reactor framework.


