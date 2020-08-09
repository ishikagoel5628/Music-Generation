## Music-Generation

### Introduction
The current technological advancements have transformed the way we not only produce, but listen and work with music. And with the advent of deep learning it has now become possible to generate music without the need of working with instruments.This offers artists more creative freedom and ability to explore different domains in music.
Task: Our task here is to take some existing music data then train a model using this existing data. The model has to learn the patterns in music that we humans enjoy. Once it learns this, the model should be able to generate new_ music for us.

Now, what is music? In short music is nothing but a sequence of musical notes. Our input to the model is a sequence of musical events/notes. Our output will be new sequence of musical events/notes. In this case-study we have limited our self to single instrument music as this is our first cut model. 

### Data
You can download the MIDI files from the following site: 'http://www.midiworld.com/'

### Required Libraries
We use the following libraries:

* keras
* tensorflow
* music21
* pandas
* numpy

### References
https://towardsdatascience.com/how-to-generate-music-using-a-lstm-neural-network-in-keras-68786834d4c5
https://medium.com/@alexissa122/generating-original-classical-music-with-an-lstm-neural-network-and-attention-abf03f9ddcb4
https://www.analyticsvidhya.com/blog/2020/01/how-to-perform-automatic-music-generation/
