## FFS and cFFS Tutorials and Simulation of LiF Dissociation using RETIS and FFS:

## Instructor/Authors

**Dr. Sapna Sarupria**
- Department of Chemistry, University of Minnesota
- https://sarupriagroup.github.io/
- sarupria@umn.edu

**Tutorials**
- PH (Porhouy Minh)
- Naomi Trampe

## Slides:
- Slide for FFS/cFFS session can be found [here](https://github.com/icomse/3rd_workshop_advanced_sampling/blob/main/Friday/2023-iCoMSE-PathSampling-P2-FFScFFS.pdf)

## Videos: 
- [Video for FFS explanation]
- [Video for cFFS explanantion]
- [Video for FFS tutorial]

## Getting setup and downloading the tutorials (NOTE: much of the material about accessing computing resources was for the workshop, and will not be available for people viewing the information after the workshop)

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
  - “$ git pull”: This will allow you to download the latest version of contents within the iCoMSE repository. (note: the repository referred to is THIS repostitory, which contains this information - you will have to clone it, via `git clone https://github.com/icomse/3rd_workshop_advanced_sampling.git`.)
    - If you are facing an issue due to the fact that you have previous commits, then you'd run do a "$ git revert" first before doing "$ git pull"
 
## Friday Tutorials (Toy models of path sampling methods):

This tutorial will be run through Jupyter notebooks (located in the directory at the left of your screen) via OnDemand. For each Jupyter notebook, please make sure to switch your kernel to “icomse-cpu” kernel.

Note: For participants without Bridges2 access, please refer to this link: [https://github.com/icomse/3rd_workshop_advanced_sampling/blob/main/settingup.md](y) for environment setup instructions

- In this tutorial, you will see Jupyter notebooks for each toy model of each path sampling method: FFS, cFFS. 
  - FFS = Forward flux sampling
  - cFFS = Contour forward flux sampling
 
- Each of these Jupyter notebooks will use langevin_dynamics.py, which uses stochastic dynamics to sample between two states (i.e., A and B) of the potential energy surfaces (PES) we provided.   

- Within each notebook, you will find short descriptions of what each notebook does and the learning objectives for that exercise.

## Literature regarding FFS and cFFS
- Simulating rare events in equilibrium or nonequilibrium stochastic systems [https://doi.org/10.1063/1.2140273](https://doi.org/10.1063/1.2140273)
- Forward flux sampling-type schemes for simulating rare events: Efficiency analysis [https://doi.org/10.1063/1.2198827](https://doi.org/10.1063/1.2198827)
- Optimizing the sampling and staging for simulations of rare events via forward flux sampling schemes [https://doi.org/10.1063/1.2953325](https://doi.org/10.1063/1.2953325)
- Kinetics and mechanism of the unfolding native-to-loop transition of Trp-cage in explicit solvent via optimized forward flux sampling simulations [https://doi.org/10.1063/1.3474803](https://doi.org/10.1063/1.3474803)
- Automatic, optimized interface placement in forward flux sampling simulations [https://doi.org/10.1063/1.4801866](https://doi.org/10.1063/1.4801866)
- Contour forward flux sampling: Sampling rare events along multiple collective variables [https://doi.org/10.1063/1.5063358](https://doi.org/10.1063/1.5063358)

## Reviews regarding FFS and cFFS
- Forward flux sampling for rare event simulations [http://doi.org/10.1088/0953-8984/21/46/463102](http://doi.org/10.1088/0953-8984/21/46/463102)
- Studying rare events using forward-flux sampling: Recent breakthroughs and future outlook [https://doi.org/10.1063/1.5127780](https://doi.org/10.1063/1.5127780)
- Practical guide to replica exchange transition interface sampling and forward flux sampling [https://doi.org/10.1063/5.0080053](https://doi.org/10.1063/5.0080053)

