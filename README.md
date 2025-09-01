# Physics-Aware-GNN-Perovskites
Code for 'Rapid High-Throughput Design of ABX₃ Perovskites for Photodetector via Physics-Aware GNN and Transfer Learning
Physics-Aware Graph Neural Network for ABX₃ Perovskites

This repository contains code used in the manuscript:
"Rapid High-Throughput Design of ABX₃ Perovskites for Photodetector via Physics-Aware Graph Neural Networks and Transfer Learning".

The models are designed to predict band gaps and formation energies of inorganic ABX₃ perovskites, and include transfer learning from a large-scale inorganic crystal dataset.

Contents

ml-bandgap.py — Training and evaluation code for band gap prediction.

ml-energy.py — Training and evaluation code for formation energy prediction.

ml-finetuning-bandgap.py — Transfer learning script for band gap (fine-tuning on ABX₃ subset).

ml-finetuning-energy.py — Transfer learning script for formation energy (fine-tuning on ABX₃ subset).


Data

Pretraining dataset: Materials Project (retrieved via API).

Fine-tuning dataset: ABX₃ perovskites curated from the Materials Project database.
