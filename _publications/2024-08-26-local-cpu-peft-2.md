---
title: "Enhancing Medical Summarization with Parameter Efficient Fine Tuning on Local CPUs"
collection: publications
category: conferences
permalink: /publication/2024-08-26-local-cpu-peft
date: 2024-08-26
venue: "ICECCE 2024"
status: "Oral Presentation"
authors: "**S. Sim**, M.F. Goh, W.C. Yap, Z.Y. Diong"
author_role: "First Author"
collaborators: "Intel Malaysia"
collaborator_logo: "/images/collab/intel.png"
paperurl: "https://ieeexplore.ieee.org/document/10823619"
excerpt: "A cost-effective, privacy-aware approach to clinical summarization that fine-tunes Llama 3 8B on CPUs using QLoRA together with IPEX-LLM and Intel AMX optimizations."
---

Documenting and summarizing patient symptoms and medical history for each visit can significantly burden clinicians' time management. Large Language Models (LLMs) have demonstrated great potential in natural language processing (NLP) tasks; however, their effectiveness in clinical summarization tasks has not yet been rigorously validated. While much research has focused on leveraging closed LLMs like GPT-4, Claude, and Gemini for clinical applications, privacy concerns hinder their deployment in real clinical settings. On-premises deployment offers a potential solution.

This study examines domain adaptation techniques on the open-source LLM, Llama 3 8B Instruct, to improve clinical summarization. Our approach emphasizes fine-tuning on CPUs instead of the more commonly used GPUs, aiming for greater cost savings in practical applications. We apply Quantized Low-Rank Adaptation (QLoRA) for efficient task-specific adaptation and introduce CPU optimization techniques such as IPEX-LLM and Intel® AMX to enhance performance. Our results show that CPU fine-tuning, while less conventional than GPU-based methods, still provides a practical, cost-effective, and privacy-aware solution for on-premises deployment, supporting the accuracy of medical summarization and enabling customization according to unique clinical requirements.
