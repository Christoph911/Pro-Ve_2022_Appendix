# Collaborative System for Question Answering in German Case Law Documents - Pro-VE 2022


This paper has been submitted for publication at the *Pro-VE 2022 Conference*.

> We introduce a collaborative system for Question Answering in German caselaw documents and conduct experiments to proof that our trained model outperforms existing ones. 

## Abstract

> Legal  systems  form  the  foundation  of  democratic  states.  Neverthe-less, it is nearly impossible for individuals to extract specific information fromcomprehensive legal documents. We present a human-centered and AI-supportedarchitecture for semantic question answering (QA) in the German legal domain.Our architecture is built on top of human interaction and natural language pro-cessing (NLP) -based legal information retrieval. Laypersons and legal profes-sionals receive information supporting their research and decision-making by in-teracting with the architecture using a graphical interface. The internal AI is basedon state-of-the-art methods evaluating complex context-based search terms, con-sidering German law-specific words and phrases. Subsequently, relevant docu-ments or answers are ranked and presented to the user. In addition to the novelarchitecture, we publish the first annotated data set for QA in the German legaldomain.  The  experimental  results  indicate  that  our  semantic  QA  pipeline  out-performs existing approaches.


## Software implementation

All source code used to generate the results in the paper are in
the `src` folder.
The calculations and figure generation are all run inside
[Jupyter notebooks](http://jupyter.org/).
Test and train data used in this paper are provided in `data`.


## Getting the code

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    git clone https://github.com/Christoph911/Pro-Ve_2022_Appendix.git

or [download a zip archive](https://github.com/Christoph911/Pro-Ve_2022_Appendix/archive/master.zip).


## Dependencies

You'll need a working Python environment to run the code.
The recommended way to set up your environment is through the
[Anaconda Python distribution](https://www.anaconda.com/download/).
Anaconda can be installed in your user directory and does not interfere with
the system Python installation.
The required dependencies are: 
  - Python >= 3.7.5
  - farm-haystack >= 1.0
  - PyTorch
  - Running ElasticSearch DocumentStore (self-hosted or managed)
  - GPU support is highly recommended


## License

All source code is made available under a MIT-license. You can freely
use and modify the code, without warranty, so long as you provide attribution
to the authors.

The paper text is not open source. The authors reserve the rights to the
article content, which is currently submitted for publication in the
Springer Lecture Notes in Computer Science. 
