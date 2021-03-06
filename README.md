# PASA
This repository contains the source code of an F\# implementation of the PASA probabilistic approach for predicting QoS of parallel design patterns-based applications. Such approach has been presented in
> _A. Brogi, M. Danelutto, D. De Sensi, A. Ibrahim, J. Soldani, M. Torquati <br>
> **Analysing Multiple QoS Attributes in Parallel Design Patterns-based Applications.** <br>
> [International Journal of Parallel Programming, pp 1–20, DOI: 10.1007/s10766-016-0476-8, 2016]._ 

If you wish to reuse the sources in this repository, please properly cite the above mentioned paper. Below you can find the BibTex reference:
```
@article{PASA,
 author = {Antonio Brogi and Marco Danelutto and Daniele De~Sensi and Ahmad Ibrahim and Jacopo Soldani and Massimo Torquati},
 title = {Analysing Multiple QoS Attributes in Parallel Design Patterns-based Applications},
 journal = {International Journal of Parallel Programming},
 pages = {1--20},
 year = {2016},
 issn = {1573-7640}
 note = {http://dx.doi.org/10.1007/s10766-016-0476-8}
} 
```
## How to use PASA
In order to use this program, you need to do following steps:

* Install Microsoft Visual Studio 2013. 
* Create a Visual F# Console Application project.
* Right click on project name in "Solution Explorer" window to add existing code files.
* In F# project, order of the code files is very important (files can be Move Up or Down). Please use the following order to run PASA:
 * Visualizer.fs
 * PASA.fs
 * Example1.fs
 * Example2.fs
 * Main.fs
* You may also need to add  *FSharp.Charting*, *FSharp.Core*, *FSharp.Data* etc in the *References* depending upon your system configuration.

