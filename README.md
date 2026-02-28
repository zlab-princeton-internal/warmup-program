# Warmup Program

Welcome! This program is designed for Princeton undergraduates interested in exploring machine learning research. You will get hands-on experience with state-of-the-art open-source projects and GPU clusters — skills that are essential for ML research.

## How It Works

1. **Set up your environment**: Get access to the Adroit cluster and configure your development setup.
2. **Explore open-source repos**: Pick projects from the curated list below that interest you.
3. **Submit bi-weekly reports**: Write a short report about your experience — what you tried, what you learned, what worked, and what didn't.

There are no strict requirements on results. We care about your curiosity and engagement. Just try things out, document your experience honestly, and have fun exploring.

## Step 1: Cluster Setup

You will use Princeton's **Adroit** cluster for GPU access.

1. **Request an account**: Complete the [Adroit registration form](https://forms.rc.princeton.edu/registration/?q=adroit).
2. **Read the scheduler docs**: Review the [SLURM guide](https://researchcomputing.princeton.edu/support/knowledge-base/slurm#gpus) to understand GPU job submission. You can also refer to our [internal Della cluster guide](https://github.com/zlab-princeton-internal/cluster-guide/tree/main/della) for more detailed SLURM examples (Della and Adroit are different clusters, but the SLURM usage is similar).
3. **Recommended GPUs**: Use MIG A100 or V100 on Adroit for development and debugging.

Once your account is approved, verify that you can SSH into the cluster and submit a simple test job.

## Step 2: Explore Repos

Choose any of the following repos to explore. You are free to pick whichever ones interest you. Each report should focus on one repo. **For your first report, we recommend starting with modded-nanogpt** — it's self-contained, runs fast, and gives you a good feel for the workflow.

Not all repos require the Adroit cluster — some can run on your own machine (e.g., with a personal GPU or even CPU for smaller experiments). Repos that need LLM API access (like AI-Scientist-v2) can use Google Cloud's free $300 credit for API keys.

### Beginner-friendly

| Repo | Description |
|------|-------------|
| [modded-nanogpt](https://github.com/KellerJordan/modded-nanogpt) | Speed-optimized GPT training |
| [Diffusers](https://github.com/huggingface/diffusers) | Diffusion model library |
| [nano-vllm](https://github.com/GeeeekExplorer/nano-vllm) | Simple vLLM implementation |

### Intermediate

| Repo | Description |
|------|-------------|
| [OpenEvolve](https://github.com/algorithmicsuperintelligence/openevolve) | Evolutionary agent inspired by AlphaEvolve |
| [Vision-Agents](https://github.com/GetStream/Vision-Agents) | Vision models and agents |
| [Terminal-Bench](https://github.com/laude-institute/terminal-bench) | Terminal agent benchmark |

### Advanced

| Repo | Description |
|------|-------------|
| [AI-Scientist-v2](https://github.com/SakanaAI/AI-Scientist-v2) | Automated scientific discovery |
| [SkyRL](https://github.com/NovaSky-AI/SkyRL) | Scalable reinforcement learning framework |
| [LLaVA-OneVision-1.5](https://github.com/EvolvingLMMs-Lab/LLaVA-OneVision-1.5) | Multimodal training |

**What to do with a repo:**
- Read the README and understand what the project does
- Set up the environment and get it running (on Adroit or your own machine)
- Run the provided examples or experiments
- Try modifying something — change a hyperparameter, swap a component, run on different data
- **Read related papers**: Most repos are built on specific research ideas. Find and read the relevant papers to understand the motivation and methods behind the code. This is a great way to build research intuition.
- Note what you find interesting, surprising, or confusing

You will run into issues — that's expected and part of the learning process. When you get stuck, don't give up. Try debugging on your own first, then reach out and ask for help.

## Step 3: Submit Reports

Submit a short report every **two weeks**. Each report should cover **one repo** you explored during that period.

**Report format** (keep it simple):
- **Repo**: Which repo you worked on
- **Setup**: How you set it up (any issues you ran into)
- **What you tried**: What experiments or modifications you made
- **What you learned**: Key takeaways, interesting findings, or open questions
- **Time spent**: Approximate hours

Reports don't need to be long or polished. A few paragraphs is fine. We value honest documentation of your experience over impressive results.

Reports can be short, but submitting them on time is a firm requirement. If you're stuck, ask questions — consistent engagement is what matters most.

**Submission**: Send your report to [Taiming Lu](mailto:tl0463@princeton.edu) via email.

## Questions

For any questions about the program, cluster setup, or repo selection, contact [Taiming Lu](mailto:tl0463@princeton.edu) via email or Slack.
