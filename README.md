# Comparative Study of Non-Invasive Anemia Detection: RGB Analysis of Anterior Conjunctiva versus CIELAB Features from Palm Images using Artificial Neural Networks

This project presents a comparative study of two non-invasive anemia detection approaches using image processing and Artificial Neural Networks (ANN).

## Methods Compared

* **Anterior Conjunctiva RGB Analysis**

  * Extracts mean RGB values from eye conjunctiva images.
  * Uses ANN for binary anemia classification.

* **Palm Image CIELAB Analysis**

  * Converts palm images to CIELAB color space.
  * Uses mean L*, a*, and b* values as features.
  * Uses the same ANN architecture for fair comparison.

## Results

| Method          | Accuracy |
| --------------- | -------- |
| Conjunctiva RGB | 81%      |
| Palm CIELAB     | 93%      |

The palm-based CIELAB approach achieved better performance and showed greater robustness for non-invasive anemia screening.

## Authors

Ganesh M, Manjiswari J, Komali Priya P, Saladi Saritha, Yepuganti Karuna

## Paper

The complete research paper is available in this repository.
