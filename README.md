<p align="center">
    <!-- ![AstroWelcome](/DesignAssets/Ai/LogoMain@2x.png | width=400) -->
    <img width="50%" src="https://github.com/astroDimitrios/AstronomyClass/blob/main/DesignAssets/Ai/LogoMain%402x.png">
</p>

# Astronomy and Python Coding Activities

**NEW DOCS** - [astropython.com](https://www.astropython.com)
Slowly updating the new docs! - The most complete info about each individual activity will likely remain in the individual activity README's.

YouTube Channel:

My channel [astroDimitrios](https://www.youtube.com/channel/UCf8Sg-cgLNubyCM5Em8eDZg/featured) has videos of some activities and challenges as well as beginner intro videos:
https://www.youtube.com/channel/UCf8Sg-cgLNubyCM5Em8eDZg/featured

## Intro

This directory contains code on various Astronomy topics.

Each code has a teacher version with all outputs. These have the suffix Teacher. The student file is much smaller as it is missing the outputs and has code completition tasks for the students to complete.

At the start of the code is the **Aim** of the activity along with a **Predict** section which encourages the students to think about the topic before starting the activity.

The goal of the coding activities is mainly to **process** and **visualise** data and **extract physical insights** from them (as described in the AAPT report below). Although by performing the activities students will inevitably also learn debugging, how to convert theory/models into code, and how to present data formally in a document or presentation.

The outputs (figures etc) were designed to be a starting point for my students to put their own data and visualisations in their reports and presentations. My hope is this will promote a deeper understanding of the topic and better engage the students/encourage ownership and pride in their work.  

Some are best done in pairs like the introduction activities AstPy1 and AstPy2. Activities are designed to take at most an hour with some taking an hour and a half (AstPy4 and AstPy6 for instance).

Folders starting with a ***C*** are the Astronomy and Python challenges that anyone can participate in. I will try and make them at least bi-monthly. Maybe less over the summer and new year. My solutions will be added to the folder after the end of the challenge.

**NOTE** - Sometimes when I update a interactive notebook with corrections I forget about the normal .py version so it's not the most up to date.  

**Inspiration taken from:**

Adam LaMee - Scientific Computing Resources [https://adamlamee.github.io/CODINGinK12/](https://adamlamee.github.io/CODINGinK12/)    
Brown & Wilson, Ten quick tips for teaching programming, PlosCompBiol, [https://doi.org/10.1371/journal.pcbi.1006023](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1006023)  
American Association of Physics Teachers (AAPT), [Computational Physics Report](https://www.aapt.org/Resources/upload/AAPT_UCTF_CompPhysReport_final_B.pdf)  
PICUP, Integrating computing into physics, [https://www.compadre.org/PICUP/webdocs/About.cfm](https://www.compadre.org/PICUP/webdocs/About.cfm)  
astronomycenter resources, [https://www.compadre.org/astronomy/index.cfm](https://www.compadre.org/astronomy/index.cfm)

## How to run the code

<p><strong>NEW: </strong>You can now test some of the activities on our JupyterHub. Sign up <a href="https://hub.astropython.com/hub/signup">here</a> with a username and password then head over to <a href="https://hub.astropython.com/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2FastroDimitrios%2FLaunch&urlpath=lab%2Ftree%2FLaunch%2FWelcome.ipynb&branch=main">hub.astropython.com</a> and log in! (It's important to use the second link after signing up so you get sent to the Welcome document)

The welcome document has links which pull the activities you want to try from my GitHub. If something doesn't work please let me know! The server is built for my students so it can only handle 20-30 people at a time. If you do test out some of the activities let me know what you think.</p>

**NOTE:** The server may go down periodically. If you want to keep your work please download it to your local computer, do NOT assume it is safe forever on the hub. 

**Alternate ways of running notebooks**

The .ipynb files can be run my going to https://jupyter.org/try.  
Click on **Try JupyterLab** and wait for it to load.  
Upload the **.ipynb** file using the Upload File button (little upwards arrow in the top right).

Or you could install JupyterLab on your local machine.

The **.ipynb** files contain tasks for students. The Teacher **.ipynb** file contains the solutions.

**NOTE** - Sometimes there is a **.py** file with solutions and code to create more complex figures. I have NOT checked that these will run on JupyterLab. They were used to test my code before creating the interactive JupyterLab Notebooks.

## Inside each folder

Each folder contains the following:

* **.ipynb** - An interactive python file
* **Teacher.ipynb** - An interactive python file for teachers will solutions
* **.py** - A normal python file used for testing, or to perform other tasks not possible in a notebook
* Any **inputs** required to run the code
* Any **products** from the code (ouput images etc.)

## Assignment grading

**nbgrader**

[nbgrader](https://nbgrader.readthedocs.io/en/stable/index.html) is a tool to make assignments out of notebooks and mark them.

The **source** and **resources** files contain nbgrader versions of **AstPy-1**.
The gradebook file is also generated by nbgrader.

At the moment I have limited use for nbgrader assignments so there most likely won't be nbgrader versions of all notebooks.

## Data

There is now a ***Data*** directory where all data is stored. I will continue to keep all data files needed in their respective assignment directories as well.

# Table of code contents

Difficulty based on a three star system. Bear in mind all of these can be adapted to make them harder or easier!

AstPy Number | Difficulty | Description     | Data Files  | Comments
------------ | ---------- | -------------   | ----------- | --------
1 | :star: | Introductory Activities || 10 Intro Activities (2 fully guided)
2 | :star::star: | Intermediate introductory activities
3 | :star::star: | Stellar Fusion | Nuclear masses and binding energies (csv) |  Binding energy anim and calcs including coulomb potential well.
4 | :star: | Solar Images | Various SDO HMI and AIA FITS | Getting and potting SDO/SOHO Images.
5 | :star: | Solar Radiation | | Blackbody rad, Wien's law etc. Effective temperature of planets.
6 | :star::star::star: | Sunspots | SDO HMI Fits | Calculation of solar rotation period (interactive and automatic). Sunspot identification and sunspot tracking (automatic).
7 | :star::star::star: | Lunar Surface | LOLA DEM, LOLA Raw Topographic Data for Catalan Crater | Annotating your image of the moon from a telescope. Calculating resolution, crater heights and diameters. Comparing to Lunar Reconnaissance Orbiter (LRO) and Lunar Orbiter Laser Altimeter (LOLA) data.
8 | :star: | Planets | Orbital data, density, radius, mass etc. | Comparing planets by looking at data from the NASA Planetary Factsheet such as mass and radius etc. Looking briefly at exoplanet detection and observational bias.
9 | :star: | Planetary Interiors | Structure of the planets csv and chemcial composition of the Earth csvs. | Visualising the interiors of planets, visualise the chemical composition of the Earth's interior.
10 | :star::star: | Planetary Atmospheres | Chemical composition of planetary atmospheres. Exobase altitudes and temperatures (with escape velocities).  | Visualising and comparing the chemical composition of planetary atmospheres. Calculating whether a planet can hold onto a gas using escape velocities and kinetic theory.
11 | :star::star: | Earth's Heat| Geothermal gradient data and pressure data.  | Visualise the thermal gradient of the Earth. Model the geotherm of the lithosphere. Calculate energy transfer via conduction and latent heat.
12 | :star::star: | Earth's Atmosphere | Data to construct the international standard atmosphere (ISA) model. | Visualising the temperature, pressure, density, and speed of sound variation with altitude using the ISA model.
13 |  | Martian Surface | | COMING SOON!
14 | :star::star: | Planetary Rings | Data on the ring structure for all gas giants and data on their moons. | Visualising the ring structure of Saturn and the other gas giants. Calculating roche limits for some moons.
15 | :star::star::star:+ | Ring Dynamics | Data on Saturns moons. | Visualising the Roche limit with an N-body simulation. Calculating the locations of mean-motion resonances. Looking at bending and density waves, and the effects of shepherd moons.

# Challenges

A folder with a C then a number (C001 for instance) is one of the astronomy and python challenges!
Well my solution to it anyway.

Challenge Number | Date | Description     | Data Files  | Comments
------------ | -----------| -------------   | ----------- | --------
1 | 2020 June | Calculate the time between when a planet is at its closest to the Earth and when a planet is at its furthest from the Earth. || My solution is for Mars!
2 | 2020 Summer | Create a program to track sunspots across the face of the Sun automatically. || Solution in AstPy-6
3 | 2020 Autumn | How much older would you be if you stayed on Earth instead of travelling to Alpha Centauri at a) warp 5? or b) sublight speed? | | Solution on Youtube! [Here](https://www.youtube.com/watch?v=wGmS2CCaKxg)
4 | 2020/21 Winter | Earth has one Moon, Mars two, and Tatooine three! If Mars and Tatooine had oceans of water on them what would the tides be like? | |

# Specials

A folder with an S then a number (S001 for instance) is a special activity.

Special Number |  Description  | Data Files  | Comments
------------ | -----------| -------------   | ----------- 
1 | Celebrate the landing of the Mars 2020 Perseverance Rover by calculating launch windows to Mars with a Hohmann transfer orbit. | Ecliptic longitude and distance data for Earth and Mars | Also includes a notebook which makes the Hohmann transfer rover gif [here](https://github.com/astroDimitrios/Astronomy/blob/master/Code/S001%20-%20Mars%202020%20Launch%20Windows/GIF%20Files/social.gif).
