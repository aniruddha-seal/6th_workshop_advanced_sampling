# Path Sampling Tutorials

## Instructor/Authors

**Dr. Sapna Sarupria**
- Department of Chemistry, University of Minnesota
- https://sarupriagroup.github.io/
- sarupria@umn.edu

**Tutorials**
- PH (Porhouy Minh)
- Naomi Trampe

## Slides 
- Slides for for TPS/TIS/RETIS session can be found [here](https://github.com/icomse/6th_workshop_advanced_sampling/blob/main/Thursday/2024-iCoMSE-PathSampling-P1-TPSTIS.pdf)

## Getting setup and downloading the tutorials (NOTE: much of the material about accessing computing resources was for the workshop, and will not be available for people viewing the information after the workshop)
- To get this started, please login to Bridges2 OnDemand via: https://ondemand.bridges2.psc.edu/pun/sys/dashboard/

- Then navigate to Interactive Apps → Jupyter Lab 
  - Number of hours = 3
  - Number of nodes = 1
  - Account = see220002p
  - Partition = RM-shared**
  - Extra Slurm Args = -n 5

- After that, click on “Connect to Jupyter”. From here you should see a startup page which should have an option for you to open a “Terminal”.

- Then go into your iCoMSE directory by using the command: 
  - `$ cd [YOUR iCoMSE DIRECTORY]`

- Then using the command
  - `$ git pull`: This will allow you to download the latest version of contents within the iCoMSE repository. (note: you will need to first clone this repository before fetching)
 
 In addition to the Monday - Wednesday directories, you should now also see Thursday and Friday directories 
 
## Thursday Tutorials (Toy models of path sampling methods):
This tutorial will be run through Jupyter notebooks (located in the directory at the left of your screen) via OnDemand. For each Jupyter notebook, please make sure to switch your kernel to “icomse-cpu” kernel.

Note: For participants without Bridges2 access, please refer to this link: [https://github.com/icomse/6th_workshop_advanced_sampling/blob/main/settingup.md](y) for environment setup instructions

- In this tutorial, you will see Jupyter notebooks for each toy model of each path sampling method: TPS, TIS, RETIS. 
  - TPS = Transition path sampling
  - TIS = Transition interface sampling
  - RETIS = Replica exchange transition interface sampling 
 
- Each of these Jupyter notebooks will use langevin_dynamics.py, which uses stochastic dynamics to sample between two states (i.e., A and B) of the potential energy surfaces (PES) we provided.   

- Within each notebook, you will find short descriptions of what each notebook does and the learning objectives for that exercise.

## Literatures regarding TPS, TIS, RETIS
- [https://doi.org/10.1146/annurev.physchem.53.082301.113146](url)
- [https://doi.org/10.1002/9780470890905.ch3](url)
- [http://dx.doi.org/10.1063/1.1562614](url)
- [https://doi.org/10.1016/j.jcp.2004.11.003](url)
- [https://doi.org/10.1063/1.4989844](url)
- [https://doi.org/10.1063/1.2976011](url)
- [https://doi.org/10.1063/5.0080053 ](url)
## Literatures regarding maximum likelihood estimation (MLE) for obtaining RC and reweighted path ensembles (RPE) 
- [https://doi.org/10.1063/1.2234477](url)
- [https://doi.org/10.1063/1.2409924](url)
- [https://doi.org/10.1146/annurev-physchem-040215-112215](url)
- [https://doi.org/10.1007/s10955-011-0324-6](url)
- [https://doi.org/10.1063/1.3651367](url)
- [https://doi.org/10.1063/1.3491817](url)
## Literatures regarding infRETIS
- [https://doi.org/10.1021/acs.jpca.2c06004](url)
- [https://doi.org/10.1073/pnas.2318731121](url)
## Literatures regarding ML with TPS
- [https://doi.org/10.1038/s43588-023-00428-z](url)
- [https://doi.org/10.1021/acs.jctc.3c00821](url)
- [https://doi.org/10.1088/2632-2153/acf55c](url)



