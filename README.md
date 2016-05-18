No bullshit guide to linear algebra notebooks
=============================================

Jupyter notebooks with exercises for the [*No bullshit guide to linear algebra*](https://gum.co/noBSLA).

I recommend you **watch the videos at 1.5x speed** to make them more interesting ;)

Abstract
--------
Linear algebra is the study of vectors and linear transformations.
You may be familiar with vectors from learning about them in physics class,
but in linear algebra vectors will play a central role so you'll get to know
them very well, and also study the types of functions you can apply to vectors.
In particular we'll study the linear transformations, which are functions that
take vectors as inputs and produce vectors as outputs.
Linear transformations can be represented by matrices, thus we can also say that
linear algebra is the study of vectors and matrices.


Contents
--------
### Chapters overview
Video: https://www.youtube.com/watch?v=2G3PmEZI6n8  
Notebook: [Linear_algebra_chapters_overview.ipynb](./Linear_algebra_chapters_overview.ipynb) 

### Ch3: Definitions of vectors and matrices
Video: https://www.youtube.com/watch?v=IjyKTvhWG70  
Notebook: [chapter03_definitions.ipynb](./chapter03_definitions.ipynb)

### Ch3: Linearity
Video: https://www.youtube.com/watch?v=RLvLt6DQct8  
Notebook: [chapter03_linearity_intuition.ipynb](./chapter03_linearity_intuition.ipynb)

### Ch4: Gauss-Jordan elimination and Reduced row echelon form 
Video: https://www.youtube.com/watch?v=tfC6KMsRP8w  
Notebook: [chapter04_exercises.ipynb](./chapter04_exercises.ipynb)

### Ch4: Problems 
Notebook: [chapter04_problems.ipynb](./chapter04_problems.ipynb)


Other stuff
-----------

    cut_material/               Less interesting things lessons, and testing
       python_basics_zero_based_indexing.ipynb
       plotting_work.ipynb      example usage for plot_helpers
       Linear_algebra_overview_proj_example.ipynb   first draft of Overview notebook
    
    extra/
       Determinants.ipynb                       Determinant formula from first principles
       Vector fields 2D.ipynb                   examples of vector fields (can be used for vector calc)
       jupyter widgets math demo.ipynb          example interactives in notebook
       python_basics_zero_based_indexing.ipynb  
    
    requirements.txt            python packages required to tun these notebooks
    
    util/                       Utility and support functions
       md_to_ipynb_helper.ipynb convert an outline (markdown list) to notebook cells
       notebook_helpers.py      used in above
       plot_helpers.py          functions for potting vectors, lines, and planes



Install
-------
Create a virtual env and install the packages from `requirements.txt`:

    virtualenv  -p python3.5 pydev
    source pydev/bin/activate
    pip install -r requirements.txt


Running
-------
Just start the jupyter notebook server:

    source pydev/bin/activate
    jupyter notebook

then access the notebooks using your favourite browser.
