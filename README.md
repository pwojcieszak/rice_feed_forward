# rice_feed_forward
Rice grain dataset classification using scikit-learn library and Feed Forward neural network model

The analyzed data comes from the publicly available dataset "Rice (Cammeo and Osmancik)" [Link to dataset](https://colab.research.google.com/corgiredirector?site=https%3A%2F%2Farchive.ics.uci.edu%2Fdataset%2F545%2Frice%2Bcammeo%2Band%2Bosmancik).

The dataset consists of physical measurements made on two classes of rice grains. Our goal is to teach the model, based on the available data, how to distinguish between classes of grains, so that it is able to correctly identify new instances.

The dataset consists of:

- 3810 examples,
- 2 classes: Cammeo and Osmancik,
- 7 attributes: area, perimeter, major axis length, minor axis length, eccentricity, convex area and degree of filling,
- 1630 examples are of class Cammeo and 2180 of class Osmancik.

The notebook includes data visualization, model tuning and final performance evaluation.
