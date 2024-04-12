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
## module OpenPose
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 3863142680, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: none, Model: control_v11p_sd15_openpose [cab727d4], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0

---
origin
![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/OpenPose%EC%B6%94%EC%B6%9C%20%EC%9B%90%EB%B3%B8.png)

RigOutput

![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/%EC%B6%94%EC%B6%9C%EB%B3%B8.png)

---
## module None

Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 2505606783, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: openpose, Model: control_v11p_sd15_openpose [cab727d4], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0

---
origin

![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/%EC%B6%94%EC%B6%9C%EB%B3%B8.png)

RigOutput

![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/openpose%EA%B7%B8%EB%A6%BC%ED%99%94.png)


# Segmentation

## Module: seg_ofcoco

masterpiece, castle, middle western
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1806341205, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0: "Module: seg_ofcoco, 

Model: control_v11p_sd15_seg [e1f51eb9], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Processor Res: 512, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0

origin

![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/SegOriginPic.png)

RigOutput

![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/seg.png)
---

## Module: None

masterpiece, castle, middle western
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 1302718217, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, ControlNet 0:

 "Module: none, Model: control_v11p_sd15_seg [e1f51eb9], Weight: 1, Resize Mode: Resize and Fill, Low Vram: False, Guidance Start: 0, Guidance End: 1, Pixel Perfect: False, Control Mode: Balanced, Hr Option: Both, Save Detected Map: True", Version: v1.7.0


---

origin

![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/seg.png)

RigOutput

![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/segOutPut.png)


# lora


parameters

adventurer, masterpiece, simple background, <lora:pixel_f2:0.5>
Steps: 20, Sampler: DPM++ 2M Karras, CFG scale: 7, Seed: 117111648, Size: 512x512, Model hash: 00fea6886c, Model: fantasyBlend_v10, VAE hash: df3c506e51, VAE: kl-f8-anime2.ckpt, Lora hashes: "pixel_f2: 9d49ca20880d", Version: v1.7.0

---
![image](https://raw.githubusercontent.com/parechae123/StableDiffusion2024_3/38506699766986a0013f6a109f0da6a4a2e0a394/ControlNet/%EB%A1%9C%EB%9D%BC%EC%82%AC%EC%9A%A9.png)