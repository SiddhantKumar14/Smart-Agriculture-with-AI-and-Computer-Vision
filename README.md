# Leaf-Age-Detection
An application involving computer vision, machine learning and basic image processing to detect the age of a leaf, by extension the ideal time to harvest a crop based on a single leaf photograph.

A very simple CNN (Convolutional Neural Network) is applied to create a binary classifier which detects whether the given leaf is a tomato leaf or not.
Training dataset - https://drive.google.com/file/d/1DVy0LyUUfJciyo7BUFm1sHKSRdTVJgjF/view
(Only the Healthy leaves section)

The first image, leaf.jpg is the sample image I used for measuring the digital length of the object (the leaf)
leaf2.png is the image used in the Yellowing rate detection program. It had to be cropped unnaturally since there were more than one objects in the image. 
An image with only one object need not be cropped.

The age detection dataset has been extracted from the given image using https://automeris.io/WebPlotDigitizer/ and prepared from https://www.researchgate.net/publication/237159745_The_growth_and_development_of_the_Leaf_in_tomato_Lycopersicon_esculentum_I_The_plastochron_index_a_suitable_basis_for_description
and
https://www.researchgate.net/publication/241869487_The_influence_of_light_intensity_and_leaf_age_on_the_photosynthetic_capacity_of_leaves_within_a_tomato_canopy
