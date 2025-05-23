# comfyUI_workflows
存一些自己搭建or复刻的工作流
main中工作流来源：https://github.com/cubiq/ComfyUI_Workflows/tree/main/basic#basic
B站papaya的视频入门：https://www.bilibili.com/video/BV1an9zY3EmC/?spm_id_from=333.1387.homepage.video_card.click&vd_source=f0332ff4e16f088f0f25d5ed5274bad2
1. 基础的工作流-basic_workflow
checkpoint：v1-5-pruned-emaonly.safetensors
2. 使用外置的VAE-basic_workflow_ext_vae
checkpoint：v1-5-pruned-emaonly.safetensors
VAE：vae-ft-mse-840000-ema-pruned.safetensors
3. 生成多张图片-basic_latent_batch
checkpoint：v1-5-pruned-emaonly.safetensors
VAE：vae-ft-mse-840000-ema-pruned.safetensors
4. 参数化节点-basic_parametrized
checkpoint：v1-5-pruned-emaonly.safetensors
VAE：vae-ft-mse-840000-ema-pruned.safetensors
5. LoRA微调-basic_lora
Checkpoint：dreamshaper 8Inpainting.safetensors
LoRA：ghibli_style_offset.safetensors
VAE：vae-ft-mse-840000-ema-pruned.safetensors
6. 多个LoRA-multiple_loras
Checkpoint：dreamshaper_8.safetensors
LoRA：ghibli_style_offset.safetensors
LoRA：more_details.safetensors
VAE：vae-ft-mse-840000-ema-pruned.safetensors
7. 文本裁剪-CLIP skip
Checkpoint：v1-5-pruned-emaonly.safetensors
VAE：vae-ft-mse-840000-ema-pruned.safetensors
8. SDXL简单版-SDXL_Simple
Checkpoint:sd_xl_base_1.0.safertensors
Checkpoint:sd_xl_refiner_1.0.safertensors
9. SDXL_advanced
Checkpoint:sd_xl_base_1.0.safertensors
Checkpoint:sd_xl_refiner_1.0.safertensors
10. SDXL_text_g-l
