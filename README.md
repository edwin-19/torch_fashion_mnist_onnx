# Torch Fashion Mnist Classifier
The idea for this repo was just to test out how to make a simple CNN with torch, you can download the fashion mnist library online and test it out your self, at the same time i wanted to run ONNX and checked the results would be any different turns out no at least for the simpler layers not sure about the more custom or complex layers

- Update 27/8/2024
- Added training code for pytorch lightning 

## Repo contains
- Training code and validation
- Torch single inference
- ONNX single inference
- Added batch inference to torch
- Added resnet50 backbone for trasnfer learning
- Added feature visualization using PCA and tSNE

## Things to do
- [x] Add backbone such as resnet or mobile net
- [x] Convert to ONNX and check the results
- [x] Use tSNE, PCA to visualize the classification results (check if any outliers)
- [x] Added pytorch lightning training code for comparison