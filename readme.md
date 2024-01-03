
# Collected notes from Patrick Debois on visual GenAI & ComfyUI

## Basics
- Using SDXL Turbo : https://comfyanonymous.github.io/ComfyUI_examples/sdturbo/

## Samplers
- Stable Diffusion Samplers: A Comprehensive Guide: https://stable-diffusion-art.com/samplers/

## Prompting
- Camera angles prompts : https://generativeai.pub/stable-diffusion-enables-the-control-of-camera-distance-and-angles-using-prompts-53ca4d1c9981
- GPT-4 + Stable-Diffusion = ?: Enhancing prompt understanding of text-to-image diffusion models with large language models : https://aihub.org/2023/06/26/gpt-4-stable-diffusion-enhancing-prompt-understanding-of-text-to-image-diffusion-models-with-large-language-models/


## Area composition
- Area Composition Examples : https://comfyanonymous.github.io/ComfyUI_examples/area_composition/
- GLIGEN model lets you specify the location and size of multiple objects in the image: https://comfyanonymous.github.io/ComfyUI_examples/gligen/

- Davemane42's Custom Node for ComfyUI , MultiAreaConditioning 2.4, MultiLatentComposite : https://github.com/Davemane42/ComfyUI_Dave_CustomNode
- ComfyUI: Area Composition, Multi Prompt Workflow Tutorial:  https://www.youtube.com/watch?v=NPkSa1y0GLM

## ControlNet
- Official ControlNet : https://github.com/lllyasviel/ControlNet
- What is ControlNet for Stable Diffusion? How to Use It? : https://lancerninja.com/controlnet-for-stable-diffusion/


- Creating AI Generated QR Codes Using Stable Diffusion And ControlNet: https://www.brainbyte.io/creating-ai-generated-qr-codes-using-stable-diffusion-and-control-net/

### Openpose
- SDXL-OpenPose and CodeFormer Workflow for Image Transformation:  https://blog.segmind.com/enhancing-image-quality-and-feature-retention-a-guide-using-sdxl-codeformer-and-openpose/
- CodeFormer: Robust Face Restoration and Enhancement Network - https://huggingface.co/spaces/sczhou/CodeFormer

- https://webapp.magicposer.com/
- https://openposes.com/

- Reposer = Consistent Stable Diffusion Generated Characters in ANY pose from 1 image - https://www.youtube.com/watch?v=SacK9tMVNUA


### Segmentation
- ComfyUI animation with segmentation: TrackAnything with SAM models : https://www.youtube.com/watch?v=HoTnTxlwdEw
- Stable Diffusion Inpainting with Segment Anything Model (SAM) : https://www.youtube.com/watch?v=CERvlvUvVEI
- (track-anything )Tutorial install Track-Anything for video in Windows:  https://www.reddit.com/r/StableDiffusion/comments/1306qap/trackanything_tutorial_install_trackanything_for/
- Track-Anything is a flexible and interactive tool for video object tracking and segmentation, based on Segment Anything, XMem, and E2FGVI: https://github.com/gaomingqi/Track-Anything
- color_coding_semantic_segmentation_classes :  https://docs.google.com/spreadsheets/d/1se8YEtb2detS7OuPE86fXGyD269pMycAWe2mtKUj2W8/edit?pli=1#gid=0

### Depth
- ComfyUI Post Processing - Depth and 3d Texture Generation -  https://www.youtube.com/watch?v=D2RpT4hQgak


## IP-adapter
- How the IP-Adapter Creator uses IPA in Stable Diffusion - https://www.youtube.com/watch?v=yrqT5FaBoIU
- The image prompt adapter is designed to enable a pretrained text-to-image diffusion model to generate images with image prompt:https://github.com/tencent-ailab/IP-Adapter


- IPAdapter hugginface : https://huggingface.co/h94/IP-Adapter
- ComfyUI reference implementation for IPAdapter models : https://github.com/cubiq/ComfyUI_IPAdapter_plus

Matteo Series:
- How to use IPAdapter models in ComfyUI: https://www.youtube.com/watch?v=7m9ZZFU3HWo
- IP-Adapter advanced features : https://www.youtube.com/watch?v=mJQ62ly7jrg
- Attention Masking with IPAdapter and ComfyUI:  https://www.youtube.com/watch?v=vqG1VXKteQg

- A1111: IP Adapter ControlNet Tutorial (Stable Diffusion) : https://www.youtube.com/watch?v=KHm5Q5TfNvE
- IP-Adapters are the New Killer App for Stable Diffusion in Comfy-UI : https://www.youtube.com/watch?v=ySqrmxl4jUE
- STOP wasting time with Style LORAs! Use THIS instead! How to copy ANY style with IP Adapter - https://www.youtube.com/watch?v=rOOhvZ-8Y0w

## AnimateDiff

- Animatediff perfect scenes. Any background with conditional masking. ComfyUI Animation :  https://www.youtube.com/watch?v=gDUeqCErjt4
- Animate your hero and take him/her to any scenario in ComfyUI: https://civitai.com/articles/2952/animate-your-hero-and-take-himher-to-any-scenario-in-comfyui

- Comfyui Animatediff plugin : https://github.com/ArtVentureX/comfyui-animatediff
- Official implementation of AnimateDiff : https://github.com/guoyww/AnimateDiff
- AnimateDiff for ComfyUI (old?) : https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved

- Unlocking the AI Frontier: Prompt Travel, ControlNet, and IP-Adapter in AnimateDiff : https://medium.com/ai-artistry/unlocking-the-ai-frontier-prompt-travel-controlnet-and-ip-adapter-in-animatediff-5d83a74ea766
- Introduction to the comfyUI + animateDiff Video2Video, AI Video Generation Workflow and Examples:  https://medium.com/@zhangp365/introduction-to-the-comfyui-animatediff-video2video-ai-video-generation-workflow-and-examples-f6cec78f640b

- Video to video with AnimateDiff prompt travel: https://stable-diffusion-art.com/animatediff-prompt-travel-video2video/
- Comfyui AnimateDiff v3 + LCM Video to Video - https://www.youtube.com/watch?v=XQLtI0KT2G0
- Ai Animation With ComfyUI: https://www.youtube.com/watch?v=YulLJ7ixBvg
- ComfyUI AnimateDiff Flicker-Free Inpainting : https://www.youtube.com/watch?v=eUJ06FWc3Go

- ComfyUI AnimateDiff Prompt Travel, ControlNets and Video to Video : https://www.youtube.com/watch?v=Drh8jpjE1yo
- Prompt travelling : https://www.andyhtu.com/post/animatediff-animation-control-how-to-prompt-travel-in-automatic111
- https://simpleaiart.com/sd-animatediff-cli-prompt-travel/
- https://github.com/s9roll7/animatediff-cli-prompt-travel

- AnimateDiff for Stable Diffusion WebUI : https://github.com/continue-revolution/sd-webui-animatediff#motion-lora

- Longer movies with AnimateDiff:  https://github.com/pixelatedpoets/longer-animatediff-movies


## Motion Lora
- Motion LoRAs in AnimateDiff : https://www.youtube.com/watch?v=rMOnq2he5dQ&list=TLPQMjkxMjIwMjPv9c0Nep2Qtw&index=3

## LCM Lora 
- Using LCM Lora for consistency + animatediff - https://stable-diffusion-art.com/lcm-lora/
- Latent Consistency Model for ComfyUI - https://github.com/0xbitches/ComfyUI-LCM
- Latent Consistency Models: Synthesizing High-Resolution Images with Few-Step Inference: https://github.com/luosiallen/latent-consistency-model
- Stable Diffusion ComfyUI Install Latent Consistency Model (LCM) (Tutorial Guide) - https://www.youtube.com/watch?v=y0Tw9Zb4Sy4

## Detailers
- Adetailer: Automatically fix faces and hands:  https://stable-diffusion-art.com/adetailer/
- Auto detecting, masking and inpainting with detection model: https://github.com/Bing-su/adetailer

- VRT: A Video Restoration Transformer - https://github.com/JingyunLiang/VRT

## Interpolator
- Make smooth AI generated videos with AnimateDiff and an interpolator: https://replicate.com/blog/animatediff-interpolator
- CONSISTENT VID2VID WITH ANIMATEDIFF AND COMFYUI , enigmatic_e:  https://www.youtube.com/watch?app=desktop&v=P4IdHKHrb48

## Faceswap
- REACTOR - Face Swap for A1111 - Full Guide! Better than Roop! : https://www.youtube.com/watch?v=jNmOGVFQwaY

## Mating & Background swap
-  How to change background in Stable Diffusion
A minimalistic implementation of Robust Video Matting (RVM) in ComfyUI : https://github.com/Fannovel16/ComfyUI-Video-Matting
- How to change background in Stable Diffusion: https://stable-diffusion-art.com/change-background/


## Using a camera
- Real Time Camera to AI in ComfyUI : https://www.youtube.com/watch?v=rl1znJNarAE
- NDI input and output functionality to the ComfyUI - https://github.com/ningxiaoxiao/comfyui-NDI
- Noodle webcam is a node that records frames and send them to your favourite node : https://github.com/Niutonian/ComfyUi-NoodleWebcam 
- Custom node and script for sending webcam to ComfyUI - https://github.com/toyxyz/ComfyUI_toyxyz_test_nodes
- ComfyUI node suite Nodes for procedural masking, live composition and video manipulatio : https://github.com/Amorano/Jovimetrix
- Comfy UI Webcam Noodling...like Mocap : https://www.youtube.com/watch?v=TH8xqyVjMpc

## Text
- Overlay text on an image in ComfyUI with font/alignment/placement customization - https://github.com/mikkel/ComfyUI-text-overlay

