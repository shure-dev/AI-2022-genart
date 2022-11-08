# GAN for generating art
> Nov.2022 Artificial Intelligence, Home assignment


![Test Image 1](/results/results/real.png)
![Test Image 2](/results/results/2monet.png)
![Test Image 3](/results/results/3ukiyoe.png)
![Test Image 4](/results/results/4ceznne.png)
![Test Image 5](/results/results/5vangogh.png)

## Members
- Max Grönlund
- Joona Hytönen 
- Ville Juuti
- Juho Kemppainen
- Yusuke Mikami
- Simo Turunen

## How to run
1. Go file "AI-2022-genart/Joensuu-cycleGAN.ipynb"
2. Run notebook "AI-2022-genart/Joensuu-cycleGAN.ipynb"

## Abstract

Aim of this group project was to implement General adversarial networks (GAN) model architecture 
in our work where we suppose to transform pictures of our city (Joensuu) taken by us into art style like. 
GAN concept based on combination of two separated neural network. We used technique named CycleGAN image-to-image translation. 
This technique provides several different ways to manipulate images. We used the one which 
translates real photographs into specific art style. 

We used Deepnote for collaborator purposes. We pulled original CycleGAN code 
from Github repository to our Deepnote notebook, then for image transformation 
we first implemented pre-trained art-style models like Monet, Ukiyoe, Cezanne and Vangogh and 
then trained models with training data proposed by CycleGAN developing team. Image manipulation of 
real photographs was succeeded. The number of real images is 14. Collection of real Images and results
can be found in the 6. Experiments and results section.  

