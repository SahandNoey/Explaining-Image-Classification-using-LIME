# Explaining Image Classification Using LIME

Using **LIME (Local Interpretable Model-agnostic Explanations)** to explain image classification model.
**ResNet** is used as the pre-trained image classification model that LIME explains.
The aim is to provide clear, interpretable explanations for the predictions of image classifiers, enabling better understanding of what features influence a model's decisions.
LIME generates human-readable explanations by highlighting the regions of the image that were most influential in the model's prediction.


## Results

![Family](https://github.com/SahandNoey/Explaining-Image-Classification-using-LIME/blob/master/family_output.png)
![Penguin](https://github.com/SahandNoey/Explaining-Image-Classification-using-LIME/blob/master/penguin_output.png)


- _**The image in the center** highlights the **top 5 superpixels** that had the most positive influence on the model's classification decision (contributed the most to the prediction with the highest probability)._
- ***The image on the right** shows the **top 5 superpixels** that had the most negative impact on the model's classification decision (areas that detracted from or opposed the predicted class).*
