# Hi, I'm Shaurya Pratap Srivastava (`null-Exception1`)

First-year Computer Science Undergraduate focusing on low-level distributed infrastructure, concurrent systems execution, and ML inference optimization frameworks.

---

### Technical Competencies
- **Languages:** Go, Pure C, Python (PyTorch / TorchRL), JavaScript (Next.js / JSX), SQL (PostgreSQL), Assembly (x86)
- **Systems & Infrastructure:** Distributed Sharding, gRPC Meshes, Docker & Compose, Sync/Async Worker Pools, TCP Netcode, Data Structures (Segment Trees, Hash Rings, Tries)
- **Algorithms & Problem Solving:** Codeforces Pupil (Peak 1148) | CSES Problem Set (Graphs, Trees, DP)

---

### Active Engineering Projects

#### [s-tree-sharding](https://github.com)
*Distributed Database Datastore Engine (Go, gRPC, Docker, Protobuf)*
- Designed an autonomous multi-node distributed database utilizing a custom **auto-balancing segment tree topology** with interval range-locking frameworks to eliminate concurrent multi-node write conflicts.
- Implemented a decentralized **500ms rebalance monitor** executing midpoint data-range extractions to seamlessly migrate out-of-bounds keys to adjacent ring neighbors without a central coordinator.

#### [roommatefinder](https://github.com)
*High-Throughput Concurrent Matching Backend (Go, PostgreSQL, Next.js)*
- Optimized concurrent endpoint request processing performance by **937%** (scaling throughput from 2,705 to 25,360 requests/second) by isolating and eliminating raw `json.Marshal` preprocessing overhead.
- Decoupled traditional mutual exclusion (`sync.Mutex`) barriers into an asynchronous **Fan-In/Fan-Out channel pipeline framework** utilizing native `sync.Map` scaling states.

#### [forzadrivingai](https://github.com) & [testingdrivingrl](https://github.com)
*Autonomous Vehicle Continuous Physics Driving AI (PyTorch, TorchRL, OpenCV, Gymnasium)*
- Engineered a continuous coordinate Reinforcement Learning workspace mapping screen-captured line boundaries and instantaneous vehicle velocity into live observation tensors.
- Built real-time spatial line-tracking modules utilizing custom **OpenCV geometric ray-casting loops**, reducing raw video data input overhead by 99.8% before deep policy parsing.
- Deployed a probabilistic policy architecture using a **TanhNormal structural distribution** to cleanly bound continuous acceleration, braking, and steering maneuvers.

#### [dLLM](https://github.com)
*Experimental LLM Inference Optimization sandbox (Python, PyTorch)*
- Researched inference optimization layers by modeling **Von Neumann spectral entropy** metrics over final-layer hidden-state Gram matrices to detect semantic repetition trajectories.
- Documented a structural micro-architectural infrastructure post-mortem detailing GPU computation bubbles (>95% execution stalls) caused by KV-Cache socket saturations over generic virtualized networks.

---

### 📊 Production Telemetry Tracks
- 📝 Technical Blog: [null-exception1.github.io/blog](https://github.io)
- 📬 Contact Line: [shauryapsrivastava1@gmail.com](mailto:shauryapsrivastava1@gmail.com)
