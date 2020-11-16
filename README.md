# Text Analysis Workshop

These materials are adapted from workshops I did in 2018 and 2019 for AAPOR, NYAAPOR, the World Bank, and IBM, with a lot of help from an old colleague of mine, Mika Jugovich. 
They're intended to provide a broad overview of a variety of different text analysis methods, so you can pick out what's potentially interesting and useful for your own research, 
and have a starting point for additional independent learning.  You can find slides that pair with the notebook 
[here](https://drive.google.com/file/d/1dyUtpzTeNORmkzZt_-6sX_Cx6GH-KQa9/view?usp=sharing).

## Installation

### Run on Google Colab

Since these materials are purely for demonstration purposes only, the easiest way to play with the code is to open 
the tutorial notebook using Google Colab.  Colab provides a free Python/Jupyter environment with all of the standard Python 
data science packages pre-installed, so it's extremely easy to fire up on your own.  You can open the notebook direclty 
from this Github repository by going to the following link: [https://colab.research.google.com/github/patrickvankessel/AAPOR-Text-Analysis-2019/blob/master/Tutorial.ipynb](https://colab.research.google.com/github/patrickvankessel/AAPOR-Text-Analysis-2019/blob/master/Tutorial.ipynb)

### Run locally

If you want to run the notebook locally, you should be able to clone the repository onto your own machine by running the following code, 
assuming you have Python 3 and pip installed:

```bash
git clone https://github.com/patrickvankessel/text-analysis-workshop.git
cd text-analysis-workshop
pip3 install -r requirements.txt
python3 -m jupyter notebook
```