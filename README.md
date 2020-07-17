# Fast Single Image Super-Resolution Using a New Analytical Solution for <img src="https://latex.codecogs.com/gif.latex? l_2-l_2 " />  Problems | Computer Vision

Centrale Lille | [Anas ESSOUNAINI][anas-email] | [Ali MOURTADA][ali-email]



***

## Description

This project aims to implement the algorithms described in the paper [Fast Single Image Super-Resolution Using a New Analytical Soltion for Problems](documents/paper_fast_super_resolution.pdf) in order to create __high resolution__ images from __low resolution__ ones.

## Repository Structure 

This repository consists in several directories with specific purposes:

- `image_super_resolution`: This directory contains the `image_super_resolution` Python Library developed exclusively for this project. It contains functions used within the scripts. To install the library, navigates to the project directory and run the following `pip` command:
  ```Shell
  cd [path_to_project_directory]
  pip install -e .
  ```
  1. `utils`: module with intermediate functions
  2. `analytical`: implementation of FSR Analytical algorithm
  3. `iterative`: implementation of ADMM algorithm
- `prototype notebooks`: preliminary notebook for the project.
- `images`: images on which we apply high resolution algorithms.
- `test_package`: test of the algorithm of a picture (lena for instance)

---
Please contact us [Anas ESSOUNAINI][anas-email], [Ali MOURTADA][ali-email] for any information, feedback or questions.

















[anas-email]: mailto:essounaini97@gmail.com
[ali-email]: mailto:mourtada.ali1997@gmail.com 