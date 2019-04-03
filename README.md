## athenahacks_demo
Demo Objectives:
  - Ease of working with APIs in Python
  - Basic NLP concepts with Python
  - Word2Vec
  - NLP + Classification
  
## Getting Set-Up
Getting set-up with Python can be a pain sometimes, so hopefully these instructions make it as seamless as possible.

1. Download the [anaconda distribution for your OS](https://www.anaconda.com/distribution/). If it's your first time, you'll want to check the add to path part, even if it shows up red.

2. Clone this repo and `cd` into it:

```
   git clone https://github.com/jwilber/athenahacks_demo.git
   cd athenahacks_demo
```

2. Once you have conda, install the environment for this project:

```
   conda env create -f environment.yml
```

This should create an environment called `athena`. This will install all required packages for the demo in a containerized manner. Read more about environments [here](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html).

3. Activate the newly installed environment.

```
   source activate athena
```

4. Set-up `gensim` stuff if necessary.

```
   python -m spacy download en
```

5. Launch jupyter notebooks

```
   jupyter notebook
```

A web-browser should launch serving the repo's content. Navigate to `notebooks` and go crazy.

When you're done with this, you can exit the python environment via `source deactivate`.
