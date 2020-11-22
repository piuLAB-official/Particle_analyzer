# How to use
_Before launching the software prepare you files to analyze into a folder named "Figure". Open on MATLAB browser the directory containing the Figure folder._

Steps || Description |
----------------------|------------|------
|![step1](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step1.png) | If no file is present in the list, click on **Update List** button. Select the image you want to analyze and click on **Load file**.
![step2](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step2.png) | Automatically you will be able to draw a line into the image. draw the line over the scale bar, its lenght will be used to convert pixel dimenstions to µm. Type the lenght in µm correspondent to the line you have drawn and click on **Set scale** button.
![step3](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step3.png) | You have now setup the scale and all measurement will be calibrated. If you want to change the lenght in µm you can do it by typing the new value and clicking on **Set scale**. If you need to correct the line over the image, reload the file as described in *Step 1*.
![step4](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step4.png) | Go to _ **Enhance** _ section, here you will binarize the image preparing it for the analysis. The resulting image will be used for the particles recognition. Use particular care during the image preparation, as every feature not present after these steps will not be seen during the image analysis.
![step5](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step5.png) | Select a treshold for the binarize step, then click on **Binarize** button. Repeat this process until the result cleary shows only the feature you want to measure. The resulting image will be used later to refine each particle. Use particular care during this step since every feature not present after it, will not be seen during the image analysis.
![step6](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step6.png) | **Open** button will reduce the noise by removing isle of _black_ pixel inside _white_ feature and viceversa. The value defines a treshold for the dimentions of the isle to remove. Repeat this process until the result cleary shows only the feature you want to measure. This image resulting after this step will be used only to isolate the particles in order to speed up the process, but not for the particles measure.
![step7](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step7.png) | Use **Complement** button to switch _white_ and _black_ pixels. Feature to measure have to be _white_. Use **Refine** button to furtherly clear the noise. 
![step8](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step8.png) | step 8
![step9](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step9.png) | step 9
![step10](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step10.png) | step 10
![step11](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step11.png) | step 11
![step12](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step12.png) | step 12
![step13](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step13.png) | step 13
![step14](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step14.png) | step 14
![step15](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step15.png) | step 15
![step16](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step16.png) | step 16
![step17](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step17.png) | step 17
![step18](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step18.png) | step 18
![step19](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step19.png) | step 19
![step20](https://github.com/piuLAB-official/Particle_analyzer/blob/main/HowTo_steps/step20.png) | step 20
