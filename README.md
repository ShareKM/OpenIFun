# OpenIFun
Tracer kinetic modeling is a fundamental technique in dynamic positron emission tomography (PET) that uses mathematical models to extract physiologically significant parameters from the measured data. A blood input function is commonly required to serve as the input to the kinetic model and then used to fit the time activity curve (TAC) of a tissue region of interest or image voxel. However, obtaining a reliable input function is challenging in several contexts and has attracted much effort in the technical field.
![Wang_OpenIFun_KM](https://github.com/user-attachments/assets/bceb995d-a2db-4909-8cf5-d35ce0697c2d)

**OpenIFun** is an open-data project, launched as a part of the Open Kinetic Modeling Initiative (OpenKMI), aiming to build a database of blood input functions for tracer kinetic modeling in dynamic PET data. The first effort uses total-body PET scanners to collect image-derived input functions (IDIF) from major blood pools from dynamic PET scans of human subjects for the widely used radiotracer <sup>18</sup>F-FDG.

This database has several crucial applications. Examples include, but are not limited to:

- It can be used to develop population-based input function models, for instance, for whole-body Patlak parametric imaging of shortened dynamic scans that do not include an early dynamic scan for deriving the complete blood input function.
- It can be used to develop deep-learning models and algorithms by providing training pairs of high-quality and low-quality IDIFs and associated other types of data.
