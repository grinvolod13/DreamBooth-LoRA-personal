# Computer Vision Course Assignment: DreamBooth Personalization with Diffusers & LoRA

## Training Summary

- **Base model:** `stable-diffusion-v1-5`  
- **Method:** DreamBooth + LoRA  
- **LoRA settings:**
  - UNet: `r=8`, `alpha=27`  
  - Text encoder: `r=8`, `alpha=17`  
- **Training steps:** 1500  
- **Batch size:** 2  
- **Learning rate:** 1e-4 (constant scheduler)  
- **Gradient accumulation:** 1  
- **Device:** GPU (`cuda`)  
- **Precision:** float16  

## Examples

