# ECON-323 Final Project
## Analysis of Brazillian E-commerce Dataset by Olist

Please see the notebook `Final-Project.ipynb`. (Note: all **the data** has been downloaded from [Kaggle](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), and is available under **archive**)

You may use the provided `environment.yml` file to create a new conda environment (I used **conda 4.10.3** and **pip 21.2.2(python 3.7)** on a Macbook Air M1). You may also find it useful to create a jupyter ipykernel for it, and simply run all the cells in `Final-Project.ipynb`. The setup steps are as follows:

1. Create a new conda environment (called `econTest`) for running the project - `conda env create -f environment.yml`
2. Activate the environment via the terminal and then create a new ipykernel for it - 
```
conda activate econTest
python -m ipykernel install --user --name=econTest
jupyter lab
```
3. Open up the notebook with the created kernel, and run!