# Template_TFE
Template for the Bachelor and Master theses at the school of Engineering of the University of Malaga. 

TFE stands for *Trabajo Fin de Estudios*, which means *Final Degree Project*.

# Files and Folders Organization

## Template
There are two files that define the UMA_templated used in this document: *UMA_template.sty*, and *UMA_template.tex*. They are (and should be) used for different things

### UMA_template.sty
This file imports the packages used in the template and define the configuration parameters. If you want to include new packages, you can include them here

### UMA_template.tex
This file change the default name of some items to have them in Spanish (e.g., Chapter = Capítulo, Figure = Figura), and defines some useful variables used along the project (e.g., TFE title, Author, Supervisor).

## Support
This folder contains support and pre-thesis documents

## Images
A folder that contains all the images of the project. If possible, try to use images in small size and vectorial format (i.e., PDF).

- The name of the image file should be self-descriptive (e.g., control_diagram.pdf, experiment_force_position_plot.PDF).
- Avoid using numbered names (e.g., image1.pdf, image2.pdf).
- Try to follow a name rule (e.g., put the name of chapter at the beginning and then the name of the image and always using underscore "__"_ between words: introduction_relevance_robotics_diagram.pdf, results_velocity_plot.pdf)

## biblio.bib
A file that contains the BibTex file with the bibliography using in the manuscript. If you are not familiar with BibTex, have a look at [this link](https://www.overleaf.com/learn/latex/Questions/How_to_include_a_bibliography_using_bibtex) and [this other link](https://www.overleaf.com/learn/latex/Bibliography_management_with_bibtex)

If you want to include a citation from a manuscript, just do the following (explained in [this tutorial in Spanish](https://github.com/jmgandarias/tutorial_latex)):
- Search for the manuscript title in google scholar (*example:* title of the paper: "MOCA-S: a sensitive mobile collaborative robotic assistant exploiting low-cost capacitive tactile cover and whole-body control" - [Google Scholar link](https://scholar.google.com/scholar?hl=en&as_sdt=0%2C5&q=MOCA-S%3A+a+sensitive+mobile+collaborative+robotic+assistant+exploiting+low-cost+capacitive+tactile+cover+and+whole-body+control&btnG=)]
- Click on *Cite*, if there is only one version, or *All N versions*, if there are N versions of if ([example of the previous paper](https://scholar.google.com/scholar?cluster=17878571624567848652&hl=en&as_sdt=0,5)) and then use the most official version (the one that has a link to the editor website), which usually is the first one and the one with all the citations of that manuscript. Click on *Cite* and select *BibTex*. Then copy the bibitem of the paper and paste it in your *biblio.bib* file.
The previous paper has the following bibitem:
```
@article{leonori2022moca,
  title={MOCA-S: a sensitive mobile collaborative robotic assistant exploiting low-cost capacitive tactile cover and whole-body control},
  author={Leonori, Mattia and Gandarias, Juan M and Ajoudani, Arash},
  journal={IEEE Robotics and Automation Letters},
  volume={7},
  number={3},
  pages={7920--7927},
  year={2022},
  publisher={IEEE}
}
```
- If you want to cite a paper in your document, just put ~\cite{*name_of_the_bibitem*}. The name of the previous bibitem is *leonori2020moca*.
- Try to organize the bibliography as follows:
    - Follow this order: Books, Journals, Conferences, Others
    - Name the bibitem as: *First_author_surnameYearFirst_word_of_the_title_of_the_paper*


# Author
This template has been authored by Juan M. Gandarias, Assistant Professor at the University of Malaga, inspired by the memorithesis template authored by Victor Baena
%

# Use it
There is an updated version of this project available in Overleaf at [this link](https://www.overleaf.com/read/hzprjsxdxczd#9b4fce)