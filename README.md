# Context
This repo follows the awesome-list software trend and is a curated collection of open resources for chemical security, dual-use chemistry, chemical risk, and chemical safety. There will inevitably be a lot of overlap with biosecurity but since there are already many reseources online tackling it, the core focuse here will be around chem. The focus is around science, evaluations, benchmarks, red teaming, safeguards, AI4science, and governance.

## Contents

- [Benchmarks and Evaluations](#benchmarks-and-evaluations)
- [Red Teaming and Uplift Studies](#red-teaming-and-uplift-studies)
- [Safeguards and Mitigations](#safeguards-and-mitigations)
- [AI4Science and Autonomous Agents](#ai-for-science-and-autonomous-agents)
- [Biosecurity](#biosecurity)
- [Frontier Safety Frameworks](#frontier-safety-frameworks)
- [Policy, Governance, and Treaties](#policy-governance-and-treaties)
- [Chemical Safety Data](#chemical-safety-data)
- [Contributing](#contributing)

## Benchmarks and Evaluations

- [WMDP Benchmark](https://www.wmdp.ai/) ([paper](https://arxiv.org/abs/2403.03218)): A multiple-choice proxy benchmark for hazardous knowledge in biosecurity, cybersecurity, and chemical security. It also introduces the RMU unlearning method.
- [ChemBench](https://github.com/lamalab-org/chembench) ([paper](https://arxiv.org/abs/2404.01475)): A framework that measures LLM chemical knowledge and reasoning against human chemists, including toxicity and safety questions.
- [ChemSafetyBench](https://arxiv.org/abs/2411.16736): A benchmark of more than 30K samples on chemical properties, legality of use, and synthesis requests, built to test LLM safety in chemistry.
- [SOSBench](https://arxiv.org/abs/2505.21605): A regulation-grounded safety benchmark of 3,000 hazardous prompts across six scientific domains, including chemistry.
- [SciKnowEval](https://arxiv.org/abs/2406.09098): A multi-level scientific knowledge benchmark for chemistry and biology that includes a safety and ethics dimension.
- [LAB-Bench](https://arxiv.org/abs/2407.10362): A benchmark from FutureHouse covering practical biology research tasks such as protocols, literature, and sequence manipulation.
- [Virology Capabilities Test (VCT)](https://arxiv.org/abs/2504.16137): A multimodal benchmark from SecureBio that tests troubleshooting of expert-level virology protocols.
- [HarmBench](https://arxiv.org/abs/2402.04249): A standardized framework for automated red teaming and robust refusal, with a chemical and biological weapons category.
- [Inspect Evals](https://github.com/UKGovernmentBEIS/inspect_evals): A community collection of evaluations for the UK AISI's Inspect framework, including several science and dangerous-capability evals.
- [SecureBio AI Benchmarks Dashboard](https://securebio.substack.com/p/introducing-securebios-trends-in): A dashboard tracking frontier model performance on biosecurity-relevant benchmarks over time.

## Red Teaming and Uplift Studies

- [Frontier Threats Red Teaming for AI Safety (Anthropic)](https://www.anthropic.com/news/frontier-threats-red-teaming-for-ai-safety): Anthropic's approach to expert-led red teaming for catastrophic misuse, using biology as a test case.
- [Building an Early Warning System for LLM-Aided Biological Threat Creation (OpenAI)](https://openai.com/index/building-an-early-warning-system-for-llm-aided-biological-threat-creation/): A human uplift study with 100 participants that compares internet-only access to internet plus GPT-4.
- [The Operational Risks of AI in Large-Scale Biological Attacks (RAND)](https://www.rand.org/pubs/research_reports/RRA2977-2.html): A red-team study in which expert teams planned attacks with and without LLM access.
- [Can Large Language Models Democratize Access to Dual-Use Biotechnology?](https://arxiv.org/abs/2306.03809): An early classroom exercise testing whether chatbots help non-experts with pandemic-pathogen-related information.
- [GPT-4 System Card](https://cdn.openai.com/papers/gpt-4-system-card.pdf): An early public example of expert red teaming for chemical and biological risks before deployment, including chemistry tool augmentation.
- [Dual Use of Artificial-Intelligence-Powered Drug Discovery](https://www.nature.com/articles/s42256-022-00465-9): A landmark paper by Urbina et al. showing that a toxicity-prediction model could be inverted to generate VX-like nerve agent candidates.

## Safeguards and Mitigations

- [Constitutional Classifiers](https://arxiv.org/abs/2501.18837): Input and output classifiers trained on a constitution to block universal jailbreaks for CBRN content, tested with thousands of hours of red teaming.
- [Deep Ignorance](https://arxiv.org/abs/2508.06601): Shows that filtering hazardous data out of pretraining builds tamper-resistant safeguards into open-weight models.
- [Risks of AI Scientists: Prioritizing Safeguarding Over Autonomy](https://arxiv.org/abs/2402.04247): A survey of the vulnerabilities of autonomous scientific agents, including chemistry, with a proposed safeguarding framework.

## AI4Science and Autonomous Agents

- [ChemCrow](https://arxiv.org/abs/2304.05376): An LLM agent augmented with 18 chemistry tools, with a discussion of safety measures for controlled substances.
- [Coscientist](https://www.nature.com/articles/s41586-023-06792-0): A GPT-4-driven system that autonomously designs, plans, and runs chemical experiments in a cloud lab.
- [Emergent Autonomous Scientific Research Capabilities of LLMs](https://arxiv.org/abs/2304.05332): An early demonstration of an autonomous research agent, including red-teaming of its willingness to synthesize controlled and dangerous substances.

## Biosecurity

- [The Age of AI in the Life Sciences (National Academies)](https://www.nationalacademies.org/read/28868): A 2025 consensus report on the benefits and biosecurity considerations of AI-enabled biological tools.
- [Responsible AI x Biodesign](https://responsiblebiodesign.ai/): A community statement of values, principles, and commitments for responsible AI protein design, signed by over 170 scientists.
- [Frontier Model Forum Publications](https://www.frontiermodelforum.org/publications/): Industry issue briefs on AI-bio threat models, safety evaluation taxonomies, thresholds, and multilingual CBRN evaluations.

## Frontier Safety Frameworks

- [Anthropic Responsible Scaling Policy](https://www.anthropic.com/responsible-scaling-policy): Defines AI Safety Levels and CBRN capability thresholds that trigger stronger safeguards.
- [OpenAI Preparedness Framework](https://openai.com/index/updating-our-preparedness-framework/): OpenAI's framework for tracking and mitigating severe risks, with biological and chemical capability as a tracked category.
- [Google DeepMind Frontier Safety Framework](https://deepmind.google/discover/blog/introducing-the-frontier-safety-framework/): Critical capability levels, including CBRN, with corresponding evaluation and mitigation protocols.

## Policy, Governance, and Treaties

- [International AI Safety Report](https://internationalaisafetyreport.org/): An independent, internationally backed scientific assessment of general-purpose AI risks, with a dedicated section on biological and chemical risks.
- [OPCW Report on AI and the Chemical Weapons Convention](https://www.opcw.org/media-centre/news/2026/03/opcw-releases-landmark-report-ai-and-chemical-weapons-convention): The 2026 report of the OPCW Scientific Advisory Board's Temporary Working Group on AI.
- [Chemical Weapons Convention (OPCW)](https://www.opcw.org/chemical-weapons-convention): The full text of the treaty and its schedules of controlled chemicals.

## Chemical Safety Data

- [PubChem](https://pubchem.ncbi.nlm.nih.gov/): An NIH open chemistry database with hazard, toxicity, and GHS safety data for millions of compounds.
- [CAMEO Chemicals (NOAA)](https://cameochemicals.noaa.gov/): A database of hazardous chemical datasheets and a reactivity predictor for emergency responders.

## Contributing

Contributions are welcome! To suggest a resource:

1. Fork this repository.
2. Add your resource to the most relevant section, in the format `- [Name](link): One-sentence description.`
3. Open a pull request with a short note on why the resource is relevant.

If you're not sure where something fits, or want to suggest a new section, feel free to open an issue instead.

Please only add publicly available resources. Do not submit links to content that provides actionable instructions for producing chemical or biological weapons.
