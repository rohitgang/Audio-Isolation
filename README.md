# Audio-Isolation

## Scenario 

Imagine you recorded an audio clip on your phone right now. You are standing in a crowded area and recording yourself singing. You go home, load the audio clip on your audio mixing app. 
You want to lower the background sounds, but you are unable as you recorded it on your phone and the audio clip does not have the information of the different sounds.  

But fear not, because you have at your disposal a program which can identify the different audio sources in your audio clips and isolate the different sounds from the different sources. This gives you control of all the sounds in that audio clip. Now you can remove audio sources from the clip, lower the volume of the sounds from different audio sources. 

So you can sing even if you are sitting in a coffee shop, go home and refine the audio clip by removing specific sounds from your audio.

***

## Technical Language

This will be a deep learning model to which when an audio clip is fed in, it can identify the different type of sounds in the audio clip. So the audio clip goes from being one waveform to multiple waveforms each of which corresponds to a sound in the original audio clip.

The deep learning model will be tasked with understanding the audio clip and then being able to make out different sounds in the clip. How?? Thinking of the input data to the model, it will be the audio clip ’s frequencies ? I have never dealt with audio clip, so no clue on this. 

* Autoencoders are used to regenerate the input. In the hidden layers, can we do something which splits the audio (frequency?pitch?) and then recreates the input but with all the different audio waves?

* If we apply PCA to the audio file (how?), and we take the first principal component, will we get the (freq?pitch?) of the sound which is most dominant in the audio clip?
