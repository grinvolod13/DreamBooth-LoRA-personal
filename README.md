# Computer Vision Course Assignment: DreamBooth Personalization with Diffusers & LoRA

## Training Summary
- [Check out WandB output](https://api.wandb.ai/links/grinvolod13-kau-edu-ua/cmhp4rt0)
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
## Outputs:
* [Train Colab notebook](https://colab.research.google.com/drive/1aX3tFmZ-T3QjKdXt2id_RdCLtFgb-lGP)
* [HuggingFace LoRA model](https://huggingface.co/grinvolod/lora-personal)
* [WandB output](https://api.wandb.ai/links/grinvolod13-kau-edu-ua/cmhp4rt0)
## Examples
![image](./example.png)
