# Comfyroll-Workflow-Templates
A collection of workflow templates for use with Comfy UI

This workflow template is intended as a multi-purpose template for use on a wide variety of projects. It can be used with any checkpoint model.

Prerequisites
* ComfyUI installation
* WAS Node Suite custom nodes, v2.0 or higher
* at least 10GB VRAM is recommended

Installation
* save the workflow on the same drive as your ComfyUI installation
* save the Custom Nodes from the download in your \ComfyUI\custom_nodes folder
* install WAS Node Suite from https://civitai.com/models/20793/was-node-suite-comfyui
* install Detail Tweaker LoRA from https://civitai.com/models/58390 (optional)

On first use
* select models and VAE
* select a default LoRA in each Load LoRA node
* select upscale models
* select ControlNet models
* add a default image in each of the Load Image nodes (purple nodes)
* add a default image batch in the Load Image Batch node
* do a test run
* save a copy to use as your template

Template Features
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

Tips
* each optional component can be bypassed using logic switches (red nodes)
* set the Load Image Batch to single-image when it is not being used
* the default setting on all switches is Off (1)
* Preview Image nodes can be set to preview or save image using the output_type
* use ComfyUI Manager to download ControlNet and upscale models
* if you are new to ComfyUI it is recommended to start with the simple and intermediate templates in Comfyroll Template Workflows

Resources
https://upscale.wiki/wiki/Model_Database
https://github.com/RockOfFire/ComfyUI_Comfyroll_CustomNodes
