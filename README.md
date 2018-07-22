# Julia Meets Mendel: Algorithms and Software for Modern Genomic Data

This repo contains the materials for short course [_Julia Meets Mendel: Algorithms and Software for Modern Genomic Data_](http://ww2.amstat.org/meetings/jsm/2018/onlineprogram/ActivityDetails.cfm?SessionID=215388) at 2018 Joint Statistical Meeting (JSM), Vancouver, Canada.

## Syllabus

| Time | Topic | Instructor |  
|:-----------|:------------|:------------|  
| 8:30-9:00 | participants intro., intro. to OpenMendel | Eric Sobel |  
| 9:00-9:30 | Julia: more than just fast R | Hua Zhou |  
| 9:30-10:15 | Julia: linear algebra, optimization | Hua Zhou |  
| 10:15-10:30 | coffee break | |  
| 10:30-11:15 | Julia: parallel computing | Hua Zhou |  
| 11:15-noon | review of genetic and genomic concepts | Janet Sinsheimer |  
| noon-1:00 | lunch | |  
| 1:00-2:00 | handling big genomic data in OpenMendel | Hua Zhou |  
| 2:00-3:15 | GWAS for population and genetic analysis | Eric Sobel |  
| 3:15-3:30 | coffee break | |  
| 3:30-4:00 | linear mixed models for genetic analysis | Hua Zhou |  
| 4:00-4:45 | mendelian randomization | Janet Sinsheimer |  
| 4:45-5:00 | how to contribute to OpenMendel project | Eric Sobel |  

## Getting started

There are several ways run Jupyter notebooks in this course.

### Run Jupyter notebooks on the dedicated server

The **easiest** way is to run Jupyter notebooks on a server dedicated to this course.  

0. Point your browser to [localhost:8000]().  

0. You'll be greeted by a JupyterHub login page:
<p align="center">
![](https://raw.githubusercontent.com/Hua-Zhou/JSM2018-CE18C/master/jupyterlab_login.png)
</p>
Your username is initial of your first name + your last name. For example, if your name is `Joe Bruin`, then your username is `jbruin`. Your password is `jsmce18c`. Of course you can change password after you log in, e.g., by `passwd` command at Bash terminal.

0. After login, you will see the self-explanatory JupyterLab interface:
<p align="center">
![](https://raw.githubusercontent.com/Hua-Zhou/JSM2018-CE18C/master/jupyterlab_home.png)
</p>

0. To transfer the course materials to your home directory on the server, click `Terminal` in JupyterLab and type command 
```bash
git clone https://github.com/Hua-Zhou/JSM2018-CE18C.git
```
You should see the folder `JSM2018-CE18C` in the `Files` tab on the left of JupyterLab. Now youc can open any Jupyter notebooks in that folder and run the examples.

### Run Jupyter notebooks on your own laptop

This is **not** recommended for Julia beginners, since your software environment (OS, Julia version, pcckages versions, etc.) may be quite different. But if you want to run Jupyter notebooks on your own machine. Simply `git clone https://github.com/Hua-Zhou/JSM2018-CE18C.git` to sync the most recent lectures.



