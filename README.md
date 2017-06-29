# SVFEngine

## 1.Publication
 -  https://doi.org/10.1016/j.enbuild.2017.05.024
 -  http://www.sciencedirect.com/science/article/pii/S0378778816317030
 -  Liang, J., Gong, J., Sun, J., & Liu, J. (2017). A customizable framework for computing sky view factor from large-scale 3D city models. Energy and Buildings, 149, 38-44.
 -  Abstract
A common approach to derive the sky view factor (SVF) in an urban environment is to combine urban morphological modeling and computational geometry techniques. Computational methods and tools have been developed to derive SVF from digital surface models (DSMs) and small-scale three dimensional (3D) city models, but they are not well suited for accommodating large-scale 3D city models. In this paper, we present a computational framework (SVFEngine) for deriving SVF from a wide variety of 3D city models, including the recently developed oblique airborne photogrammetry-based 3D city model (OAP3D), which is a highly detailed representation of an urban environment. We compared the SVF estimates computed from a large-scale high-resolution OAP3D with those from a set of street view panoramas at 30 locations. The comparison shows that the SVF estimates obtained using both methods closely match each other with a correlation coefficient of 0.99. The result suggests that high-resolution 3D city models have the potential for deriving accurate SVF estimates. Several examples are presented to show how SVFEngine can be applied in urban environmental modeling and analysis. The source code of SVFEngine is freely available (https://github.com/ljm355/SVFEngine) so it can be fully integrated into a user-defined workflow.

## 2.Environment
 * (1) Operating System: deveoped and tested under Windows 7 64-bit
 * (2) IDE: Visual Studio 2015. Make sure that x64 mode is on and Configuration Properties -> Working Directory be set to $(SolutionDir)\bin.
 * (3) Precompiled dependencies: OpenSceneGraph 3.2.0(http://www.openscenegraph.org/), osgEarth 2.5 (http://osgearth.org/) and GDAL 2.1.2 (http://www.gdal.org/). They can be acquired from OSGeo4W (https://trac.osgeo.org/osgeo4w/).

## 3. Test data
 * (1) bin/data/models/OAP3D/OAP3D.osgb (used in Example 1 and 2): a subset of an oblique airborne photogrametry-based 3D city model (OAP3D).
 * (2) bin/data/models/CAD/CAD.osg (used in Example 1): a subset of a 3D city model created in a CAD software.
 * (3) Boston building footprints (used in Example 3): packed with osgEarth.

## Contact:
Dr. Jianming Liang
ljm355@163.com


