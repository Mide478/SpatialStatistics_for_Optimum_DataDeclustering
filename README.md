# SpatialStatistics_for_Optimum_DataDeclustering


<!-- TABLE OF CONTENTS -->
<h2 id="table-of-contents"> :book: Table of Contents</h2>

<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#project-summary"> ➤ Project Summary</a></li>
    <li><a href="#prerequisites"> ➤ Prerequisites</a></li>
    <li><a href="#folder-structure"> ➤ Folder Structure</a></li>
    <li><a href="#dataset"> ➤ Dataset</a></li>
    <li><a href="#acknowledgements"> ➤ Acknowledgements</a></li>
    <li><a href="#contributors"> ➤ Contributors</a></li>
  </ol>
</details>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- PROJECT SUMMARY -->
<h2 id="project-sumary"> :pencil: Project Summary</h2>

<p align="justify"> 
 
* Subsurface resource sampling is not designed for representativity, yielding biased spatial datasets.

* Cell-based declustering (CBD) is used for debiasing datasets with sampling bias. However, the cell size selection in CBD is irrational and subjective.

* We propose a novel workflow, Spatial Statistics-based Assignment of Declustering Cell Size (SSADC) to objectively determine the optimal cell size during CBD via spatial point statistics.

* SSADC consistently yields more accurate estimates of the true population across various degrees of sampling bias, demonstrating its effectiveness in spatial debiasing. 

</p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- PREREQUISITES -->
<h2 id="prerequisites"> :fork_and_knife: Prerequisites</h2>

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>
[![made-with-R](https://img.shields.io/badge/Made%20with-R-blue.svg)](https://www.r-project.org/) <br>
[![Made withJupyter](https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter)](https://jupyter.org/try) <br>

<!--This project is written in Python programming language. <br>-->
The following open-source packages are mainly used in this project:
* Numpy
* Pandas
* Matplotlib
* Scipy

Please install other required packages detailed in the `requirements.txt` file and include custom-made `Functions.py` containing functions in active working directory

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- :paw_prints:-->
<!-- FOLDER STRUCTURE -->
<h2 id="folder-structure"> :cactus: Folder Structure</h2>

    Scripts
    .
    ├── Functions.py

    Workflows
    .
    ├── R Notebook: Cellsized_RipleyK_Example.Rmd
    ├── SSADC Example.ipynb

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)
<!-- DATASET -->
<h2 id="dataset"> :floppy_disk: Dataset</h2>
<p> 
  The dataset used for example demonstration in SSADC Example Case folder is publicly available in <a href="[https://github.com/GeostatsGuy](https://github.com/GeostatsGuy/GeoDataSets/blob/master/sample_data_biased.csv)"> GeoDataSets: Synthetic Subsurface Data Repository as `sample_data_biased.csv` </a> 
  
</p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- ACKNOWLEDGEMENTS -->
<h2 id="acknowledgements"> :scroll: Acknowledgements</h2>
<p align="justify"> 
This work is supported by the Digital Reservoir Characterization Technology (DIRECT) Industry Affiliate Program at the University of Texas at Austin, and many thanks to Equinor for providing real dataset used to test the workflow.
</p>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<!-- CONTRIBUTORS -->
<h2 id="contributors"> :scroll: Contributors</h2>

<p>  
  👩‍🎓: <b>Ademide O. Mabadeje</b> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Email: <a>ademidemabadeje@utexas.edu</a> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GitHub: <a href="https://github.com/Mide478">@Mide478</a> <br>
  
  👨‍🏫: <b>Michael J. Pyrcz</b> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Email: <a>mpyrcz@austin.utexas.edu</a> <br>
  &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; GitHub: <a href="https://github.com/GeostatsGuy">@GeostatsGuy</a> <br>
</p>
<br>
