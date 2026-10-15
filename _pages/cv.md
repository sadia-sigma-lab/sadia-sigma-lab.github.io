---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<p><a href="{{ base_path }}/files/Sadia_Asif_CV.pdf" class="btn btn--large">Download full CV (PDF)</a></p>

Research Interests
======
* Trustworthy and privacy-preserving AI
* Machine unlearning and selective forgetting in large models
* Safety and privacy in multi-agent LLM systems
* Alignment-preserving fine-tuning and robust evaluation
* Data valuation and differential privacy for ML ecosystems

Education
======
* **Ph.D. in Computer Science**, Rensselaer Polytechnic Institute, Troy, NY, USA (2024–Present)
  * Advisor: Mohammad Mohammadi Amiri
  * Research Focus: Trustworthy and privacy-preserving AI — machine unlearning, safeguarding multi-agent LLM architectures, information-theoretic privacy control, RL for agent safety, and safety evaluation of large foundation models and agentic systems
* **B.Sc. in Electrical Engineering, Minor in Computer Science**, National University of Sciences and Technology (NUST), Islamabad, Pakistan (2017–2021)
  * Thesis: Developed a deep learning-based EEG abnormality detection system to enhance diagnostic accuracy for healthcare applications

Research and Professional Experience
======
* **Research Extern**, IBM Research, Yorktown Heights, NY (May 2026 – Aug 2026)
  * Mentors: Prasanna Sattigeri, Karthikeyan Natesan Ramamurthy, Momin Abbas
  * Long-Horizon Multi-Agent Risk Trajectory Prediction: developed methods for predicting emerging safety risks and unsafe trajectories across multi-turn interactions in multi-agent tool-calling systems
  * Long-Horizon Agent Safety Benchmark: built a trajectory-level benchmark for evaluating safety in long-horizon tool-using agents across safe completion, unsafe completion, correct refusal, over-refusal, and indeterminate outcomes under diverse multi-turn attack scenarios
* **Research Collaborator**, IBM Research, Yorktown Heights, NY (Jan 2026 – Present)
  * Mentors: Prasanna Sattigeri, Karthikeyan Natesan Ramamurthy, Momin Abbas
  * Investigating security and privacy risks from Key–Value (KV) cache sharing in multi-agent and long-context LLM pipelines, including cross-agent information leakage, representation-level inference attacks, and side-channel vulnerabilities
  * Designing formal threat models and empirical studies to quantify leakage from shared internal representations, toward leakage-bounded and privacy-aware KV-sharing mechanisms
* **Graduate Research Assistant**, Amiri Lab, Rensselaer Polytechnic Institute (Aug 2024 – Present)
  * Advisor: Dr. Mohammad Mohammadi Amiri
  * Machine Unlearning: designed theoretically grounded, computationally efficient unlearning algorithms for LLMs using penalty-based bi-level optimization, achieving strong forget-set removal with minimal retain-set degradation (ICLR 2026)
  * Privacy-Preserving Multi-Agent LLM Systems: developed an information-theoretic framework for privacy control in sequential multi-agent LLM pipelines, formally analyzing representation leakage and safety–utility trade-offs
  * Safe Fine-Tuning of LLMs: investigating alignment-preserving fine-tuning strategies based on representation-level constraints to prevent collapse of refusal behavior and safety boundaries
  * Data Poisoning and Unlearnable Text: studying text-based data poisoning and unlearnable example generation to discourage unauthorized model training on copyrighted or sensitive data
  * Differential Privacy and Data Valuation: designed privacy-aware data valuation mechanisms for multi-seller settings using differential privacy
  * Strategic Planning in LLMs: proposed an artificial oracle framework for anticipatory reasoning in multi-turn interactions, modeling user-response prediction via reinforcement learning and Markov decision processes
* **Head of R&D and Technical Lead**, Quant Data Solutions (Aug 2021 – Aug 2024)
  * Optimized a compensation analysis system for a Silicon Valley firm by fine-tuning and deploying LLMs, including an AI-driven agent to automate large-scale analysis of employee records
  * Analyzed historical time-series data across global exchanges for a leading Chicago HFT firm; implemented algorithmic trading strategies and feature engineering pipelines for ML-based price forecasting
  * Built an end-to-end theft-detection system for streaming video surveillance using YOLO, I3D, AssembleNet, and MoViNet for ATM crime and outdoor theft detection
  * Developed a novel speaker-identification system for multi-speaker recognition in noisy audio, surpassing existing approaches
  * Designed scalable backend systems and database schemas from scratch using Node.js, TypeScript, Redis, and PostgreSQL
  * Led technical teams across diverse stacks, driving code review, bug fixing, and performance optimization best practices
