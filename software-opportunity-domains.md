# Software Opportunity Domains

This document is the domain map for researching unusually powerful, abandoned, discontinued, underused, or historically premature software technologies that may become commercially or strategically valuable if rebuilt with modern hardware and software.

The goal is **not** to collect interesting software for curiosity. Candidates should have a clear technical advantage, an identifiable market, and a realistic path toward a product, engine, platform component, SDK, infrastructure layer, or strategic technology.

## Core software domains

### 1. Graphics, Rendering & Geometry Engines
- Real-time rendering
- Virtual geometry
- Voxel / sparse voxel octree rendering
- Point-cloud rendering
- Massive-scene visualization
- Ray tracing / path tracing
- Global illumination
- Volumetric rendering
- Neural rendering
- Geometry streaming
- LOD / continuous detail systems
- CAD / BIM visualization
- Out-of-core rendering
- Procedural geometry

### 2. Game & Interactive Simulation Engines
- General-purpose game engines
- Large-world streaming
- Destruction engines
- Physics-based worlds
- Procedural world generation
- Deterministic simulation
- Multiplayer world-state engines
- ECS / data-oriented runtimes
- Live simulation systems

### 3. Physics Engines
- Rigid-body physics
- Soft-body physics
- Cloth
- Fluids
- Granular materials
- Fracture / destruction
- Multi-physics coupling
- GPU / distributed physics
- Real-time engineering physics

### 4. CAD, BIM & Engineering Kernels
- Solid modeling
- B-Rep kernels
- CSG
- Parametric modeling
- Geometric constraints
- Feature-history engines
- Mesh healing / repair
- Boolean engines
- CAM geometry
- IFC / BIM kernels
- Digital twins
- Computational geometry
- Geometry interoperability

### 5. Compilers, Runtimes & Binary Translation
- JIT / AOT compilers
- Dynamic binary translation
- x86 ↔ ARM ↔ RISC-V translation
- Cross-ISA compatibility
- Legacy application execution
- VM / bytecode runtimes
- Language runtimes
- Auto-vectorization
- Heterogeneous CPU/GPU execution
- Profile-guided optimization
- Incremental compilation

### 6. Distributed Compute & Cluster Software
- Transparent process migration
- Distributed memory
- GPU pooling
- Multi-PC compute aggregation
- Local AI clusters
- Heterogeneous compute scheduling
- Render farms
- HPC runtimes
- Edge compute
- Fault-tolerant execution
- Resource virtualization

### 7. AI Infrastructure & Model Engines
- Inference runtimes
- Model serving
- Distributed inference
- Distributed training
- Model compression
- Quantization
- Sparse execution
- Mixture-of-experts routing
- KV-cache management
- Memory-efficient inference
- On-device AI
- Edge AI
- Agent runtimes
- AI accelerators / compiler stacks

### 8. Databases & Storage Engines
- Relational engines
- Distributed databases
- Object databases
- Graph databases
- Temporal databases
- Vector databases
- In-memory databases
- Columnar storage
- Time-series engines
- Event stores
- Log-structured engines
- Massive indexing systems
- Deduplication
- Compression-aware storage

### 9. Filesystems & Data Architecture
- Transactional filesystems
- Versioned filesystems
- Content-addressed storage
- Distributed filesystems
- Copy-on-write systems
- High-performance small-file storage
- Snapshotting
- Data provenance
- Immutable storage
- Local-first synchronization

### 10. Networking & Communication Engines
- Low-latency networking
- Zero-copy networking
- Peer-to-peer stacks
- Overlay networks
- Distributed messaging
- Replication protocols
- Multiplayer synchronization
- Remote desktop protocols
- Application streaming
- Congestion-control engines
- Mesh networking
- Offline-first networking

### 11. Scientific & Industrial Simulation
- CFD
- FEM
- Structural analysis
- Electromagnetics
- Thermodynamics
- Molecular simulation
- Multibody dynamics
- Chemical simulation
- Weather / climate computation
- Process simulation
- Industrial digital twins
- Real-time simulation

### 12. Computer Vision & Spatial Computing
- SLAM
- Visual odometry
- Photogrammetry
- 3D reconstruction
- Point-cloud processing
- Depth estimation
- Localization
- Mapping
- Scene understanding
- Neural fields
- Spatial indexing
- Large-scale geospatial reconstruction

### 13. Robotics & Autonomous Systems
- Robot operating runtimes
- Motion planning
- Path planning
- Multi-robot coordination
- Autonomous control
- Sensor fusion
- Manipulation
- Industrial robotics
- Drone autonomy
- Vehicle autonomy
- Robotics simulation

