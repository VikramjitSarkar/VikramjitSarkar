# Hi, I'm Vikramjit 👋

**Local AI on real machines. Honest numbers.**

I run open AI models on my own hardware, a **MacBook Pro M5 (32GB)** and an **RTX 4080 SUPER PC (16GB)**, and publish the real results: tokens per second, memory use, crashes and the fixes. I also build apps with AI (Flutter, web) and test what local coding models can really do.

[![YouTube](https://img.shields.io/badge/YouTube-IamVikramjit-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@IamVikramjit)
[![Website](https://img.shields.io/badge/Website-vikramjitsarkar.github.io-e0915a?logo=googlechrome&logoColor=white)](https://vikramjitsarkar.github.io)
[![X](https://img.shields.io/badge/X-@VikramjitSarkar-000000?logo=x&logoColor=white)](https://x.com/VikramjitSarkar)
[![Instagram](https://img.shields.io/badge/Instagram-@iam.vikramjit-E4405F?logo=instagram&logoColor=white)](https://www.instagram.com/iam.vikramjit/)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-bikramjitsarkar-FFD21E?logo=huggingface&logoColor=black)](https://huggingface.co/bikramjitsarkar)

## Latest benchmark

**Qwen 3.6 35B-A3B (UD-Q4_K_XL, 22.4 GB file) on an RTX 4080 SUPER 16GB + 32GB RAM**, llama.cpp b11900, MoE experts offloaded to RAM (`-ncmoe 16`, 64K context, q8_0 KV cache):

| Prompt tokens | Prompt processing | Time to first token | Generation |
|---|---|---|---|
| 2,056 | 1,782 tok/s | 1.15 s | 79.6 tok/s |
| 8,303 | 1,829 tok/s | 4.5 s | 80.5 tok/s |
| 20,964 | 2,068 tok/s | 10.1 s | 77.4 tok/s |

Same model on the MacBook Pro M5 32GB: ~40 tok/s (vs ~17 tok/s for a dense 27B).
Full config and discussion: [Hugging Face thread](https://huggingface.co/unsloth/Qwen3.6-35B-A3B-GGUF/discussions/31) · Video: [I Ran a 35B AI Model on a 16GB GPU](https://www.youtube.com/watch?v=ZypAda9_w-c)

## What I work with

llama.cpp · LM Studio · oMLX / MLX · Ollama · opencode · ComfyUI · Flutter · Python · ffmpeg · Playwright

## Contact

- Collabs and business: thevikeffect@gmail.com
- 📫 Email: bikramjitsarkar2@gmail.com
- Whatsapp: +919830753207
- 💞️ Open to collaborating on Flutter and local-AI projects
