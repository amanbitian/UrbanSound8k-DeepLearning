# UrbanSound8k-DeepLearning
## We will analyse and classify 7.09GB of Audio clips of lenght <=4S of urban sounds
from 10 classes: `air_conditioner`, `car_horn`, `children_playing`, `dog_bark`, `drilling`, `enginge_idling`, `gun_shot`, `jackhammer`, `siren`, and `street_music`  

![tempsnip](https://user-images.githubusercontent.com/86042628/142737708-20fd6e4f-15dc-4b40-a666-98edb31945ad.png)

Distribution of data as per class: This seems a balanced dataset

## So why librosa?
1. librosa Try to **converge the signals** i.e it will make one signal which is mono
2. It represents a audio signal with **normalized pattern**
3. It is able to see the sample_rate and **by default it converts the sample_rate to 22050**  
[Read more on Librosa](https://librosa.org/doc/latest/tutorial.html)  
Data loading with librosa ( click above link for more details
![libosa](https://user-images.githubusercontent.com/86042628/142738227-b83e9def-08b3-4c38-b6be-21d6ead232e7.PNG)

# We can solve this with CNN too
![spectogram](https://user-images.githubusercontent.com/86042628/142742618-a7fc4976-08b3-4eae-a6b4-5ba9868762ac.PNG)

**Spectogram** is `visual representation of all the frequencies over time`
* y-axis is frequency in **hertz**
* x-axis is the **time**
* **color** represents the magnitude or amplitude: The `brighter the higher`.
* It's usally in `decibels`
* We can convert a waveform to spectrogram which is technically equivalent to an image
