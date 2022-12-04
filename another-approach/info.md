# Another Approach

This folder contains the model and all the related material (tests and images), which follows a different approach to the main one, in fact in this case the augmentation phase is carried out every time within the model, the advantage is that we can have a larger dataset, but the disadvantage is that the maximum batch size is 32 samples.

And as also explained in the paper in the End-to-End architecture of Contrastive Learning models the batch size is fundamental, for this reason this approach has been discarded.
This consideration is demonstrated by the test plots in which the maximum accuracy achieved by the classifier in the downstream task is approximately 46%.