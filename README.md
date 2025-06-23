# mango: A generative design framework intended for wireframe DNA origami

This is a Python-based generative design framework intended for wireframe DNA origami. Here, grammars are employed which can allow for the exploration of wireframe objects corresponding with different design features. This framework is intended to give you a "sandbox" to generate designs which minimize an input function given specific design constraints. The accompanying readthedocs documentation walks through tutorials on the types of designs the can be generated.

Also, this package can create standardized outputs that can be created and viewed in browser using the [visualization application](https://ajvetturini.github.io/kodak/).

This package is in active development and it should be expected for code to change quite frequently.

# Documentation
Documentation can be found [here](https://mango-docs.readthedocs.io/en/latest/index.html).

Tutorials can be found [here](https://mango-docs.readthedocs.io/en/latest/tutorials.html#).

# How to install

As this toolkit is still an early build, it is not currently available on PyPi / pip. Therefore, to install (or update) the package, please run the following commands.

1. Create a new virtual environment in anaconda (_recommended_)
2. Open a terminal (or command line) and run the following commands in order (you can just copy and paste the whole line. Please note the period on the 3rd bullet)
   - git clone https://github.com/CMU-Integrated-Design-Innovation-Group/Mango.git
   - cd Mango
   - pip install -e .

This should install the mango package to your environment which you can then import into a Python. Please see readthedocs for a tutorial on how this framework is intended to be used.

# Citation

If you use this application in your work, we kindly ask that you use the following citation:

Vetturini, Anthony J, Jonathan Cagan, and Rebecca E Taylor. “Generative Design-Enabled Exploration of Wireframe DNA Origami Nanostructures.” Nucleic Acids Research 53, no. 2 (January 27, 2025): gkae1268. https://doi.org/10.1093/nar/gkae1268.


# Funding

This work was supported through the following:

- National Science Foundation [CMMI-2113301]
- Air Force Office of Scientific Research [FA9550-22-1-0147]
- National Defense Science and Engineering Graduate Fellowship

# Requirements

Python Version >= 3.9

- dill==0.3.8
- networkx==3.2.1
- numba==0.59.0
- numpy==1.26.4
- pandas==2.2.0
- plotly==5.18.0
- pymeshfix==0.16.2
- pyvista==0.43.2
- scipy==1.12.0
- trimesh[easy]==4.1.0
