# Visual Attention Prediction Model Based on Prominence Maps, Machine Learning and Biometric Data

**Abstract**—This work is framed in the domain of software engineering. Specifically, it is situated in the subdomain of user interface evaluation. The context of the same comprises the phenomenon of visual attention and its evaluation through indicators that allow evaluating the quality of these interfaces. Specifically, it presents a model for the prediction of visual attention based on saliency maps, machine learning and biometric data. Its objective is to serve as a support to promote the usability of user interfaces. Experiments carried out with the eye tracker by the Institute for Cognitive Sciences at the University of Osnabrück and the University Medical Center in Hamburg-Eppendorf, among which free visualization tasks on user interfaces such as web pages, formed the input with which the model was developed. Its general structure consists of two elements: a convolutional neural network and Guided Grad-CAM (a convolutional layer visualization method). Biometric components were used to train the network: images whose size was set as a function of the foveal radius and the user's distance from the interface. The natural units of information (nats) were used as a measure to evaluate the accuracy of the model.

**Keywords**—Visual Attention, CNN, Biometric Components, Eye Fixations, Heat Map.

This repository contains the scripts used for visual attention prediction based on saliency maps, machine learning and biometric data.

The experiments were performed using the following data set: [DRYAD](https://datadryad.org/stash/dataset/doi:10.5061/dryad.9pf75)

The experiments were performed by using this [script](https://github.com/helbert-novoa/saliency).

Please cite our paper if you find it useful for your research.
@inproceedings{
  author = {H. Novoa and W. J. Giraldo and E. Granell and F. D. giraldo},
  title = {Modelo para la Predicción de la Atención Visual Basada en Mapas de Prominencia, Aprendizaje Automático y Datos Biométricos},
  year = {2021}
}
