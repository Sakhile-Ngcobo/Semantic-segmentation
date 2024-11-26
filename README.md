# Semantic-segmentation

 The purpose of this project was to track the nematode. The challenge with tracking this object was the nematode has a transparent body which is very similar to the fluid in which it is placed on. To address this we had to build a CNN model that can effectively discriminate between the object body and fluid, also keeping in mind that the object is in motion presenting further complications especially when the object twirls or crosses its body. 

Since the object was captured in a lab setting through video. The aim was to first create a script that extract images from the video frames, manually creating ground truths by drawing boundaries around the object's body. Later on feed those ground truths to the model so it can learn or predict how to create its own ground truths.

