# Comfyroll Workflow Templates
__A collection of workflow templates for use with Comfy UI__

These workflow templates are intended as multi-purpose templates for use on a wide variety of projects.
They can be used with any checkpoint model.

### Installation
* clone the workflows
  *  cd to ComfyUI\custom_nodes
  *  git clone https://github.com/Suzie1/Comfyroll-Workflow-Templates.git
* install __WAS Node Suite__ v2.0 or higher from https://civitai.com/models/20793/was-node-suite-comfyui
* install __Comfyroll Custom Nodes__ from https://github.com/RockOfFire/ComfyUI_Comfyroll_CustomNodes

Optional resources:
* install __Detail Tweaker LoRA__ from https://civitai.com/models/58390
* install __4x-UltraSharp__ from  https://mega.nz/folder/qZRBmaIY#nIG8KyWFcGNTuMX_XNbJ_g
* install __ControlNet models__ from https://civitai.com/models/9251/controlnet-pre-trained-models
* install __ControlNet diff models__ from https://civitai.com/models/9868/controlnet-pre-trained-difference-models

It is recommended to install and update custom nodes using [ComfyUI Manager](https://github.com/ltdrdata/ComfyUI-Manager)

### On First Use 
Varies by template:
* select models and VAE
* add a default image in each of the Load Image nodes (purple nodes)
* add a default image batch in the Load Image Batch node
* select upscale models
* select ControlNet models
* select a default LoRA in each Load LoRA node
* do a test run
* save a copy to use as your template

### List of Templates
* Simple Template
* Intermediate Template
* Advanced Template
* Pro Template

### Simple Template Features
* Txt2Img, Img2Img
* Hires Fix and latent upscaling
* image upscaling

![Simple Template](https://github.com/Suzie1/Comfyroll-Workflow-Templates/blob/main/workflow_images/Comfyroll_Simple_Template.jpg)

### Intermediate Template Features
* Txt2Img, Img2Img
* ControlNet diff models
* image borders
* ControlNet for adding noise
* Hires Fix and latent upscaling
* image upscaling

![Intermediate Template](https://github.com/Suzie1/Comfyroll-Workflow-Templates/blob/main/workflow_images/Comfyroll_Intermediate_Template.jpg)

### Advanced Template Features
* Txt2Img, Img2Img or Img2Img batch
* up to 3 LoRAs (these can be toggled On/Off)
* ControlNet diff models
* image borders
* image upscaling
* up to 2 ControlNets or a ControlNet batch

![Advanced Template](https://github.com/Suzie1/Comfyroll-Workflow-Templates/blob/main/workflow_images/Comfyroll_Advanced_Template.jpg)

### Pro Template Features
* Txt2Img, Img2Img or Img2Img batch
* dual models
* dual prompts
* up to 5 LoRAs (these can be toggled On/Off)
* up to 2 ControlNets or a ControlNet batch
* ControlNet diff models
* image borders
* various noise options
* Hires Fix and latent upscaling
* image upscaling
* post-processing styles and enhancements

![Pro Template](https://github.com/Suzie1/Comfyroll-Workflow-Templates/blob/main/workflow_images/Comfyroll_Pro_Template.JPG)

### Tips
* each optional component can be bypassed using logic switches (red nodes)
* set the Load Image Batch to single-image when it is not being used
* the default setting on all switches is Off (1)
* Preview Image nodes can be set to preview or save image using the output_type
* use ComfyUI Manager to download ControlNet and upscale models
* if you are new to ComfyUI it is recommended to start with the simple and intermediate templates in Comfyroll Template Workflows
* at least 10GB VRAM is recommended for the Pro Template

### Resources

https://upscale.wiki/wiki/Model_Database

https://civitai.com/models/87609/comfyroll-custom-nodes-for-comfyui

https://github.com/RockOfFire/ComfyUI_Comfyroll_CustomNodes

https://civitai.com/models/20793/was-node-suite-comfyui

https://github.com/ltdrdata/ComfyUI-Manager

