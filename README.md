Download these files and extract them into a working directory https://www.kaggle.com/datasets/angelolmg/tilda-400-64x64-patches/data 

It should look something like this:

![explorer_DKr4xVZRoy](https://github.com/theBombfly/TDA_Project/assets/79114060/4e8022af-c7cb-4d75-8ae8-ca0959dfa36c)


Preproccesor.py does all of the homology/persistence imaging and pushes it to the "datadumper". The MDS doesn't do a whole lot, the clustering is
too high dimensional. SVM classification gets about 93% training and 91% validation accuracy. Both of these can run without the raw data, they 
pull from the preproccess dump. These are all CLI scripts, so copying code to a jupyter notebook and including some commentary is probably all
that needs done for camera ready.
