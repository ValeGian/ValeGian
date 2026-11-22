**AI Tech Lead, LLM Inference Engineer at [Translated](https://translated.com).** I own the decoder behind Lara, our
LLM translation service, and lead a small team around it. Day to day: vLLM internals, speculative decoding (Medusa,
EAGLE-3, DSpark), low-precision inference (FP8, NVFP4) on NVIDIA Hopper and Blackwell GPUs, and the benchmarks that
decide what ships.

**Open source**

- **Lara Mini**: I'm part of the core team behind Translated's open multilingual MoE base model
  ([model](https://huggingface.co/translated/Lara-4-Mini-Base), [report](https://arxiv.org/abs/2611.16956)), and I
  brought it to [Hugging Face Transformers](https://github.com/huggingface/transformers/pull/50819) (merged, v5.24.0)
  and [vLLM](https://github.com/vllm-project/vllm/pull/67978) (in review).
- I also work upstream on the stack I run in production: fixes, bug reports and root-cause analyses for vLLM,
  SGLang (SpecForge) and TensorRT-LLM.

**Side projects**

- [liteinfer](https://github.com/ValeGian/liteinfer): an LLM inference engine from scratch: paged KV cache, Triton
  paged attention, continuous batching, chunked prefill, CUDA graphs. On PyPI.
- [variantGPT](https://github.com/ValeGian/variantGPT): GPT-2 trained with seven attention variants, from MHA to
  DeepSeek's MLA, under the same budget and compared.

[valegian.github.io](https://valegian.github.io) · [LinkedIn](https://www.linkedin.com/in/valerio-giannini/)
