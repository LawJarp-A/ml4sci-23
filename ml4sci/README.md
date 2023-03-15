# Machine Learning for Science (ML4SCI)

* [Gsoc page](https://summerofcode.withgoogle.com/programs/2022/organizations/machine-learning-for-science-ml4sci)
* [Ideas page](https://ml4sci.org/gsoc/2023/summary.html)
* [Pre-req](https://docs.google.com/document/d/1lWTSASnVICm_4Zof7wr6_LkS24P_Z8TR1px_tctemQI/edit?usp=sharing)
* Socials
  * [Gitter](https://matrix.to/#/#ML4SCI_general:gitter.im)


# Project: DeepLense
* **What is dark matter?**
  * Dark matter is a form of matter that does not interact with light or any other form of electromagnetic radiation, making it invisible to telescopes and other instruments that rely on detecting such radiation. Its existence is inferred from the gravitational effects it has on visible matter, such as stars and galaxies. The evidence for dark matter comes from observations of the dynamics of galaxies and clusters of galaxies, which suggest that they contain far more matter than can be accounted for by visible matter alone. The nature of dark matter is still unknown, but it is thought to make up about 85% of the matter in the universe.
* **If we cannot see dark matter, how do we know it exists??**
  * Although we cannot see dark matter directly, its presence can be inferred through its gravitational effects on visible matter. One way that astronomers have detected the existence of dark matter is by observing the rotation curves of galaxies. According to the laws of gravity, the outer parts of a galaxy should rotate more slowly than the inner parts, but observations have shown that the outer parts of galaxies rotate at similar speeds to the inner parts. This suggests the presence of an invisible, massive object, which we now know is dark matter.
  * Other evidence for dark matter includes gravitational lensing, where the gravity of a massive object, such as a galaxy cluster, bends the path of light from more distant objects behind it. The amount of bending indicates the amount of mass present, and in many cases, the amount of visible matter is not sufficient to explain the observed bending. This again suggests the presence of invisible matter, i.e., dark matter.

## Paper 1: Decoding Dark Matter Substructure without Supervision
### Brief
The paper "Decoding Dark Matter Substructure without Supervision" discusses the use of unsupervised machine learning techniques to infer the presence of substructure in dark matter halos using galaxy-galaxy strong lensing simulations. The identity of dark matter remains elusive, and while many proposed candidates may turn out to be dark matter, it is equally likely that the correct physical description has yet to be proposed. Therefore, machine learning can help physicists gain insight into the dark sector from a theory agnostic perspective. In this paper, the authors demonstrate that unsupervised machine learning algorithms can produce nearly instantaneous results at the inference stage, making them a promising approach to identifying substructure in dark matter halos. The authors also highlight the differences between supervised and unsupervised approaches and the advantages of the latter, which do not require a labeled training set or a priori model assumptions.
## Paper 2: Deep Learning the Morphology of Dark Matter Substructure
### Brief
The article discusses the challenges of detecting dark matter, which is believed to be a weakly interacting massive particle (WIMP) but has so far evaded detection. The article suggests considering alternative models of dark matter, such as condensate models, which could form vortices that could be detected through strong gravitational lensing images. The article proposes using machine learning methods, such as a convolutional neural network, to classify substructure in the images and distinguish between different types of dark matter. This theory-agnostic approach could enhance our understanding of dark matter and potentially lead to its detection.
## Paper 3: 
### Brief
This is a scientific paper on the use of domain adaptation for simulation-based dark matter searches using strong gravitational lensing. The authors discuss the challenges in identifying dark matter based on astrophysical or cosmological signatures and how machine learning can be used to extract these signals. However, machine learning models trained on simulations are expected to lose accuracy when applied to real data, and domain adaptation can serve as a bridge between simulations and real data applications. The authors demonstrate the power of domain adaptation techniques applied to strong gravitational lensing data with dark matter substructure and show that it can significantly mitigate the losses in the model performance. This technique can help domain experts build and apply better machine learning models for extracting useful information from strong gravitational lensing data expected from the upcoming surveys.
## Pre - Requisites

### Task 1 

**Task**: Build a model for classifying the images into lenses using PyTorch or Keras. Pick the most appropriate approach and discuss your strategy.


**Dataset Description**: The Dataset consists of three classes, strong lensing images with no substructure, subhalo substructure, and vortex substructure. The images have been normalized using min-max normalization, but you are free to use any normalization or data augmentation methods to improve your results.

**Evaluation Metrics**: ROC curve (Receiver Operating Characteristic curve) and AUC score (Area Under the ROC Curve) 


#### What is strong gravitational lensing?
Strong gravitational lensing is a phenomenon predicted by Einstein's theory of general relativity in which the gravitational field of a massive object, such as a galaxy or a cluster of galaxies, bends the path of light from a more distant object, such as a quasar or a galaxy, behind it. This bending causes the distant object's light to be magnified and distorted into multiple images or arcs, forming a "gravitational lens". Strong gravitational lensing occurs when the lensing object is massive enough and positioned in just the right way to produce multiple, highly distorted images of the background object. Studying strong gravitational lensing can provide important insights into the distribution of mass in the lensing object and the nature of dark matter.