* **Founding Engineer**, E-Mareez Care (Feb 2022 – Present)
  * Designed and implemented a scalable, high-performance backend architecture for healthcare applications (Python, FastAPI, Flask, Node.js, Express.js, TypeScript)
  * Engineered PostgreSQL and Redis integrations for fast, reliable, real-time data processing
  * Integrated monitoring and logging solutions to proactively manage system health and reduce incident response time in production
  * Collaborated with developers and designers on the React.js/Next.js/TypeScript frontend
* **Research Fellow**, Kyung Hee University, AI Robotics Research Lab (Jun 2021 – Sep 2021)
  * Developed deep learning algorithms for brain-controlled drones using EEG motor imagery data
  * Engineered adversarial attack techniques on EEG datasets, evaluating robustness of EEGNet, VGG, Deep CNN, Shallow CNN, TIDNet, and ResNet
  * Worked with Physionet, Amigos, and DEAP EEG datasets to design and validate models under real-world conditions
* **Research Assistant**, SIGMA Research Lab, National University of Sciences and Technology (NUST) (Aug 2020 – Dec 2021)
  * Localized a deep learning-based algorithm for detecting EEG signal abnormalities and implemented gaze-tracking techniques for EEG signal analysis
  * Developed a customized tool for visualizing and annotating EEG signal abnormalities to aid diagnostic workflows
  * Supervised five interns on research projects and organized regular progress meetings

Selected Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Technical Skills
======
* **Programming:** Python, C/C++, JavaScript, TypeScript, SQL, .NET, MATLAB, JAX
* **Frameworks & Libraries:** PyTorch, TensorFlow, Hugging Face, vLLM, Scikit-learn, LlamaIndex, SmolAgents, LangChain, CrewAI, Pandas, NumPy, OpenCV, SciPy, RAG, Streamlit, Node.js, Next.js, React, React Native, Flask
* **Large Language Models:** LLaMA 3.1, Qwen 2.5, Mistral, LongChat, DeepSeek-R1 (inference); long-context and multi-agent LLM pipelines
* **Fine-Tuning & Adaptation:** LoRA, Prefix/Prompt Tuning, Soft Prompting, Representation-Constrained Fine-Tuning
* **Privacy & Alignment:** Differential Privacy (DP-SGD), Opacus, TF-Privacy, privacy auditing and evaluation, safety classifiers, red-teaming and jailbreaking analysis
* **Tools & Systems:** Git, GitHub, Docker, Kafka, AWS, Microsoft Azure, Redis, Postman, Linux, Slurm, Jupyter, LaTeX
* **Databases:** PostgreSQL, MySQL, SQL Server, MongoDB, Firebase

Awards and Recognition
======
* COLM Travel Grant (2026)
* Graduate Student Spotlight Mention for Outstanding Research Performance (2026)
* ICLR Travel Award (2026)
* Grace Hopper Celebration Tech Conference Travel Award (2025)
* Best Data Science Webinar Instructor Award (2023)
* Distinction in UBL Datathon for AI-based ATM Theft Detection Prototype (2022)
* Russian AI and Mathematics Olympiad Winner (2021)
* Academic High Achiever Award, 5th/6th/8th Semester (2020–2021)
* National Talent Scholarship (2017–2021)
* Crossroad Emerging Leader Finalist, Harvard Business School (2020)
* PEEF Merit-Based Scholarship, Provincial Government (2015–2017)

Academic Service
======
* **Area Chair:** Who Verifies the Agents? Workshop @ NeurIPS 2026
* **Program Committee Member:** Bidirectional Human-AI-Alignment Workshop @ NeurIPS 2026
* **Conference Reviewer:** IEEE Conference on AI (CAI) 2026; AAAI (2025, 2026); ICML 2026; COLM 2026; NeurIPS 2026
* **Journal Reviewer:** Machine Intelligence Research; IEEE Transactions on Network Science and Engineering; Informatics for Health and Social Care
* **Teaching Assistant**, RPI: Introduction to Artificial Intelligence, Introduction to Algorithms, Computer Architecture and Operating Systems, Computer Organization

Volunteer / Membership
======
* ICLR 2026 Volunteer, Rio de Janeiro, Brazil
* Microsoft Student Partner, Islamabad
* UN Millennium Fellowship Campus Network Project Member
* Chair, ASWAN ACM Student Chapter
