---
content_type: page
title: Projects
uid: 90f60c06-d578-ff04-ac25-c2799d5bf7d9
---

Final Project Introduction ([PDF]({{< baseurl >}}/resources/project_intro-1))

Problem A ([PDF]({{< baseurl >}}/resources/project_a-1))

Problem B ([PDF]({{< baseurl >}}/resources/project_b-1))

Problem C ([PDF]({{< baseurl >}}/resources/project_c-1))

### For Problem C

Initial structure ({{% resource_link "c5afb4f1-770c-b9a2-4b1e-56921736daf6" "PDB" %}}) This is the initial structure (obtained from Protein Data Bank; after processing).  
Structure file ({{% resource_link "78777e54-4d70-b132-4024-f830da16a607" "PSF" %}})  
Initial fix.pdb file (specify fixed atoms) ({{% resource_link "8c650734-8e0a-9d76-7759-171147ab00f9" "PBD" %}})  
Initial smd.pdb file (specify atoms that are being pulled) ({{% resource_link "a5f590e4-585a-046c-a393-abdf67f8c4a5" "PDB" %}})

### Simulation Results

CMDF - Log file run mode I (short) ({{% resource_link "4d999063-a464-1d75-afde-5a941b448dcd" "XYZ" %}}) This .xyz file shows a sequence of crack propagation (1,000 steps, as in the example script given above). Frequency of snapshot writing, time step etc. is the same in all examples, and equal to the example script. You may directly load this file into VMD and carry out the analysis.

CMDF - Log file run mode II ({{% resource_link "37e81cc2-d4da-7ca2-1086-dbb875a0da01" "XYZ" %}}) Log file for 2,000 step mode II (shear run).

CMDF - xyz file - mode II, shear ({{% resource_link "3539024b-0910-7b50-93ba-423ff45100f5" "XYZ" %}}) This .xyz file shows a sequence of 2,000 steps under shear loading. Frequency of snapshot writing, time step etc. is the same in all examples, and equal to the example script.

NAMD - Initial geometry for pulling ({{% resource_link "9f09def6-cd30-4e68-69cd-12246301ea47" "COOR" %}})

NAMD - tensile deformation 0.002 rate (F-x-curve) ([JPG]({{< baseurl >}}/resources/fxcurve_002))

NAMD - tensile deformation 0.001 rate ([DCD]({{< baseurl >}}/resources/out_small_001))

NAMD - tensile deformation 0.0005 rate (F-x-curve) ([JPG]({{< baseurl >}}/resources/fxcurve_005))

NAMD - tensile deformation 0.0005 rate ([DCD]({{< baseurl >}}/resources/out_small_005))

NAMD - bending load (force-displacement plot) ([JPG]({{< baseurl >}}/resources/bending_load))

NAMD - bending load ([DCD]({{< baseurl >}}/resources/out_small_bending_load))

NAMD - tensile deformation 0.002 rate (data file for force-displacement plot) ({{% resource_link "497d53a5-ffc9-94b1-5148-dcacf3277333" "DAT" %}}) NOTE: Order of columns: Displacement (in Angstrom), force (in pN). This applies to all .dat files.

NAMD - tensile deformation 0.001 rate (data file for force-displacement plot) ({{% resource_link "2b4e680e-0d89-c17e-97f2-4a68277f1864" "DAT" %}})

NAMD - tensile deformation 0.0005 rate (data file for force-displacement plot) ({{% resource_link "9503dc85-1c4a-385b-9059-13db73a5eb52" "DAT" %}})

NAMD - bending deformation (data file for force-displacement plot) ({{% resource_link "1236a4ba-5bd4-4751-570f-d75163b7161e" "DAT" %}})