# nanorepos

Best minimal-ish repos to collect INCLUDES THESE AREAs

	1.	LLM post-training / alignment
	2.	Evaluation / benchmarking
	3.	Efficient training & inference
	4.	Agents (method papers, not product frameworks)
	5.	RL for reasoning / decision-making
	6.	Multimodal reasoning
	7.	Generative vision / video / 3D
## LeJepaWORLD:
https://github.com/lucas-maes/le-wm

# LLM post-training / alignment 
## 1) [princeton-nlp/SimPO](https://github.com/princeton-nlp/SimPO)
- **Paper:** *SimPO: Simple Preference Optimization with a Reference-Free Reward*
- **Venue:** **NeurIPS 2024 (Poster)**
- **Why keep:** best overall balance of **recent + important + reasonably well-known + still fairly compact**
- **Repo shape:** `README.md`, `environment.yml`, `run_simpo.py`, `generate.py`, plus small folders like `alignment/`, `eval/`, and `training_configs/`
- **Best for:** strongest recent anchor repo in this area

## 2) [SimPER-ICLR/SimPER](https://github.com/SimPER-ICLR/SimPER)
- **Paper:** *SimPER: A Minimalist Approach to Preference Alignment without Hyperparameters*
- **Venue:** **ICLR 2025 (Poster)**
- **Why keep:** the most explicitly **minimalist recent method** in this group
- **Repo shape:** `README.md`, `environment.yml`, with `alignment/`, `eval/`, `scripts/`, and `training_configs/`
- **Best for:** newest minimalist-style preference alignment repo

## 3) [junkangwu/Dr_DPO](https://github.com/junkangwu/Dr_DPO)
- **Paper:** *Towards Robust Alignment of Language Models: Distributionally Robustifying Direct Preference Optimization*
- **Venue:** **ICLR 2025 (Poster)**
- **Why keep:** cleanest repo layout among the three
- **Repo shape:** `README.md`, `requirements.txt`, `train.py`, `trainers.py`, `utils.py`, `preference_datasets.py`
- **Best for:** pure repo minimality
## 4) [Direct Preference Optimization](https://github.com/eric-mitchell/direct-preference-optimization)
Paper: "Direct Preference Optimization: Your Language Model is Secretly a Reward Model" — ICLR 2024 (Spotlight)


# Efficient training & inference — repos to collect

## 1) [microsoft/MInference](https://github.com/microsoft/MInference)
- Area: Efficient inference / long-context acceleration
- Venue signal: NeurIPS 2024 Spotlight, later extended at ICLR 2025 and ICML 2025
- Why keep: strongest anchor repo, fairly famous, very important problem
- Caveat: not minimalistic enough to be your pure minimal pick

## 2) [shadowpa0327/Palu](https://github.com/shadowpa0327/Palu)
- Area: Efficient inference / KV-cache compression
- Venue signal: ICLR 2025
- Why keep: best balance of minimal + important in this area
- Best for: your “minimal runnable research repo” criterion

## 3) [junzhang-zj/LoRAM](https://github.com/junzhang-zj/LoRAM)
- Area: Efficient training / memory-efficient fine-tuning
- Venue signal: ICLR 2025 Poster
- Why keep: strong recent training-side repo, more compact than framework-style PEFT repos
- Best for: efficient training bucket

# Agents (method papers, not product frameworks) — repos to collect

> In this area, truly minimalist repos are rarer than in alignment.
> So the right strategy is:
> - **1 famous anchor repo**
> - **1 best recent method repo**
> - **1 smallest collectible repo**

---

## 1) [FoundationAgents/AFlow](https://github.com/FoundationAgents/AFlow)
- **Paper:** *AFlow: Automating Agentic Workflow Generation*
- **Venue:** **ICLR 2025 Oral**
- **Why keep:** strongest **anchor repo** in this area
- **What it does:** automatically searches and optimizes agent workflows instead of hand-designing them
- **Why it matters:** oral at ICLR 2025, clearly high paper signal
- **Repo style:** method/framework hybrid, not fully minimal
- **Use it as:** the **best famous repo** for agent methods

### Minimality verdict
- not your pure `train.py + eval.py + README` style
- still worth keeping because the paper signal is unusually strong

---

## 2) [tsinghua-fib-lab/AgentSquare](https://github.com/tsinghua-fib-lab/AgentSquare)
- **Paper:** *AgentSquare: Automatic LLM Agent Search in Modular Design Space*
- **Venue:** **ICLR 2025**
- **Why keep:** best balance of **recent + agent-method focus + research code**
- **What it does:** searches over modular agent designs with planning, reasoning, tool-use, and memory modules
- **Why it matters:** directly about **agent design as a method problem**, not a product stack
- **Repo style:** modular research repo with code, prompts, and results
- **Use it as:** the **best recent method repo** in this area

### Minimality verdict
- not flat-minimal
- but much closer to a paper repo than a full agent platform

---

## 3) [co-evolve-lab/magis](https://github.com/co-evolve-lab/magis)
- **Paper:** *MAGIS: LLM-Based Multi-Agent Framework for GitHub Issue Resolution*
- **Venue:** **NeurIPS 2024**
- **Why keep:** strongest **task-specific multi-agent method repo** I found that is still collectible
- **What it does:** uses specialized agents for software issue resolution
- **Why it matters:** NeurIPS 2024 paper, focused multi-agent design, narrower scope than general-purpose agent frameworks
- **Repo style:** smaller and more task-bounded than AFlow
- **Use it as:** the **smallest collectible repo** of the three

### Minimality verdict
- still not perfectly minimal
- but more bounded and less framework-like than many agent repos


# Decesion making
- [dcmpc] (https://github.com/aidanscannell/dcmpc)

# Reasoning LLM

## 1) [GAIR-NLP/LIMO](https://github.com/GAIR-NLP/LIMO)
- Conference: COLM 2025
- Why keep: recent, important, fairly visible, and the closest to a minimal reasoning repo
- Best for: reasoning fine-tuning

## 2) [simplescaling/s1](https://github.com/simplescaling/s1)
- Conference: ICLR 2025 / EMNLP 2025
- Why keep: compact repo for test-time scaling and reasoning
- Best for: inference-time reasoning

## 3) [Open-Reasoner-Zero/Open-Reasoner-Zero](https://github.com/Open-Reasoner-Zero/Open-Reasoner-Zero)
- Project: open reasoning-RL
- Why keep: strongest famous anchor repo in open reasoning
- Best for: reasoning-RL training
