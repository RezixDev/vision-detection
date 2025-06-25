# Vision Detection - How Computers see the World

I rememeber back in the Day i was impressed with some Tools like OpenCV or YOLO.

https://opencv.org/
https://pjreddie.com/darknet/yolo/

I thought that this would speed up the building of Robots or the creation of machines. Some years later, there was still no Robots walking on the streets. What a Bummer. Instead we've got GenAI Tools like ChatGPT or MidJourney. And... even better Multimodal Models. And they can also see stuff and interpret things.

But, we've got better. Let explore the new Landscape of Computer Vision and what is possibilities today.

SAM 2 (Segment Anything Model) v2
Page:
https://ai.meta.com/sam2/
Repository:
https://github.com/facebookresearch/sam2

Before we've got bounding boxes over a given Object. To classify one Object a lot of labelling was needed.
Today in the current landscape, with just some click's of a Mouse we are able to select what we want to focus on, and what should be ignored.

Unfortunatelly, SAM got some problems in keeping the tracking of the Objects in sync, but there did arrived an even better approach: SAMURAI
Showcase:
https://yangchris11.github.io/samurai/

Repo:
https://github.com/yangchris11/samurai

Paper:
https://arxiv.org/pdf/2411.11922

OWL SAM, Segmentation Mask via Text-Prompting:
https://huggingface.co/spaces/merve/OWLSAM


## How to replace Background in a given Image using SAM and Stable Diffusion

I guess this is the most simple example to showacase the use of SAM.

For the presentation we can use GUI Tools like:

ComfyUI
https://github.com/comfyanonymous/ComfyUI

Gradio
https://github.com/gradio-app/gradio

For example A1111 is based on Gradio:
https://github.com/AUTOMATIC1111/stable-diffusion-webui

Python Packages we are going to use are:
PyTorch, NumPy, transformers from the SAM Lib and diffusers from StableDiffusion.





If you are looking for an smaller Model (maybe because you don't have much of memory on your Device) an alternative could be SmolVLM

https://huggingface.co/blog/smolvlm




