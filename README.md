# LLaMA Finetune Starter

This is my first hands-on experiment with fine-tuning a Large Language Model (LLM) — specifically, the **LLaMA 2-7B Chat** model.

The goal of this project was to explore how instruction tuning works using a small dataset and tools like PEFT, LoRA, bitsandbytes, and Hugging Face's Trainer.

---

## What I Did

- ✅ Loaded `NousResearch/Llama-2-7b-chat-hf` in 4-bit using QLoRA
- ✅ Used a lightweight instruction-tuning dataset (1k samples)
- ✅ Applied LoRA (Low-Rank Adaptation) using `peft`
- ✅ Fine-tuned with Hugging Face `Trainer` instead of TRL
- ✅ Tokenized raw text to `input_ids` before training
- ✅ Trained on Kaggle GPU with quantized memory efficiency

---

## Tech Stack

- **Model**: LLaMA 2-7B (HF variant)
- **Library**: Hugging Face Transformers
- **Quantization**: bitsandbytes (4-bit)
- **PEFT**: LoRA for parameter-efficient tuning
- **Platform**: Kaggle (Free GPU)

---

## Dataset

Used a small instruction-based dataset (`Llama2-1k.parquet`) for faster experimentation.

---

## What's Next

This was my first dive into LLM fine-tuning. I plan to:

- Experiment with larger datasets
- Try other models like Mistral or Gemma
- Explore SFTTrainer or DeepSpeed integration

---

## Acknowledgements

Huge thanks to the Hugging Face and open-source communities for making this so beginner-friendly.

---

>  If you're reading this — yes, this is my first LLM finetuning attempt. Feel free to share tips!
