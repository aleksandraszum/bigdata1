# Big Data
# Miniproject 1 - Kaggle global terorrism analysis

This repository was created for Big Data Exploration course during studies.
Solutions was showed in this repository was about global terorrism analysis and they visualised results previously asked questions.

## What should you do

* Prepare your environment
This solutions was written on Linux with Python3.7.1.
You should install Python (and library such as: pandas, numpy, matplotlib, seaborn, sys), Anaconda, Jupyter Notebook. 

* Clone repo to own computer using: 

git clone https://github.com/aleksandraszum/bigdata1.git

* Create a new conda environment (it is not nessesary)


If you're using mini conda this step help you tune the the necessary Python packages.

All necessary packages are listed in requirements.yml file, that defines dataexp env.

Before you create the new dataexp env using conda, check if there is no different env with the same name on your PC. Remove all env that can create a conflict with the new one

conda env list
conda env remove --name dataexp

Create the new env using the package list from the provided file

conda env create -f requirements.yml
source activate dataexp

* Open the Jupyter Notebook and follow the instructions

jupyter notebook miniproject-bigdata1.ipynb

* Commit and push all the changes to your own github repo

git commit -m "My update.."
git push origin master


If you want to learn data exploration, do those tasks:

    1. Download data set, Global Terrorism Database, from https://www.kaggle.com/START-UMD/gtd
    2. Take a quick look at the data set. Check what's inside, how the data is structured, and where the data is corrupted (missing values, bad structure, etc).
    3. Think and create 5 questions to the data. Try to ask yourself what's really interesting in the data set. What's not so obvious. E.g. some trends, patterns, correlations.
    4. Create a jupyter notebook and use python, numpy, pandas, matplotlib (at least) to provide all the answers to your questions.
    5. Create a new github repository, and put your jupyter notebook there.
    6. Create readme.md file as well in your github root directory with all necessary instructions (what is in the repo, what libs are necessary to run the code, where to find data set and where to save it - this is necessary because the dataset is too big for github repo).
    7. Provide the necessary documentation and introduction in your notebook using markdown language, at least: data source description, data structure, importing process, data processing process.
    8. Put some data visualization in your notebook. Sometimes it's much easier to present the answer using a chart rather than numbers
    9. Check if your notebook run smoothly - use 'Reset & Run All' command from the menu. Save it.
    10. Export the notebook as HTML as well, and save the file in the repo.
    11. Do not forget to commit/push all the changes to your repo on hithub.
    12. Smile :) You did a good job!

FAQ:

    1. Can I take a look at different solution provided at kaggle? Yes, you can. But check more than one solution. Try to understand what the authors are trying to solve, and how could it be used in your project. Try to find really good examples - easy to understand and not so complicated. Remember - you create the notebook as an instruction to someone else! Try to not complicate the process.
    2. Can I take a look at my friend's solution, that he/she has just put on github? Yes, you can. But it's the smart way of solving the project. I'm sure that you want to be smarter in the next semester - so try to create a better solution and your own one :)
    3. Jupyter notebook provide R kernel, so can I use R instead? Nope, R sucks. Even if you love R, try to solve the project using Python.\n

virtualenv
