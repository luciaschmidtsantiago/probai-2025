# ProbAi 2025 | Day 5

## Session 1 | Geometric Probabilistic Models - Viacheslav Borovitskiy

## Session 2 | Probabilistic Circuits - Antonio Vergari
you will need to install the cirkit library that you can find here: https://github.com/april-tools/cirkit (try to install it before the lecture!). 

Alternatively, you can run the Google Colab notebooks code with 
`!pip install libcirkit -q --no-deps ` and `!pip install torch torchvision -q` added in the first lines.

- Notebooks
    * fitting a simple GMM implemented as a circuit
      * [Link](https://github.com/april-tools/cirkit/blob/main/notebooks/learning-a-gaussian-mixture-model.ipynb)
      * [Colab](https://colab.research.google.com/github/april-tools/cirkit/blob/main/notebooks/learning-a-gaussian-mixture-model.ipynb)
    * building and fitting a deeper circuit
      * [link](https://github.com/april-tools/cirkit/blob/main/notebooks/learning-a-circuit.ipynb)
      * [Colab](https://colab.research.google.com/github/april-tools/cirkit/blob/main/notebooks/learning-a-circuit.ipynb)
    * (optionally) mixing and matching circuits and tensor factorizations structures
      * [link](https://github.com/april-tools/cirkit/blob/main/notebooks/region-graphs-and-parametrisation.ipynb)
      * [Colab](https://colab.research.google.com/github/april-tools/cirkit/blob/main/notebooks/region-graphs-and-parametrisation.ipynb)

### If you get a problem with running the code on Colab
You need to change your Colab notebook's runtime type to GPU. Follow these steps:

1. Go to "Runtime" in the Colab menu: At the top of your Google Colab notebook, find the "Runtime" menu option.
2. Select "Change runtime type": From the "Runtime" dropdown, choose "Change runtime type."
3. Choose "GPU" as the hardware accelerator: A dialog box will appear. Under "Hardware accelerator," select "GPU" from the dropdown menu.
4. Click "Save": After selecting GPU, click the "Save" button.