### 14. Media, Video & Audio Engines
- Video codecs
- Audio codecs
- Real-time transcoding
- Video processing
- Image processing
- Media streaming
- Ultra-low-latency conferencing
- Procedural audio
- Speech processing
- DSP engines
- GPU media pipelines

### 15. Search, Indexing & Information Retrieval
- Full-text search
- Semantic search
- Approximate nearest-neighbor search
- Similarity search
- Geometric search
- Large-scale indexing
- Incremental indexing
- Compressed indexes
- Knowledge retrieval engines

### 16. Compression & Data Reduction
- General compression
- Domain-specific compression
- Geometry compression
- Point-cloud compression
- Scientific-data compression
- Video / image compression
- Deduplication
- Delta encoding
- Learned compression

### 17. Security & Systems Software
- Sandboxing
- Capability-based security
- Isolation runtimes
- Secure execution
- Trusted computing
- Encrypted computation
- Privacy-preserving computation
- Secure enclaves
- Policy engines
- Fine-grained permissions
- Memory-safe systems

### 18. Operating-System Components
> Focus on components that can become standalone technology, not on rebuilding an entire OS without a market.

- Schedulers
- Memory managers
- Virtual memory
- IPC
- Driver frameworks
- Userspace kernels
- Filesystem layers
- Resource managers
- Compatibility layers
- Containers / isolation primitives
- Process models

### 19. Developer Tools & Programming Environments
- Live programming
- Visual programming
- Incremental programming
- Advanced debuggers
- Time-travel debugging
- Program synthesis
- Static analysis
- Dynamic analysis
- Code intelligence
- Interactive language environments
- Self-hosting systems

### 20. EDA & Chip Design Software
- Logic synthesis
- Placement and routing
- Circuit simulation
- FPGA tools
- Formal verification
- HDL tooling
- Hardware/software co-design
- Chiplet design
- Packaging simulation
- Semiconductor process simulation

### 21. Optimization, Solvers & Mathematical Engines
- Constraint solvers
- SAT / SMT
- Linear programming
- Mixed-integer optimization
- Nonlinear optimization
- Symbolic mathematics
- Automatic differentiation
- Numerical solvers
- Sparse linear algebra
- Scheduling optimizers

### 22. Enterprise & Infrastructure Engines
- Workflow engines
- Rule engines
- Transaction engines
- Event-processing engines
- Integration middleware
- Message brokers
- Business-process engines
- Enterprise search
- High-scale backend runtimes

### 23. Geospatial & Mapping Engines
- GIS kernels
- Massive terrain rendering
- LiDAR processing
- Geospatial databases
- Route engines
- Spatial analytics
- Satellite imagery processing
- 3D city engines
- Geospatial digital twins

### 24. Manufacturing & Industrial Software
- CNC / CAM engines
- Process control
- PLC programming environments
- Factory simulation
- Scheduling
- Quality-control software
- Digital manufacturing
- Generative manufacturing
- Toolpath optimization

### 25. Energy & Infrastructure Software
- Power-grid simulation
- Grid optimization
- Battery simulation
- Energy-management systems
- Renewable forecasting
- Utility digital twins
- Industrial control
- Load balancing

### 26. Logistics & Operations Engines
- Routing
- Fleet optimization
- Warehouse optimization
- Supply-chain simulation
- Scheduling
- Dispatch engines
- Packing / bin-packing
- Real-time operations optimization

### 27. Financial & Quantitative Engines
- Low-latency market infrastructure
- Risk engines
- Portfolio optimization
- Pricing engines
- Backtesting runtimes
- Time-series computation
- Fraud / anomaly engines

### 28. Formal Methods & Verification
- Theorem provers
- Model checking
- Formal verification
- Proof-carrying code
- Verified compilation
- Hardware verification
- Safety-critical verification
- Specification languages

### 29. Knowledge Representation & Semantic Systems
- Knowledge graphs
- Semantic object systems
- Ontology engines
- Executable knowledge
- Rule-based reasoning
- Scientific knowledge representation
- Machine-readable documents
- Semantic interoperability

### 30. Human–Computer Interaction Engines
> Only include technologies with a clear productivity or commercial advantage, not novelty-only UI concepts.

- New input paradigms
- Adaptive interfaces
- Accessibility engines
- Context-aware UI
- Multimodal interaction
- High-efficiency professional interfaces
- Spatial interaction where it solves a real workflow problem

### 31. Collaboration & Shared-State Engines
- Real-time co-editing
- CRDT / OT systems
- Shared simulation state
- Collaborative CAD / BIM
- Multiplayer creation tools
- Distributed undo / history
- Offline collaboration

