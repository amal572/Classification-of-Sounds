# machine_learning_project
I am trying to classify some sounds (breaking glass sound - Shooting sound), I used ESC-50 dataset you can download it from  https://github.com/vbelz/audio_classification, which is a group of sounds but it has not the Shooting sound so I collected some sound files then I have 532 wave files.

<li>I get the window simple form the sound file then I start to extract features from the audio using some features in the time domain (zero crossing rate, short-term energy) and from the frequency domain (short-term entropy of energy, spectral centroid and spread, spectral entropy, spectral flux, spectral roll-off,  and the first 13 feature from MFCCs)</li>
<li>then I get the median and  absolute_deviation for all windows for each sound file</li>
<li>then I use some model machine learning to classify the sound after some preparation and visualization of the data  then I use the best model (Gradient Boosting) to classify the sound</li>

<h2> used libraries </h2>
<li> sklearn </li>
<li> seaborn </li>
<li> pandas </li>
<li> matplotlib.pyplot </li>
<li> numpy </li>
<li> python version than 3.6 </li>



