# controllNet

## Scribble

lineart, white background, masterpiece, extremely detailed thick line drawing, 1girl , hoodie, animal gloves, skirt, sneakers
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2725415013, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: scribble_pidinet, Model: control_v11p_sd15_scribble [d4ba51ff], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0


---

![image](https://github.com/parechae123/StableDiffusion2024_3/blob/main/ControlNet/ScribbleBefore.png?raw=true)

![image](https://github.com/parechae123/StableDiffusion2024_3/blob/main/ControlNet/ScribbleAfter.png?raw=true)

## Depth

lineart, white background, masterpiece, extremely detailed thick line drawing, 1girl , hoodie, animal gloves, skirt, sneakers
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2725415013, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: scribble_pidinet, Model: control_v11p_sd15_scribble [d4ba51ff], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0


---

![image](https://github.com/parechae123/StableDiffusion2024_3/blob/main/ControlNet/DepthBefore.png?raw=true)

![image](https://github.com/parechae123/StableDiffusion2024_3/blob/main/ControlNet/DepthAfter.png?raw=true)

## Pixelize


parameters
None

postprocessing
Pixelization pixel size: 12

extras
Pixelization pixel size: 12


---

![image](https://github.com/parechae123/StableDiffusion2024_3/blob/main/ControlNet/PixelizeBefore.jpg?raw=true)

![image](https://github.com/parechae123/StableDiffusion2024_3/blob/main/ControlNet/PixelizeAfter.png?raw=true)



# OpenPose
## module None
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 3863142680, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: none, Model: control_v11p_sd15_openpose [cab727d4], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0

---
origin
![image]()
RigOutput
![image]()

---
## module OpenPose

Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2505606783, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: openpose, Model: control_v11p_sd15_openpose [cab727d4], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0

---
origin
![image]()
RigOutput
![image]()


# Segmentation

## Module: seg_ofcoco

masterpiece, castle, middle western
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1806341205, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: seg_ofcoco, 

Model: control_v11p_sd15_seg [e1f51eb9], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0

origin
![image]()
RigOutput
![image]()
---

## Module: None

masterpiece, castle, middle western
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1302718217, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0:

 "Module: none, Model: control_v11p_sd15_seg [e1f51eb9], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0


---

origin
![image]()
RigOutput
![image]()


# lora


parameters

adventurer, masterpiece, simple background, <lora:pixel_f2:0.5>
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 117111648, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Lora hashes: "pixel_f2: 9d49ca20880d", Version: v1.7.0

---
![image]()