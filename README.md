![GitHub top language](https://img.shields.io/github/languages/top/hungtrannam/Possibilistics-clustering-for-CDF)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/hungtrannam/Possibilistics-clustering-for-CDF)
[![GitHub contributors](https://img.shields.io/github/contributors/hungtrannam/Possibilistics-clustering-for-CDF)](https://github.com/hungtrannam/Possibilistics-clustering-for-CDF/graphs/contributors)

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.6549626.svg)](https://doi.org/10.5281/zenodo.6549626)
![Version Number](https://img.shields.io/github/v/release/mathworks/toolboxdesign?label=version) ![CC-BY-4.0 License](https://img.shields.io/github/license/mathworks/toolboxdesign)


# PCF ToolBox for clustering the probability density functions&reg;


[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=UniprJRC/FSDA&project=FSDA.prj)
[![GNU Octave](https://img.shields.io/badge/Powered_by-GNU_Octave-blue.svg)](https://www.gnu.org/software/octave/)


**PCF** is a MATLAB module for paper **A new possibilistic-based clustering method for probability density functions and its application to detecting abnormal elements**.

The project was started in 2023 by authors of Hung Tran-Nam, Thao Nguyen-Trang, and Ha Che-Ngoc.

Comprehensive detail of all functions is provided in the [PDF-format manual (~200 pages)](https://github.com/petercorke/spatialmath-matlab/releases/download/untagged-a2f9c8b2bd21cca9fe39/spatialmath.pdf).


Advantages of the Toolbox are that:

  * the code is mature and provides a point of comparison for other implementations of the same algorithms;
  * the routines are generally written in a straightforward manner which allows for easy understanding, perhaps at the expense of computational efficiency. If you feel strongly about computational efficiency then you can always rewrite the function to be more efficient, compile the M-file using the MATLAB compiler, or create a MEX version;
  * source code is available for the benefit for understanding and teaching.









## Installation

From the MATLAB toolstrip ```Home > Add-Ons > Get Add-Ons``` will bring up the ```Add-On Explorer```.  Enter *"PCF clustering"* into the search box, select the first entry and then click *"Add from GitHub"*.  The Toolbox will be downloaded and added to your path.


## Octave

The functions should work fine with Octave 8.4.x.

Moreover, we should install the ```statistics``` package from Octave. To load the package, run from the Octave prompt the following.

```Octave
pkg install -forge statistics
pkg install -forge fuzzy-logic-toolkit
```

## Runing

### Usage

1. **Script Execution:**
   - Open the MATLAB environment.
   - Run the script `main_script.m`.

2. **Expected Outputs:**
   - Heatmap visualization of cluster memberships.
   - Overlay plot of probability density functions (PDF) and representative PDF.
   - Validation metrics for cluster quality.

### File Structure

- **Data**: Contains functions for data simulation (`SimPDFAbnormal`).
- **Figure_Output**: Directory for saving generated figures.
- **Package/Clust**: Clustering algorithms (`PCM_2`).
- **Package/Vis**: Visualization utilities (`PlotPDFeachIteration`).
- **Package/Val**: Validation functions (`validityClustering`).
- **Package/ToolBox**: Additional tools and utilities.

### Parameters and Settings

- **Data Simulation:** Generates data with abnormal parameters defined in `abnormal_params`.
- **Clustering Settings:** Parameters for PCM, including maximum iterations (`maxIter`), fuzziness (`mFuzzy`), convergence criteria (`epsilon`), number of clusters (`kClust`), and validation parameters.

### Dependencies

- MATLAB R2020a or later.
- Octave GNU 8.4.0 or later.
- Additional packages and functions as specified in the `addpath` section.



























## Citing

## Contact us
If you have any questions, bug reports, comments, code contribtions, or constructive discussions, please contact us at:
- E-mail: hung.trannam@vlu.edu.vn for questions, comments, and code contribtions
- Create new issue in [issues](https://github.com/hungtrannam/Probabilistics-clustering-for-CDF/issues) for constructive discussions and bug reports



-----------

[![CC-BY-4.0](https://github.com/hungtrannam/Probabilistics-clustering-for-CDF/blob/main//images/cc-by-40.png)](https://creativecommons.org/licenses/by/4.0/)

Copyright &copy; 2024, The MathWorks, Inc.



