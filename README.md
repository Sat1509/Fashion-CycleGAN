# CycleGAN: Unpaired Image-to-Image Translation

## Visual Domain Adaptation for Fashion and Cultural Transformation

This repository explores unpaired image-to-image translation using the CycleGAN framework, focusing on translating visual domains that differ semantically and stylistically.
The project emphasizes aesthetic fidelity, structural preservation, and cross-domain consistency, evaluated through both qualitative and quantitative lenses.

## Project Scope:

The study investigates CycleGAN’s ability to learn bidirectional mappings between stylistically contrasting domains, for example,  transforming traditional ethnic attire into contemporary western fashion, and vice versa.

### Core aspects include:

- Implementation of Cycle-Consistency Loss, Adversarial Loss, and Identity Loss.

- Evaluation of FID, PSNR, and SSIM metrics for image quality assessment.

- Detailed analysis of mode stability, color preservation, and texture transfer.

- Detailed qualitative analysis.

## Core Objectives:

- Assess whether CycleGAN can maintain semantic coherence under strong aesthetic contrast.

- Explore how cycle consistency enforces structural realism in visually dissimilar domains.

- Quantify improvements across training epochs using perceptual and statistical metrics.

- Interpret visual outputs through entropy trends, loss evolution, and discriminator–generator dynamics.

## Reproducibility:

The repository includes fully annotated notebooks with final outputs preserved to reflect the training trajectory and final visual quality.
Some intermediate weight files are excluded due to storage constraints, but all result cells, metric curves, and sample visualizations are retained for full transparency.

## Repository Structure:

CycleGAN_Style_Translation
├── notebooks/           # Annotated and result-preserved notebooks
├── reports/             # Final report and condensed summary
└── README.md            # Current file

## Reports:

- Detailed Report: Discusses training strategy, visual evaluation, and domain mapping stability.

- Condensed Report: Summarizes the detailed report for concise review.

Both reports are included under the reports/ directory for reference.

## Research Reflection: 

This project combines technical rigor with creative curiosity.
Each experiment, visualization, and analysis represents an effort to understand not just how generative models learn, but what they internalize when translating visual identity.
The process bridges algorithmic structure and artistic reasoning, to demonstrate that aesthetic translation can be examined through scientific precision.