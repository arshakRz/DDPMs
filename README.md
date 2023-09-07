# DDPMs

<p align="center">
  <img src="figs/diffusion-models-forwardbackward_process_ddpm.png">
</p>

Applications of DDPMs in Medical Imaging: This code contains implementation of Denoising Diffusion Probabilistic Models with Classifer Free Guidance and DDIM sampler. One can use this implementation on any sort of data such as fMRI.

### Under Construction...
* **Warning: This project is still under development and it's not yet ready for real-world usage!** Please wait for the first official release... :)
* Soon the code would be available in the form of a library which could be installed using ```pip install``` command.
* more detail will be added after the first official release

Here are some results of the code on the MNIST dataset:

<p align="center">
  <img src="figs/download (2).png"">
</p>

This sample is generated without CFG and normal DDPM sampler (1000 steps):

<p align="center">
  <img src="figs/download (3).png" style="max-width: 270;">
</p>

Here is a GIF of a generated digit from pure gaussian noise with the setting above:

<p align="center">
  <img src="figs/output (5).gif" autoplay loop width="200" height="200" speed="5.0"></video>
</p>
