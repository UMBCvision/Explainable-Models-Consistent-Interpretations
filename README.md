# Explainable Models with Consistent Interpretations
Official PyTorch implementation for the AAAI 2021 paper 'Explainable Models with Consistent Interpretations'

Given the widespread deployment of black box deep neural networks in computer vision applications, the interpretability aspect of these black box systems has recently gained traction. Various methods have been proposed to explain the results of such deep neural networks. However, some recent works have shown that such explanation methods are biased and do not produce consistent interpretations. Hence, rather than introducing a novel explanation method, we learn models that are encouraged to be interpretable given an explanation method. We use Grad-CAM as the explanation algorithm and encourage the network to learn consistent interpretations along with maximizing the log-likelihood of the correct class. We show that our method outperforms the baseline on the pointing game evaluation on ImageNet and MS-COCO datasets respectively. We also introduce new evaluation metrics that penalize the saliency map if it lies outside the ground truth bounding box or segmentation mask, and show that our method outperforms the baseline on these metrics as well. Moreover, our model trained with interpretation consistency generalizes to other explanation algorithms on all the evaluation metrics.

## Code coming soon
