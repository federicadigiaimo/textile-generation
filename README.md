# Textile Generation using Latent Diffusion Models
This repository contains the implementation of a toolkit for the semantic expansion and synthesis of textile textures, developed as part of a Master's Thesis in Computer Engineering at the University of Bologna.

##Project Overview
The project addresses the production bottleneck of textile assets in AAA game development. Traditional tiling often results in visible repetitions ("wallpaper effect"), while manual creation is costly and time-consuming.
The goal is to perform semantic upscaling from 256×256 source samples to 1024×1024 production-ready assets that are natively tileable (seamless) and structurally coherent.

##Key Features

    Dual-Pathway Framework: Adaptive generation strategies based on textile topology (Regular/Geometric vs. Irregular/Organic).

    Visual Guidance (IP-Adapter): Integration of image-prompt conditioning to control weave density and material identity, surpassing the limitations of text-only prompts.

    Native Tileability: Implementation of Noise Rolling and Circular Padding within the denoising loop to transform the latent plane into a toroidal surface.

    Latent Replication: A structured initialization strategy at 60% of the denoising process to expand resolution while preventing structural drift.

##Gemini ha detto

For your project's README, a professional and technical structure in English will highlight the engineering value of your research. Regarding your question about images, they are absolutely essential for a Computer Graphics project; you should include them to demonstrate the effectiveness of your "Native Tileability" and to prove the absence of the "wallpaper effect" [1].

Below is a suggested structure for your README.md:
Textile Generation using Latent Diffusion Models

This repository contains the implementation of a toolkit for the semantic expansion and synthesis of textile textures, developed as part of a Master's Thesis in Computer Engineering at the University of Bologna [1].
Project Overview

The project addresses the production bottleneck of textile assets in AAA game development. Traditional tiling often results in visible repetitions ("wallpaper effect"), while manual creation is costly and time-consuming [1].

The goal is to perform semantic upscaling from 256×256 source samples to 1024×1024 production-ready assets that are natively tileable (seamless) and structurally coherent [1].
Key Features

    Dual-Pathway Framework: Adaptive generation strategies based on textile topology (Regular/Geometric vs. Irregular/Organic) [1].

    Visual Guidance (IP-Adapter): Integration of image-prompt conditioning to control weave density and material identity, surpassing the limitations of text-only prompts [1].

    Native Tileability: Implementation of Noise Rolling and Circular Padding within the denoising loop to transform the latent plane into a toroidal surface [1].

    Latent Replication: A structured initialization strategy at 60% of the denoising process to expand resolution while preventing structural drift [1].

Technical Stack

    Model: Stable Diffusion v1.5 (Latent Diffusion Model).

    VAE Decoder: Fine-tuned MSE (ft-mse) variant for high-frequency detail preservation.

    Hardware utilized: NVIDIA Quadro P4000 (Pascal architecture).


Author: Federica Di Giaimo

Supervisor: Prof.ssa Serena Morigi

Co-supervisor: Paolo Zuzolo
