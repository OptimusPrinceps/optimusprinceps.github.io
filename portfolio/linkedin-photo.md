---
layout: default
---

## Artificially Generating a LinkedIn Profile Picture
#### November 2022 --- August 2023

The last time I took a professional headshoot for LinkedIn was in 2020. I've changed a lot since then, and rather than taking another one I thought it would be both interesting and appropriate as a data scientist to try and use AI to generate one for me instead.

### Stable Diffusion 1.5 --- Nov 2022

My first attempt was in November of 2022 when I came across this [colab notebook](https://colab.research.google.com/github/InB4DevOps/diffusers/blob/main/examples/dreambooth/DreamBooth_Stable_Diffusion.ipynb) that handled all the heavy lifting of training a dreambooth model for Stable Diffusion v1.5. At the time I was impressed by the results! All of the images resided well within the realm of AI generated horror, but they did *somewhat* resemble me. 

Here is the image I ended up using on LinkedIn:

<img src="/assets/img/">


### Stable Diffusion 1.9 --- June 2023

My second attempt was ~8 months later in June of 2023 using Stable Diffusion v1.9. By this point, it was no longer tenable to use Colab as a free user as your virtual machine instance would get disconnected only after a few minutes (as soon as a paid user requested one). 

I set up a dev environment on my local machine and this time trained a Low-Rank Adaption Network on images of myself. This was quite a difficult and time-consuming process of carefully curating a training dataset (images had to be diverse and of high quality for good results), tuning training hyperparameters, and testing each checkpoint to find the best one. However, the end results were far and away more impressive than my first attempt. Here is the one I ended up using on LinkedIn:

<img src="/assets/img/linkedin/attempt_v2.jpg" alt="Second attempt at a LinkedIn profile picture">

An uncanny resemblance and somewhat difficult to tell that it is AI generated!

### Stable Diffusion XL --- August 2023
SDXL version coming soon!

