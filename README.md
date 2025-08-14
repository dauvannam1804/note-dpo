# note-dpo
Training Direct Preference Optimization (DPO) on Vietnamese Alpaca Preference dataset with LLaMA 3.2 1B Instruct (QLoRA 4-bit).   DPO optimizes the model to prefer “chosen” over “rejected” responses without a reward model or PPO.   Pipeline: SFT → convert to preference format → DPO fine-tuning → save &amp; push to Hugging Face.  
