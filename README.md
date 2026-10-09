# Hi, I'm Shaurya Pratap Srivastava (`null-Exception1`)

**"learning begins with the death of ego"** - liber primus 

first-year computer science undergraduate focusing on low-level distributed infrastructure, concurrent systems execution, and ML inference optimization frameworks.

currently working on : cf problem solving

---

languages: c, go, python, typescript, javascript, assembly

frameworks: grpc, tensorflow.keras or pytorch, next.js (app router) + tailwind css, socket.io or pubnub, SDL3/pygame (i guess), discord.py, flask, selenium

infra: supabase, neon, redis, mongodb, docker, firebase, vercel

---

### open source contributions:
* vllm-project/vllm: merged #54265 (docs example for Renderer.render_cmpl()); 
* reproduced a vLLM logprobs bug on the CPU backend on CPU (vLLM #60357, #60377). fix is waiting.
* opened RFC #57672 in vLLM proposing RSQR, a KV-cache eviction scheme that stores keys raw and applies one RoPE rotation at eviction; standalone benchmarks show ~3–4× lower isolated rotation cost than per-step re-rotation, with recall statistically on par with corrected re-rotation (Qwen2.5-0.5B)
* opened PR #60705 in vLLM recently (reducing Triton JIT stall from ~55 mins to 3 seconds, fix for the `_ranks_kernel` for CPU)

### interests:
* binary/web exploitation & reverse engineering (stack/rop layers)
* bit of crypto
* algorithmic problem solving (cses tracker)
* machine learning optimizations and algorithms
---

### blog

* [Cellular Automata with FeedForward Neural Nets as Neurons (and chemicals)](https://null-exception1.github.io/blog/posts/evNET/) - cellular automata's applications to brain design using non-linear complex behavioral neurons
* [RSQR: A New Perspective on Efficient KV-Cache Eviction for Streaming LLMs](https://null-exception1.github.io/blog/posts/RSQR/) - designing a RoPE re-rotation scheme for KV-cache eviction, diagnosing a numerical drift bug, and proposing it as an RFC to vLLM
* [The LLM Rabbit Hole](https://null-exception1.github.io/blog/posts/dllm/) - exploring speculative decoding and block-wise quantization for LLM inference; documents where the design failed and why
* [A Custom x86 Mini Assembly Emulator (and Why I Made It)](https://null-exception1.github.io/blog/posts/miniasmemulator/) - writing an x86 emulator in C from first principles: addressing modes, the stack, FLAGS register, JMP/CMP, Turing completeness
* [How I Built RoommateFinder (and Optimized It With Go)](https://null-exception1.github.io/blog/posts/roommatefinder/) - building a full-stack  platform from scratch; Go concurrency, caching, fan-in/fan-out worker pools, and benchmarking the wins



---




