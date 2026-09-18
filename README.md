# Hey, I'm Ayush 👋

I'm a Computer Science + Computer Engineering student at the University of Wisconsin–Madison, graduating in May 2027.

I like building systems that sit somewhere between backend infrastructure, AI, and lower-level computing. Most of the projects I enjoy involve figuring out how the pieces actually work together — from an agent running asynchronously in production, to a graph algorithm, to a pipelined processor.

I've also spent the last two summers at Amazon. Most recently, I built an autonomous AI agent and the infrastructure for secure asynchronous execution, and worked on scaling an existing agent to 100,000 users. Before that, I worked on backend data and notification systems for Amazon Relay.
I'm especially interested in:

* Backend & distributed systems
* AI infrastructure and agent systems
* Building products end-to-end
* Hardware-software systems

## A few things I've built

### [SoloSheet](trysolosheet.com)

repo - https://github.com/ayusharma17/SoloSheet

I built SoloSheet because making dense exam reference sheets manually is tedious. It takes lecture PDFs and turns them into print-ready sheets that fit an exact page limit.

The interesting part is the generation loop: Gemini restructures and compresses the content, LaTeX renders it, and the system keeps iterating until the output satisfies the user's page-count and formatting constraints.

Built with React, TypeScript, Supabase, PostgreSQL, Gemini, and LaTeX.

### [JuliaPhylo](https://github.com/JuliaPhylo)

I spent over a year contributing to open-source phylogenetics software at UW–Madison.

Most of my work was on graph algorithms for phylogenetic networks — including early work on [PhyloSummaries.jl](https://github.com/JuliaPhylo/PhyloSummaries.jl) and algorithms for comparing large networks in [PhyloNetworks.jl](https://github.com/JuliaPhylo/PhyloNetworks.jl).

This was probably my first experience working deeply in a real open-source codebase rather than building something from scratch.

### 5-Stage RISC-V Processor

One of my favorite hardware projects was building a 32-bit pipelined RISC-V processor with a team of four.

We implemented the pipeline, forwarding, hazard handling, branch prediction, and FPGA deployment ourselves. Debugging it mostly meant staring at waveforms until the processor finally did what we thought it was doing.

### [Tricking AI Detectors](https://github.com/ayusharma17/Tricking-AI-Detectors-ECE539)

This started as a question: **how reliable are AI-text detectors when the generator actively tries to fool them?**

I built a classifier for human vs. AI-generated text, then used its confidence score to guide an iterative generate-score-select loop. I also fine-tuned TinyLlama-1.1B with LoRA to study whether detector scores could be systematically improved.

[LinkedIn](https://www.linkedin.com/in/ayushsharma17/) · [Resume](https://drive.google.com/file/d/1hcRfZ8a-tZ64DYEU9OHKcX4-UvIsFGuF/view?usp=sharing)
