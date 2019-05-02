# SysMLTransformation
This repository contains Model-based transformation of OMG SysML model using Epsilon framework.
Epsilon framework: https://www.eclipse.org/epsilon/

Contents:

1. Implementation of two algorithms for Fault Tree generation of SysML models. The first algorithm derives Component-based Fault Tree from SysML models. The second, compose the generated Component-based Fault Trees based on SysML's internal block interconnections into System-level Fault Tree. The two transformations are written in the Epsilon Transformation Language (ETL).

2. In place Epsilon EOL transformation to update the SysML model from the previously generated FT models using crossmodal links.

3. An Epsilon EGL model to text transformation for the generation of FMEA models.