### 32. Digital Twin & State-Synchronization Platforms
- Physical ↔ digital state mapping
- Sensor-driven models
- Simulation synchronization
- Asset-state engines
- Industrial twins
- City / infrastructure twins
- Predictive maintenance

### 33. Knowledge-to-Execution Systems
- Equation → executable model
- Specification → simulation
- Document → structured model
- Natural language → verified workflow
- Scientific paper → executable experiment
- Standard / regulation → compliance engine

### 34. Legacy Modernization & Compatibility Software
- Old API compatibility
- Legacy binary execution
- Runtime shims
- ABI translation
- Old database migration
- Mainframe modernization
- Application virtualization
- Cross-platform compatibility

### 35. Cloud, Edge & Serverless Runtimes
- Ultra-light VMs
- Function runtimes
- Cold-start elimination
- Edge orchestration
- Stateful serverless
- Distributed state
- MicroVMs
- Workload migration

### 36. Dataflow & Stream-Processing Engines
- DAG execution
- Real-time streams
- Reactive computation
- Incremental computation
- Event-time processing
- Distributed dataflow
- Stateful streaming

### 37. Procedural & Generative Systems
- Procedural geometry
- Procedural worlds
- Generative CAD
- Generative engineering
- Rule-based design
- Constraint-driven generation
- Parametric asset systems

### 38. Large-Scale World / Scene Databases
- Persistent 3D worlds
- Scene graphs at massive scale
- Spatial object databases
- Streaming world state
- Hierarchical scene storage
- City-scale / planet-scale datasets

### 39. Memory, Cache & Data-Movement Engines
- Memory compression
- NUMA optimization
- Persistent memory
- Tiered memory
- GPU memory virtualization
- Remote memory
- High-speed cache engines
- Zero-copy data movement

### 40. Scheduling & Resource-Orchestration Engines
- CPU / GPU / NPU scheduling
- Cluster scheduling
- Deadline scheduling
- Energy-aware scheduling
- Distributed resource allocation
- AI-workload scheduling
- Dynamic workload placement

## Market / buyer classification

Every candidate should also be tagged by likely buyer or market:

- **Mass-market / B2C**
- **Gaming**
- **Creator tools**
- **Developer infrastructure**
- **Enterprise software**
- **AI infrastructure**
- **Cloud / datacenter**
- **Industrial / manufacturing**
- **Architecture / construction / BIM**
- **Scientific / research**
- **Robotics / autonomous systems**
- **Semiconductor / hardware**
- **Geospatial**
- **Energy / infrastructure**
- **Finance**
- **Defense / strategic technology**
- **Government / public infrastructure**

## Candidate evaluation criteria

A historical or abandoned technology should be investigated further when several of these are true:

1. It had a **fundamental technical advantage**, not merely a nicer UI.
2. It failed because of timing, hardware limits, distribution, financing, corporate strategy, or ecosystem problems rather than because the core idea was useless.
3. Modern CPUs, GPUs, NPUs, SSDs, networking, AI, or cloud infrastructure remove an old limitation.
4. There is a **clear present-day customer** willing to pay.
5. The technology can become a standalone engine, SDK, product, infrastructure layer, or strategic IP.
6. Existing modern competitors still have an obvious architectural weakness it could exploit.
7. A small or medium team can build a meaningful prototype without first rebuilding an entire ecosystem.
8. The idea has a defensible technical moat.
9. Performance or capability can be demonstrated with a simple benchmark that buyers immediately understand.
10. Legal / IP conditions allow a clean-room reimplementation, open-source continuation, licensing, or acquisition path.

## Red flags

Avoid spending serious effort on candidates where:

- The only advantage is nostalgia or novelty.
- The product needs an entirely new operating system or hardware ecosystem before it becomes useful.
- There is no obvious buyer.
- Modern alternatives already solve the same problem well enough.
- The idea is impressive only in demos but weak in production workloads.
- The original limitation still exists today.
- IP ownership makes commercialization unrealistic.
- Rebuilding it requires hundreds of engineers before any value can be demonstrated.

## Priority research domains

For the first deep search, prioritize:

1. Graphics / geometry / virtual matter
2. CAD / BIM / geometric kernels
3. Compilers / runtimes / binary translation
4. Distributed GPU / compute
5. AI infrastructure
6. Databases / storage
7. Physics / industrial simulation
8. Computer vision / spatial computing
9. Optimization / solvers
10. EDA / chip design
11. Networking / low-latency systems
12. Compression / indexing

These areas are most likely to contain technologies that were historically limited by hardware or timing but could now become commercially meaningful.