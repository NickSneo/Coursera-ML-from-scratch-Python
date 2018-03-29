# Coursera Machine Learning Course from Scratch in Python
---
This repository contains the assignments of Coursera ML Course implemented in Python from scratch (except the SVM Assignment).

Initially, I did some assignments in Octave. But after 2 assignments, I didn't felt like I was implementing the algorithms because most of the code was already provided.
So I decided to do it in Python from scratch to understand these algorithms properly.
Even Gradient Descent is implemented manually (**nope, scipy.optimize.fmin_cg is not used**). It is vectorized (it took me some time to get used to vectorizing) so the training is done quickly.

Another reason for implementing from scratch was to learn Python. I was new to Python and needed some practice. What could be better than implementing the assignments in Python!

One of the challenge I faced a lot was visualization using matplotlib. Since I was new to matplotlib, creating visualizations like those in assignment's PDF took a lot of time. But it was all worth it, as writing code for visualization helped me not only in learning matplotlib for plotting but also gave me more understanding of these algorithms!

## Libraries
---
This is a list of libraries I used during assignments
* numpy
* matplotlib
* pandas (when the dataset is given in csv)
* scipy (only for loading the dataset from .mat files and using imread and imsave for kmeans assignment)
* scikit-learn (**Only in SVM**)

## Resources
---
Some resources (apart from libary docs) that helped me:
* Excellent matplotlib tutorials - https://www.youtube.com/playlist?list=PLNmACol6lYY5aGQtxghQTq0bHXYoIMORy
* https://github.com/kaleko/CourseraML
* http://www.johnwittenauer.net/machine-learning-exercises-in-python-part-1/
