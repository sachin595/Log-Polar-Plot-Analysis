# Log-Polar-Plot-Analysis
In this computer vision project, log-polar plots were utilized for achieving size and orientation independence in image processing. The log-polar plot representation transforms pixel intensities from Cartesian to polar coordinates, enabling invariance to scaling, rotation, and translation. This property is particularly valuable in applications like image registration.

The formula for the log-polar plot transformation involves logarithmic scaling of radial distance (r) and calculation of the angle (θ) using the arctan2 function. The resulting log-polar plots were showcased for images of a car and a plane. Subsequently, the images underwent translation and rotation, revealing the resilience of log-polar plots to these transformations.

To quantify the effects of rotation and translation, the degree of rotation and extent of translation were calculated for each image. The observations showed that rotation had a more pronounced impact on log-polar plots than translation. The summary concludes with a tabulated representation of the rotation angles and translation extents for each image.

Overall, the project demonstrated the effectiveness of log-polar plots in achieving robustness against common geometric transformations, providing a foundation for applications such as image registration in computer vision. The quantification of rotation and translation parameters enhances the understanding of these transformations in the log-polar domain.
