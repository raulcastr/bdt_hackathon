# #bdtHackaton 
#### Dataset for the Data Science individual challenge (12-13 June 2021)

The dataset for this challenge is the 'particles.csv' file, with a shape of (127321 rows x 12 columns).

|alpha_1|alpha_2|alpha_3|beta_1|beta_2|beta_3|gamma_1|gamma_2|gamma_3|theta|noise|Particle|
|-------|-------|-------|------|------|------|-------|-------|-------|-----|-----|--------------|
|       |-59.730|396.928|9.7617|-137.5|159.59|-137.55|53.9309|154.713|-232.|21.23|3|
|...    |...    |...    |...   |...   |...   |...    |...    |...    |...  |...  |...| 


This dataset is composed of 10 columns showing the data obtained by the LHC sensors after the collision of particles. In particle physics, colliders are used as research tools: they accelerate particles to very high kinetic energies that allow them to collide with other particles. Analysis of the by-products of these collisions provides scientists with good evidence of the structure of the subatomic world and the laws of nature that govern it. Many of these by-products are produced only by high-energy collisions and decay after very short periods of time. Therefore, many of them are difficult or almost impossible to detect in any other way.

The eleventh column is the average noise measured by all the sensors.

And the last column is the one that represents the elemental particle that has been created by the high-energy collision of particles. This is the column that your algorithm will have to be able to predict.

![Alt Text](https://github.com/nuwe-io/bdt_hackathon/blob/main/images/atoms.gif)

Where each class from 0-7 corresponds to one of the elemental particles:

|Particle      |Name|
|--------------|----|  
|       0      |  Leptons |
|       1      |  Quarks |
|       2      |  Gluons |
|       3      |  Electroweak bosons |
|       4      |  Graviton |
|       5      |  Higgs boson |
|       6      |  Antileptons |
|       7      |  Antiquarks |


![Alt Text](https://github.com/nuwe-io/bdt_hackathon/blob/main/images/flash.jpg)

This dataset has been specially created for this challenge. Now let's have fun! :sunglasses:

