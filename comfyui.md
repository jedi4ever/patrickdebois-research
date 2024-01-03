
# Collected notes from Patrick Debois on visual GenAI & ComfyUI

## Basics
- Using SDXL Turbo : https://comfyanonymous.github.io/ComfyUI_examples/sdturbo/

### Samplers
- Stable Diffusion Samplers: A Comprehensive Guide: https://stable-diffusion-art.com/samplers/
- Worse image quality:  https://www.reddit.com/r/comfyui/comments/167abs7/worse_image_quality/
- Stable Diffusion Deep Dive - Samplers - which are worth using and which are redundant? - https://www.youtube.com/watch?v=gtr-4CUBfeQ

### CFG
- Stable Diffusion Deep Dive - CFG - Don't Accidentally Fry Your Images: https://www.youtube.com/watch?v=kuhO9zAzetks
- - Stable Diffusion’s CFG Scale Explained : https://onceuponanalgorithm.org/guide-stable-diffusions-cfg-scale-explained/

### Denoise
- What Denoising Strength Does and How to Use It in Stable Diffusion
-  https://onceuponanalgorithm.org/guide-what-denoising-strength-does-and-how-to-use-it-in-stable-diffusion/

### Seed
- What Is A Stable Diffusion Seed and How To Use It https://onceuponanalgorithm.org/guide-what-is-a-stable-diffusion-seed-and-how-to-use-it/

### SDXL + refiner
- ComfyUI 02 - SDXL Refiner Workflow: https://www.youtube.com/watch?v=ATIpqMfqEX4

## Prompting
- Camera angles prompts : https://generativeai.pub/stable-diffusion-enables-the-control-of-camera-distance-and-angles-using-prompts-53ca4d1c9981
- GPT-4 + Stable-Diffusion = ?: Enhancing prompt understanding of text-to-image diffusion models with large language models : https://aihub.org/2023/06/26/gpt-4-stable-diffusion-enhancing-prompt-understanding-of-text-to-image-diffusion-models-with-large-language-models/
- ComfyUI Portrait Master , node designed to help AI image creators to generate prompts for human portraits: https://github.com/florestefano1975/comfyui-portrait-master

## Refine
- Upscale from pixels to real life:  https://youtu.be/kBFMKroTuXE?si=XSFs6pN1wM_5CBaa

## Area composition
- Area Composition Examples : https://comfyanonymous.github.io/ComfyUI_examples/area_composition/
- GLIGEN model lets you specify the location and size of multiple objects in the image: https://comfyanonymous.github.io/ComfyUI_examples/gligen/

- Davemane42's Custom Node for ComfyUI , MultiAreaConditioning 2.4, MultiLatentComposite : https://github.com/Davemane42/ComfyUI_Dave_CustomNode
- ComfyUI: Area Composition, Multi Prompt Workflow Tutorial:  https://www.youtube.com/watch?v=NPkSa1y0GLM

## ControlNet
- Official ControlNet : https://github.com/lllyasviel/ControlNet
- What is ControlNet for Stable Diffusion? How to Use It? : https://lancerninja.com/controlnet-for-stable-diffusion/


- Creating AI Generated QR Codes Using Stable Diffusion And ControlNet: https://www.brainbyte.io/creating-ai-generated-qr-codes-using-stable-diffusion-and-control-net/

- Nodes for pre-processing controlnet (Openpose, ...) - https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet

### Openpose
- SDXL-OpenPose and CodeFormer Workflow for Image Transformation:  https://blog.segmind.com/enhancing-image-quality-and-feature-retention-a-guide-using-sdxl-codeformer-and-openpose/
- CodeFormer: Robust Face Restoration and Enhancement Network - https://huggingface.co/spaces/sczhou/CodeFormer
- ControlNet v1.1: A complete guide: https://stable-diffusion-art.com/controlnet/

- https://webapp.magicposer.com/
- https://openposes.com/

- Reposer = Consistent Stable Diffusion Generated Characters in ANY pose from 1 image - https://www.youtube.com/watch?v=SacK9tMVNUA


### Segmentation
- ComfyUI animation with segmentation: TrackAnything with SAM models : https://www.youtube.com/watch?v=HoTnTxlwdEw
- Stable Diffusion Inpainting with Segment Anything Model (SAM) : https://www.youtube.com/watch?v=CERvlvUvVEI
- (track-anything )Tutorial install Track-Anything for video in Windows:  https://www.reddit.com/r/StableDiffusion/comments/1306qap/trackanything_tutorial_install_trackanything_for/
- Track-Anything is a flexible and interactive tool for video object tracking and segmentation, based on Segment Anything, XMem, and E2FGVI: https://github.com/gaomingqi/Track-Anything
- Easy stable diffusion inpainting with Segment Anything Model: https://www.ikomia.ai/blog/stable-diffusion-inpainting-with-segment-anything-model-sam-using-the-ikomia-api

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
- FaceID: new IPAdapter model:  https://www.youtube.com/watch?v=jSu_tKfg5rI
- Jellyfish Ballerina Animation with AnimateDiff: https://www.youtube.com/watch?v=_f-jv311w-g

- A1111: IP Adapter ControlNet Tutorial (Stable Diffusion) : https://www.youtube.com/watch?v=KHm5Q5TfNvE
- IP-Adapters are the New Killer App for Stable Diffusion in Comfy-UI : https://www.youtube.com/watch?v=ySqrmxl4jUE
- STOP wasting time with Style LORAs! Use THIS instead! How to copy ANY style with IP Adapter - https://www.youtube.com/watch?v=rOOhvZ-8Y0w

## AnimateDiff

- Animatediff perfect scenes. Any background with conditional masking. ComfyUI Animation :  https://www.youtube.com/watch?v=gDUeqCErjt4
- Animate your hero and take him/her to any scenario in ComfyUI: https://civitai.com/articles/2952/animate-your-hero-and-take-himher-to-any-scenario-in-comfyui

- AnimateDiff + Instant Lora: ultimate method for video animations ComfyUI (img2img, vid2vid, txt2vid): https://www.youtube.com/watch?v=Ka4ENd63VBo

- Comfyui Animatediff plugin : https://github.com/ArtVentureX/comfyui-animatediff
- Official implementation of AnimateDiff : https://github.com/guoyww/AnimateDiff
- AnimateDiff for ComfyUI (old?) : https://github.com/Kosinkadink/ComfyUI-AnimateDiff-Evolved

- Unlocking the AI Frontier: Prompt Travel, ControlNet, and IP-Adapter in AnimateDiff : https://medium.com/ai-artistry/unlocking-the-ai-frontier-prompt-travel-controlnet-and-ip-adapter-in-animatediff-5d83a74ea766
- Introduction to the comfyUI + animateDiff Video2Video, AI Video Generation Workflow and Examples:  https://medium.com/@zhangp365/introduction-to-the-comfyui-animatediff-video2video-ai-video-generation-workflow-and-examples-f6cec78f640b

- Video to video with AnimateDiff prompt travel: https://stable-diffusion-art.com/animatediff-prompt-travel-video2video/
- Comfyui AnimateDiff v3 + LCM Video to Video - https://www.youtube.com/watch?v=XQLtI0KT2G0
- Ai Animation With ComfyUI: https://www.youtube.com/watch?v=YulLJ7ixBvg
- ComfyUI AnimateDiff Flicker-Free Inpainting : https://www.youtube.com/watch?v=eUJ06FWc3Go
- Stable Diffusion Animation Create Tiktok Dance AI Video (Tutorial Guide): https://www.youtube.com/watch?v=wFahkr-b7HI

-This is a comprehensive workflow tutorial on using Stable Video Diffusion in Comfy UI. : https://www.youtube.com/watch?v=m-ZoxcYNWFg

- ComfyUI AnimateDiff Prompt Travel, ControlNets and Video to Video : https://www.youtube.com/watch?v=Drh8jpjE1yo
- Prompt travelling : https://www.andyhtu.com/post/animatediff-animation-control-how-to-prompt-travel-in-automatic111
- https://simpleaiart.com/sd-animatediff-cli-prompt-travel/
- https://github.com/s9roll7/animatediff-cli-prompt-travel


- SparseCtrl is a feature added in AnimateDiff v3 that is useful for creating natural motion with a small number of inputs:  https://twitter.com/toyxyz3/status/1739318630905741636

- AnimateDiff for Stable Diffusion WebUI : https://github.com/continue-revolution/sd-webui-animatediff#motion-lora

- Longer movies with AnimateDiff:  https://github.com/pixelatedpoets/longer-animatediff-movies
- Metahuman + SD + animateDiff in comfyUI : https://twitter.com/dreamstarter_1/status/1731643881039499600

- Infinite Zoom, Powers of Ten - https://twitter.com/alexgabbia/status/1733412361334075660
- Easily use MagicAnimate within ComfyUI - https://github.com/thecooltechguy/ComfyUI-MagicAnimate

## Motion Lora
- Motion LoRAs in AnimateDiff : https://www.youtube.com/watch?v=rMOnq2he5dQ&list=TLPQMjkxMjIwMjPv9c0Nep2Qtw&index=3
- Understanding Motion and LoRa Models for AnimateDiff: https://www.andyhtu.com/post/understanding-motion-and-lora-models-for-animatediff
- Exploring Advanced Motion: Steerable Motion & AnimateDiff V3 in ComfyUI: https://www.youtube.com/watch?v=T7X0qOIiMxk
- Steerable Motion, a ComfyUI custom node for steering videos with batches of images : https://github.com/Limbicnation/Steerable-Motion

- MotionCtrl: A Unified and Flexible Motion Controller for Video Generation - https://github.com/chaojie/ComfyUI-MotionCtrl

## LCM Lora 
- Using LCM Lora for consistency + animatediff - https://stable-diffusion-art.com/lcm-lora/
- Latent Consistency Model for ComfyUI - https://github.com/0xbitches/ComfyUI-LCM
- Latent Consistency Models: Synthesizing High-Resolution Images with Few-Step Inference: https://github.com/luosiallen/latent-consistency-model
- Stable Diffusion ComfyUI Install Latent Consistency Model (LCM) (Tutorial Guide) - https://www.youtube.com/watch?v=y0Tw9Zb4Sy4
- Testing LCM LORAs in an AnimateDiff & multi-controlnet workflow in ComfyUI. - https://twitter.com/coffeevectors/status/1724579821093540182
-ComfyUI Setup & AnimateDiff-Evolved Workflow + ControlNet OpenPose and QRcode Monster : https://www.youtube.com/watch?v=GV_syPyGSDY

- set LCM in Ksampler 
- lcm will not give photo realistic ? but will go fast

## Detailers
- Adetailer: Automatically fix faces and hands:  https://stable-diffusion-art.com/adetailer/
- Auto detecting, masking and inpainting with detection model: https://github.com/Bing-su/adetailer

- ComfyUI-Impact-Pack - Tutorial #2: FaceDetailer: https://www.youtube.com/watch?v=z4JzuuFyr1Y
- ComfyUI Impact Pack - FaceDetailerPipe with Wildcard (updated) - https://www.youtube.com/watch?v=lVSNJYfvO9o
- ComfyUI Impact Pack - Tutorial #8: Gender Sensitive Detailer : https://www.youtube.com/watch?v=Vs2r-MErJZw



## Scalers & Enhancers
- VRT: A Video Restoration Transformer - https://github.com/JingyunLiang/VRT
- ComfyUI nodes for the Ultimate Stable Diffusion Upscale script by Coyote-A.  : https://github.com/ssitu/ComfyUI_UltimateSDUpscale

## Interpolator
- Make smooth AI generated videos with AnimateDiff and an interpolator: https://replicate.com/blog/animatediff-interpolator
- CONSISTENT VID2VID WITH ANIMATEDIFF AND COMFYUI , enigmatic_e:  https://www.youtube.com/watch?app=desktop&v=P4IdHKHrb48
- A custom node set for Video Frame Interpolation in ComfyUI: https://github.com/Fannovel16/ComfyUI-Frame-Interpolation


## Faceswap
- REACTOR - Face Swap for A1111 - Full Guide! Better than Roop! : https://www.youtube.com/watch?v=jNmOGVFQwaY

## Fashion swap / Outfit
- How to swap outfits in videos using Stable Diffusion with ComfyUI while keeping consistency : https://www.youtube.com/watch?v=Oa48SlGqdl8
- Outfit To Outfit - ControlNet (outfit2outfit): https://civitai.com/models/191956/outfit-to-outfit-controlnet-outfit2outfit

## Mating, Masking & Background swap
-  How to change background in Stable Diffusion
A minimalistic implementation of Robust Video Matting (RVM) in ComfyUI : https://github.com/Fannovel16/ComfyUI-Video-Matting
- How to change background in Stable Diffusion: https://stable-diffusion-art.com/change-background/
- node pack for ComfyUI, primarily dealing with masks - https://github.com/BadCafeCode/masquerade-nodes-comfyui


## Using a camera
- Real Time Camera to AI in ComfyUI : https://www.youtube.com/watch?v=rl1znJNarAE
- How to use your webcam with ComfyUI - https://www.youtube.com/watch?v=xeKZDAYeh5w
- NDI input and output functionality to the ComfyUI - https://github.com/ningxiaoxiao/comfyui-NDI
- Noodle webcam is a node that records frames and send them to your favourite node : https://github.com/Niutonian/ComfyUi-NoodleWebcam 
- Custom node and script for sending webcam to ComfyUI - https://github.com/toyxyz/ComfyUI_toyxyz_test_nodes
- ComfyUI node suite Nodes for procedural masking, live composition and video manipulatio : https://github.com/Amorano/Jovimetrix
- Comfy UI Webcam Noodling...like Mocap : https://www.youtube.com/watch?v=TH8xqyVjMpc

## Scribble, Draw, Paint
- ScreenShareNode & FloatingVideoNode - https://github.com/shadowcz007/comfyui-mixlab-nodes
- Drawing Near Real Time Rendering IN ComfyUI? - https://youtu.be/ZF1GJasG7kc?si=mlV86IyJam9OyczS
- ComfyUI canvas editor page - https://github.com/Lerc/canvas_tab
- PainterNode allows you to draw in the node window: https://github.com/AlekPet/ComfyUI_Custom_Nodes_AlekPet/tree/master/PainterNode


## Text
- Overlay text on an image in ComfyUI with font/alignment/placement customization - https://github.com/mikkel/ComfyUI-text-overlay

## Training
- DreamBooth training example: https://github.com/huggingface/diffusers/tree/main/examples/dreambooth

- Using replicate to train a lora: https://www.shruggingface.com/blog/self-portraits-with-stable-diffusion-and-lora
- https://tryolabs.com/blog/2022/10/25/the-guide-to-fine-tuning-stable-diffusion-with-your-own-images
- Training my first SD LoRA: https://weirdwonderfulai.art/tutorial/training-my-first-sd-lora/
- Dreambooth Training for Personal Embedding: https://bennycheung.github.io/dreambooth-training-for-personal-embedding
- Stable Diffusion Lora Training with Kohya (Tutorial): https://www.youtube.com/watch?v=_F39RbO3tYo
- LORA Training - for HYPER Realistic Results:  https://youtu.be/PadSEwA3xiU?si=T1lCjDS_Q76SpDp0
- Training LoRA with Kohya (theory included!) - https://youtu.be/xholR62Q2tY?si=ecF5oBzURQUdAWGn



## Extras / Plugins
- ComfyUI-Manager is an extension designed to enhance the usability: https://github.com/ltdrdata/ComfyUI-Manager
- https://github.com/ltdrdata/ComfyUI-Impact-Pack: UltralyticsDetectorProvider, Detector, Detailer, Upscaler, Pipe :   https://github.com/ltdrdata/ComfyUI-Impact-Pack
- Autocomplete, Image Feed, Show text , reroute -  https://github.com/pythongosssss/ComfyUI-Custom-Scripts
- Seamlessly switch between workflows : https://github.com/11cafe/comfyui-workspace-manager

- CR Multi-ControlNet Stack, 📉 XY Grid - https://github.com/Suzie1/ComfyUI_Comfyroll_CustomNodes
- ComfyUI-Text_Image-Composite : https://github.com/ZHO-ZHO-ZHO/ComfyUI-Text_Image-Composite
- XYZPlot , Simple grid of images: https://github.com/LEv145/images-grid-comfy-plugin
- SDXL Prompt Styler, a custom node for ComfyUI: https://github.com/twri/sdxl_prompt_styler

- Prompt scheduler - scheduling during steps : https://github.com/asagi4/comfyui-prompt-control


## Comfyui Tips
- enable module label in view (settings)
- enable preview of sampler (settings)
- enable api / dev mode
- enable auto run

## OpenAI , LLama, ...
- OpenAI, Dall-E, Generator/Stereo Image Generator: https://github.com/natto-maki/ComfyUI-NegiTools
- ComfyUI ExLlama Nodes - https://github.com/Zuellni/ComfyUI-ExLlama-Nodes
- ExLlamaV2 is an inference library for running local LLMs on modern consumer GPUs. - https://github.com/turboderp/exllamav2
- Extra nodes to be used in ComfyUI, including a new ChatGPT node for generating natural language responses.: https://github.com/omar92/ComfyUI-QualityOfLifeSuit_Omar92
- A simply node for hooking in to openAI API based servers via comfyUI : https://github.com/Electrofried/ComfyUI-OpenAINode

## LLM & Vision
- A ComfyUI extension for chatting with your images with LLaVA. Runs locally, no external services, no filter.: https://github.com/ceruleandeep/ComfyUI-LLaVA-Captioner
- No module named 'llama_cpp' - https://github.com/ceruleandeep/ComfyUI-LLaVA-Captioner/issues/1


## Models
- https://civitai.com/ 
- https://civitai.com/models
- https://github.com/civitai/civitai/wiki/How-to-use-models#fine-tuned-model-checkpoints-dreambooth-models

- epiCRealism: https://civitai.com/models/25694?modelVersionId=143906

### UX/UI
- Ui-Ux (LORA) : https://civitai.com/models/98715/ui-ux-lora
- Ui-Ux (LORA) - A tool to speed up your concept workflow, not to replace it.: https://stablediffusionapi.com/models/ui-ux
- WEBUI Helper: Embedding to help make web UI and UX designs in Stable diffusion:  https://civitai.com/models/2502/webui-helper

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
- Any guide on creating comic books with SD : https://www.reddit.com/r/comfyui/comments/16k0gvl/creating_comics/

- I created a dialogue game in ComfyUI !: https://www.reddit.com/r/StableDiffusion/comments/18fln3i/i_created_a_dialogue_game_in_comfyui/

## Critics
- Using GPT-4 with Vision as an Art Critic: https://towardsdatascience.com/using-gpt-4-with-vision-as-an-art-critic-ec91080ba334
- An interesting unexpected use case for GPT-4 with vision - it makes a pretty good intelligent picture coach: https://twitter.com/emollick/status/1707634298507956569
- https://github.com/logicalroot/gpt-4v-demos/blob/main/pages/3_%F0%9F%93%8B_Quality_Control.py

## Installers / deploys
- Run ComfyUI workflows on multiple local GPUs/networked machines.: https://github.com/city96/ComfyUI_NetDist
-An open source `vercel` like deployment platform for Comfy UI :  https://github.com/BennyKok/comfyui-deploy
- runpod-worker-comfy -  https://github.com/BennyKok/comfy-deploy-runpod-worker

-  https://pinokio.computer/
- A serverless application that uses AnimateDiff to run a Text-to-Video task on RunPod:  https://github.com/sky24h/AnimateDiff_Serverless_Runpod

- Cog: Containers for machine learning : https://github.com/replicate/cog
- ComfyUI Docker Image:  https://github.com/ai-dock/comfyui
- Example Cog, Comfyui deploy - https://github.com/lucataco/cog-comfyui-sdxl-txt2img

- The next gen Serverless ComfyUI Cloud: https://comfy.icu/serverless/
-  a powerful tool for serving image generation workflows in Discord and other platforms: https://github.com/matan1905/ComfyUI-Serving-Toolkit


## AI-Agents
- Implementation of AutoGen inside ComfyUI : https://github.com/xXAdonesXx/NodeGPT
- Kasucast #20 - Autogen/AI Agents & Local Multimodal LLMs caption realistic Stable Diffusion model - https://www.youtube.com/watch?v=jUUk4RQpiK4

## Generic Posts
- Generic post from Belgium on the new workflow : https://blog.4dcu.be/aiart/2023/09/03/comfyui-sdxl-workflows.html
- Kwebbelkop Replaced Himself With AI, We Told Him Why That's Weird... : https://www.youtube.com/watch?v=JpytyDeyVcs

## Other tools
- Pika Labs Tutorial: The Secret to Cinematic AI Videos : https://www.youtube.com/watch?v=_kZYlJpM0_g
- Unleash your Creativity with the power of Leonardo Ai : https://leonardo.ai/
- Meet the generative video platform that brings your ideas to life :  https://assistive.chat/product/video
- Krea - https://twitter.com/krea_ai/status/1723067313392320607
- RenderNet - Fastest Stable Diffusion generator on the planet: https://rendernet.ai/

- StableSwarmUI, A Modular Stable Diffusion Web-User-Interface : https://github.com/Stability-AI/StableSwarmUI
- StreamDiffusion: A Pipeline-Level Solution for Real-Time Interactive Generation : https://github.com/cumulo-autumn/StreamDiffusion
- VisionCrafter tool with GUI for AnimateDiff and other projects, that generates animations and music from text: https://github.com/diStyApps/VisionCrafter
- The AI and Generative Art platform for everyone: https://github.com/rvion/CushyStudio
-  Stable diffusion command-line interface : https://github.com/nimadez/mental-diffusion
- ImaginePy, opensource (reversed) API like Stable Diffusion, Midjourney. Everything at 0 Cost: https://github.com/ItsCEED/Imaginepy

## Dall-E
- A sample application that shows how you can outpaint using the Dall-E API: https://github.com/SabatinoMasala/dalle-api-outpainting-sample


## Diffusers , GenAI & Python
- Generative AI with diffusers -  https://colab.research.google.com/drive/1p8Ugn6IBRtyGQu5MWzCXiMo0LVWoC-AE?usp=sharing
- Hands-on Guide: Image Generation in Custom Poses using IP-Adapters and Diffusers Library:  https://pjoshi15.com/generate-images-ipadapters-diffusers/
- How To Add Text Behind Moving Objects Using Python - https://pjoshi15.com/add-text-behind-moving-objects-python/
- Generate Images By Merging Multiple LoRA Models From CIVITAI -  https://pjoshi15.com/merging-multiple-lora-models-python/

- Merge a Logo with an Image using ControlNet: https://pjoshi15.com/stable-diffusion-controlnet-python/
- Ultra fast ControlNet with 🧨 Diffusers : https://huggingface.co/blog/controlnet#ultra-fast-controlnet-with-%F0%9F%A7%A8-diffusers

## Speech to text
- https://github.com/reriiasu/speech-to-text
