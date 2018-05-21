# Deep Learning Intuition
ex: 
We want to check if two images are of the same face
Encode them into large (200-400) vectors and do a sum squared difference

## Triplicate learning
Select anchor, positive, negative
Anchor is the test image
Positive is an image of the same face
Negative is an image of a different face

You want to minimize the distance between anchor and positive
You want to maximize the distance between anchor and negative

Loss is the SSD(anchor, positive) - SSD(anchor, negative) + α
Once you have encodings you can cluster

Content layer is an early layer
Style layer is the last layer

You are trying to minimize SSD(content) + SSD(style)