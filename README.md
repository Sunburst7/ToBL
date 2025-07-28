# ToBL
The official code for the paper "ToBL: Towards Better Labeling for Open World SAR Object Detection" will be released soon.

# Abstract
Although Synthetic Aperture Radar (SAR) object detection has achieved impressive performance in recent years, existing methods are trained on a predefined closed set and therefore cannot recognize objects of novel categories. Openworld object detection that seeks to detect and classify bothbase and novel anomalies becomes a feasible solution. However,speckle noise and the inherently indistinct object boundaries inSAR imagery lead traditional open-world detection approachesto produce numerous background false positives and classification errors. To address these challenges, we propose a newframework called ToBL, to obtain better labels for open worldSAR detection. Specifically, to deal with location ambiguity,we define a Scatter Points Based Heatmap Regression Module(SHRM) to enhance the model’s object localization capability.The heatmap is modeled by a Gaussian Mixture Model tosuppress the background clutter. To address categorization confusion, we then design Dual Supervised Pseudo-Labeling (DSP)to improve the alignment of pseudo-labels with unknown-classinstances. We evaluate our method on multiple SAR objectdetection benchmarks in open world settings, demonstrating thatTOBL outperforms all existing OWOD methods, particularly onunknown-class metrics (recall up to 70.5%). The code is availableat: https://github.com/Sunburst7/ToBL


# 📑News
* [Todo] Release the code.


