# Path Sampling Tutorials

# Getting setup and downloading the tutorials:

- To get this started, please login to Bridges2 OnDemand via: https://ondemand.bridges2.psc.edu/pun/sys/dashboard/

- Then navigate to Interactive Apps → Jupyter Lab 
  - Number of hours = 3
  - Number of nodes = 1
  - Account = see220002p
  - Partition = RM-shared**
  - Extra Slurm Args = -n 1

- After that, click on “Connect to Jupyter”. From here you should see a startup page which should have an option for you to open a “Terminal”.

- Then go into your iCoMSE directory by using the command: 
  - “$ cd [YOUR iCoMSE DIRECTORY]”

- Then using the command
  - “$ git pull origin main”: This will allow you to download the latest version of contents within the iCoMSE repository. 
 
 In addition to the Monday - Wednesday directories, you should now also see Thursday and Friday directories 
 
# Thursday Tutorials (Toy models of path sampling methods):

This tutorial will be run through Jupyter notebooks (located in the directory at the left of your screen) via OnDemand. For each Jupyter notebook, please make sure to switch your kernel to “icomse-cpu” kernel.

- In this tutorial, you will see Jupyter notebooks for each toy model of each path sampling method: TPS, TIS, RETIS, FFS and cFFS. 
  - TPS = Transition path sampling
  - TIS = Transition interface sampling
  - RETIS = Replica exchange transition interface sampling 
  - FFS = Forward flux sampling 
  - cFFS = Contour forward flux sampling 
 
- Each of these Jupyter notebooks will use langevin_dynamics.py, which uses stochastic dynamics to sample between two states (i.e., A and B) of the potential energy surfaces (PES) we provided.   

- Within each notebook, you will find short descriptions of what each notebook does and the learning objectives for that exercise.
