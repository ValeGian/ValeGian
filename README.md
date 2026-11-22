**AI Tech Lead, LLM Inference Engineer at [Translated](https://translated.com).** I own the decoder behind Lara, our
LLM translation service, lead the team around it, and deploy the open 100-500B models we use internally for
work like coding. Day to day: vLLM internals, speculative decoding (Medusa,
EAGLE-3, DSpark), low-precision inference (FP8, NVFP4) on NVIDIA Hopper and Blackwell GPUs, and the benchmarks that
decide what ships.

**Open source**

- **Lara Mini**: I'm part of the core team behind Translated's open MoE base model, the best open base model in
  its size class
  ([model](https://huggingface.co/translated/Lara-4-Mini-Base), [report](https://arxiv.org/abs/2611.16956)), and I
  brought it to [Hugging Face Transformers](https://github.com/huggingface/transformers/pull/50819) (merged, v5.24.0)
  and [vLLM](https://github.com/vllm-project/vllm/pull/67978) (in review).
- I also work upstream on the stack I run in production: fixes, bug reports and root-cause analyses for vLLM (like
  a [silent accuracy drop with redundant EPLB experts](https://github.com/vllm-project/vllm/issues/67054), traced to
  its cause with a minimal repro), SGLang (SpecForge) and TensorRT-LLM.

**Side projects**

- [liteinfer](https://github.com/ValeGian/liteinfer): an LLM inference engine from scratch: paged KV cache, Triton
  paged attention, continuous batching, chunked prefill, CUDA graphs. On PyPI.
- [variantGPT](https://github.com/ValeGian/variantGPT): GPT-2 trained with seven attention variants, from MHA to
  DeepSeek's MLA, under the same budget and compared.

[valegian.github.io](https://valegian.github.io) · [LinkedIn](https://www.linkedin.com/in/valerio-giannini/)
