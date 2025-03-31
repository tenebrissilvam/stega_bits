# Bit Position Importance in Steganography

![изображение](https://github.com/user-attachments/assets/b89f7e9d-3498-4e07-b86c-d80b11206bae)

This project investigates the role of bit positions in steganography by comparing two approaches: **StegaStamp** and **Stable Signature**. The goal is to 1. determine which bit positions yield the best robustness when images are subjected to various distortions, and 2. explore the importance of different bit positions.

## Overview

Steganography is the art of hiding data within images. By exploring the importance of different bit positions, this research aims to:
- Enhance the robustness of hidden signatures against distortions.
- Provide insights for both designing new steganographic algorithms and developing countermeasures for steganalysis.

Please view the pdf with slides that showcase the main findings.

## Research and Findings

### Methods Compared
- **StegaStamp:**
- **Stable Signature:**

![изображение](https://github.com/user-attachments/assets/73375672-d3af-483b-8fce-5e2ee31b8ade)

### Key Insights
- **Bit Position Sensitivity:**  
  Certain bit positions prove more resilient to distortions than others, which is critical for maintaining the integrity of the hidden data.
- **Robustness Evaluation:**  
  Comparative experiments indicate that while both methods have their merits, the *Stable Signature* approach tends to perform better under higher levels of distortion.
- **Performance Metrics:**  
  Detailed analysis of signal-to-noise ratios, error rates, and distortion impact provides guidelines for choosing optimal embedding strategies.

For an in-depth look at the experimental results, refer to the Jupyter Notebooks included in this repository:
- `stegastamp_distortions(2).ipynb`
- `stable_signature_distortions(4).ipynb`

Additionally, the full presentation is provided in the repository as **StegaStamp vs Stable Signature.pdf**.

## Data

The experiments use a subset of the MIRFLICKR dataset. To obtain the data, please visit:
- [MIRFLICKR Dataset Download](https://press.liacs.nl/mirflickr/dlform.html)

## References

1. [The Stable Signature: Rooting Watermarks in Latent Diffusion Models. Pierre Fernandez, Guillaume Couairon, Herve J´egou´, Matthijs Douze, Teddy Furon,] (https://arxiv.org/pdf/2303.15435)

2. [StegaStamp: Invisible Hyperlinks in Physical Photographs Matthew Tancik. Ben Mildenhall, Ren Ng University of California, Berkeley,] (https://arxiv.org/pdf/1904.05343)

3. [WAVES: Benchmarking the Robustness of Image Watermarks. Bang An, Mucong Ding, Tahseen Rabbani, Aakriti Agrawal, Yuancheng Xu, Chenghao Deng, Sicheng Zhu, Abdirisak Mohamed, Yuxin Wen, Tom Goldstein, Furong Huang] (https://arxiv.org/pdf/2401.08573)

4. [HiDDeN: Hiding Data With Deep Networks. Jiren Zhu, Russell Kaplan, Justin Johnson and Li Fei-Fei,] (https://arxiv.org/pdf/1807.09937)

