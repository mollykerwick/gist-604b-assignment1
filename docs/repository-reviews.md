# Open Source Repository Review

**Student:** Molly Kerwick

**Course:** GIST 604B – Open Source GIS  

**Assignment:** GitHub Repository Management  

---

## Repository 1

**Repository Name:**  GeoPandas

**Link:**  https://github.com/geopandas/geopandas

### Purpose
This project adds support for geographic data using the Pandas library.

### Repository Structure
The repo has a multitude of .yml (YAML) files. I believe these are a more readable file type used in HTML conversion for their website <https://geopandas.org/en/stable/>. Since each YAML file is easily readable before HTML conversion, they act as documentation in each directory, which is helpful.

### Documentation
The README is very helpful. It lists all of the required Python libraries. It also includes example code with example figures. The README includes a BibTeX citation which is helpful.

### Activity
Yes. The community is very active with the most recent pull request merge being 8 days ago.

### Key Observation
They give detailed instructions for how to contribute to the project including test development requirements and commit message standards.

---

## Repository 2

**Repository Name:**  Cartopy

**Link:**  https://github.com/scitools/cartopy?tab=readme-ov-file

### Purpose
Creates maps using Python for data visualization. It uses Matplotlib with increased capability.

### Repository Structure
There is an examples directory with Python scripts showing the use of different functions and classes.

### Documentation
The README provides limited overview of the project and data types, but does include a link to the website with more information about the project.

### Activity
Yes. The most recent commit is from 23 hours ago.

### Key Observation
While the community is small (131 contributors), the community seems very active with 403 current forks.

---

## Repository 3

**Repository Name:** QGIS

**Link:** https://github.com/qgis/QGIS

### Purpose
Highly functional mapping software for Unix, Windows, and MacOS

### Repository Structure
Most of the repo is written in C++, and the install files for different operating systems are included in nested directories.

### Documentation
The README is incredibly helpful with example visualizations, installation instructions, and guidance on contributing to the project.

### Activity
The project is actively maintained with the most recent commit being 2 hours ago, and a plethora of tests from past contributors.

### Key Observation
This project has very robust documentation including READMEs in nested folders and training manuals on how to use the software.

---

## Repository 4

**Repository Name:**  TracPy

**Link:** https://github.com/kthyng/tracpy

### Purpose
Python wrapper for TRACMASS, a flow modeler tool used in oceanography mapping.

### Repository Structure
The project has an ideal repo storage system for a small software project including README, src, docs, etc.

### Documentation
The README has very clear installation instructions including use of miniconda. It looks like the markdown for the README lost support as the numbering is now not working.

### Activity
The repository hasn't been updated in about 7 years so no, the repo is no longer maintained.

### Key Observation
This project utilizes multiple Python features very well, including miniconda and ipython notebooks.

---

## Reflection

I learned that open source projects have at minimum a README, a src folder, a docs folder, and a tests folder. They also all have a LICENSE of use. As the project gets more contributions and edits, the project becomes a little more difficult to navigate. This is why clear documentation at every level is important. Nested READMEs are very helpful for large projects like QGIS, but are not needed for smaller projects like TracPy. Overall, the use of clear naming conventions, including for commit messages, are needed if the project would like to have an actively contributing community.
