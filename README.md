# nanorepos

Best minimal-ish repos to collect INCLUDES THESE AREAs

	1.	LLM post-training / alignment
	2.	Evaluation / benchmarking / model editing
	3.	Efficient training & inference
	4.	Agents (method papers, not product frameworks)
	5.	RL for reasoning / decision-making
	6.	Multimodal reasoning
	7.	Generative vision / video / 3D
  
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
