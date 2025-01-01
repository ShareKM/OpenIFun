<p align="center">
  <img src="https://github.com/user-attachments/assets/8c4089a7-3563-4973-9015-3a2b48ae98fc" width="500" >
</p>

## ShareIF

Tracer kinetic modeling is a fundamental technique in dynamic positron emission tomography (PET) that uses mathematical models to extract physiologically significant parameters from the measured data. A blood input function is commonly required to serve as the input to the kinetic model and then used to fit the time activity curve (TAC) of a tissue region of interest or image voxel. However, obtaining a reliable input function is challenging in several contexts and has attracted much research effort in the technical field.

**ShareIF** is an open-data project to support the [Open Kinetic Modeling Initiative](https://www.openkmi.org/), aiming to build a database of blood input functions for tracer kinetic modeling in molecular imaging with dynamic PET. 

## Significance of the ShareIF Database

The **ShareIF** database may have several important technical applications for kinetic modeling and parametric imaging with both short- and long-axial field-of-view PET scanners. Examples include, but are not limited to:

- Developing population-based input function models, for instance, for whole-body Patlak parametric imaging of shortened dynamic scans that do not include an early dynamic scan for deriving the complete blood input function. 
- Developing optimization-derived input functions for dynamic brain PET imaging with conventional PET scanners. 
- Developing deep-learning models and algorithms by providing training pairs of high-quality and low-quality IDIFs and associated other types of data.

## Key Components of the Database

The **ShareIF** database includes:

1. **ShareIF4FDG**: This data project uses total-body PET scanners to collect image-derived input functions (IDIF) from dynamic PET scans of human subjects. Its first phase plans to collect the IDIFs of over 200 human subject scans performed with long axial field-of-view PET scanners (e.g. UIH uEXPLORER and Siemens Quadra).

>[!NOTE]
>**Ongoing Effort**: This data project is **in progress** and has not been formally announced. The database and its GitHub page are continually being updated.