## Training
- Using replicate to train a lora: https://www.shruggingface.com/blog/self-portraits-with-stable-diffusion-and-lora
- https://tryolabs.com/blog/2022/10/25/the-guide-to-fine-tuning-stable-diffusion-with-your-own-images

## Models
- https://civitai.com/ 
- https://civitai.com/models
- https://github.com/civitai/civitai/wiki/How-to-use-models#fine-tuned-model-checkpoints-dreambooth-models

- epiCRealism: https://civitai.com/models/25694?modelVersionId=143906

## Comfy Workflows
- https://comfyworkflows.com/

## Scripting
- ComfyUI Using the API Part 1 : https://medium.com/@yushantripleseven/comfyui-using-the-api-261293aa055a
- Comfyui python interface : https://github.com/andreyryabtsev/comfyui-python-api
- Comfyui to App generator : https://github.com/xingren23/ComfyFlowApp
- Create APIs with comfyui : https://github.com/BadCafeCode/apitools-comfyui
- A powerful tool that translates ComfyUI workflows into executable Python code: https://github.com/pydn/ComfyUI-to-Python-Extension
- Building a Python API for Comfy UI with Gradio: https://www.youtube.com/watch?v=yspMVTL08Rc

## Storytelling
- How to Build an AI Children’s Book Service Ep. 1 — Deploy a Serverless Stable Diffusion API:  https://medium.com/@andrei.generative/how-to-build-an-ai-childrens-book-service-ep-1-deploy-a-serverless-stable-diffusion-api-5e7b0766d9e6
- Multimodal AI Story Teller, built with Stable Diffusion, GPT, and neural text-to-speech : https://github.com/jaketae/storyteller
- Become a Meme and Comic Strip guru in ComfyUI!: https://www.youtube.com/watch?v=piZrhyvw6f4
- I created a dialogue game in ComfyUI !: https://www.reddit.com/r/StableDiffusion/comments/18fln3i/i_created_a_dialogue_game_in_comfyui/

## Critics
- Using GPT-4 with Vision as an Art Critic: https://towardsdatascience.com/using-gpt-4-with-vision-as-an-art-critic-ec91080ba334

## Installers / deploys
-  https://pinokio.computer/
- A serverless application that uses AnimateDiff to run a Text-to-Video task on RunPod:  https://github.com/sky24h/AnimateDiff_Serverless_Runpod
- Cog: Containers for machine learning : https://github.com/replicate/cog
- ComfyUI Docker Image:  https://github.com/ai-dock/comfyui


## AI-Agents
- Implementation of AutoGen inside ComfyUI : https://github.com/xXAdonesXx/NodeGPT

## Generic Posts
- Generic post from Belgium on the new workflow : https://blog.4dcu.be/aiart/2023/09/03/comfyui-sdxl-workflows.html
- Kwebbelkop Replaced Himself With AI, We Told Him Why That's Weird... : https://www.youtube.com/watch?v=JpytyDeyVcs

## Other tools
- Pika Labs Tutorial: The Secret to Cinematic AI Videos : https://www.youtube.com/watch?v=_kZYlJpM0_g
- Unleash your Creativity with the power of Leonardo Ai : https://leonardo.ai/
- Meet the generative video platform that brings your ideas to life :  https://assistive.chat/product/video
- Krea - https://twitter.com/krea_ai/status/1723067313392320607

- StableSwarmUI, A Modular Stable Diffusion Web-User-Interface : https://github.com/Stability-AI/StableSwarmUI
- StreamDiffusion: A Pipeline-Level Solution for Real-Time Interactive Generation : https://github.com/cumulo-autumn/StreamDiffusion
- VisionCrafter tool with GUI for AnimateDiff and other projects, that generates animations and music from text: https://github.com/diStyApps/VisionCrafter
- The AI and Generative Art platform for everyone: https://github.com/rvion/CushyStudio

## Diffusers , GenAI & Python
- Generative AI with diffusers -  https://colab.research.google.com/drive/1p8Ugn6IBRtyGQu5MWzCXiMo0LVWoC-AE?usp=sharing
- Hands-on Guide: Image Generation in Custom Poses using IP-Adapters and Diffusers Library:  https://pjoshi15.com/generate-images-ipadapters-diffusers/
- How To Add Text Behind Moving Objects Using Python - https://pjoshi15.com/add-text-behind-moving-objects-python/
- Generate Images By Merging Multiple LoRA Models From CIVITAI -  https://pjoshi15.com/merging-multiple-lora-models-python/

- Merge a Logo with an Image using ControlNet: https://pjoshi15.com/stable-diffusion-controlnet-python/
- Ultra fast ControlNet with 🧨 Diffusers : https://huggingface.co/blog/controlnet#ultra-fast-controlnet-with-%F0%9F%A7%A8-diffusers

## Speech to text
- https://github.com/reriiasu/speech-to-text
