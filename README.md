# SD IceJi ProPortrait

## Built with the concept “Prompt less, Post more”
Just only short prompt and you will get a realistic portrait photo. Let you focus on posting on social media, building engagement, and doing other things that are important to you.

#### *** This Model needs VAE !!! ***

## Overview:

* The purpose of this model is to generate a portrait photo.
* These models require a VAE. You can try mse-840000-ema or anything. I have a photo of the comparison in the Comparision section (below)
* If you got bugs, adding '--no-half-vae' to the argument will solve it.

## Recommends:

* **Prompt:**
  Try to **start with** `(skindentation:1.2), (realistic:1.1), best quality, photorealistic, ...`
  **Negative:** `lowres, normal quality, ((monochrome)), ((grayscale)), BadHand v4`
* **Steps:** I recommend 30-45 (You can use higher, but many times do not have a big difference)
* **Sampler:** I developed it with DPM++ 2S a Karras, so I recommend this sampler (but others also work fine)
* **Sizes:**
  **Medium shot:** 512x512, 512x768, 512x904
  **Long shot (full body):** 768x1152, 768x1356
  *Can be used both vertically and horizontally*
* **Hires. fix:** Use Denoising strength less than 0.6 (but you can try >= 0.7, sometimes you will get problems with the hands)

## Download

[https://civitai.com/models/72093](https://civitai.com/models/72093)

## Disclaimers:

* **Do not sell:** on any website.
* **Credit:** If you use my model in your own merges
* **Not authorized:** to be used on **generative services** (without my permission)
