# Image-Compression-using-PCA
<h5>This project dives into Principal Component Analysis and how it can be used for reducing dimensions of complex features and choose specific dimensions 
  that maximize the variance </h5>
<h4> WHAT IS PCA?</h4>
<p>Imagine you have a large dataset with many variables. Visualizing and analyzing such data can be cumbersome. PCA comes in to **reduce the number of variables** while capturing most of the important information. ***It does this by creating a new set of variables, called principal components (PCs), that are linear combinations of the original ones.***

Basically what PCA does it reduces the dimensionality of any dataset by projecting the points on an arbitrary line and this line preserves the most variance. 

Why do we choose variance as the deciding factor?

PCA understands which part of our data is important only via calculating variance

- Variance can mathematically quantify the amount of information embedded within the data
- The greater the variance, the more the information. Vice versa.

How does variance associate with information?

Eg. 

Suppose that we are playing a guessing game with our friends. The game is simple. Our friends would cover their faces and we need to guess who’s who based solely on their height. Being the good friends that we are, we remember how tall everyone is.</p>
![image](https://github.com/anurag2506/Image-Compression-using-PCA/assets/142666721/c7bf5ff8-5346-4feb-b974-aca00d660a2a)


