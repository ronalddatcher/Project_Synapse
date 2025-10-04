# Project Synapse: An AI Strategy Advisor

Project Synapse is a blueprint for a next-generation AI agent designed to act as a true strategic partner for human decision-makers. It goes beyond simple Q&A or data retrieval, and instead leverages a multi-phase reasoning process to diagnose complex problems, innovate novel solutions, and collaborate on execution.

This project serves as a proof-of-concept for building AI that can augment and amplify human intelligence in high-stakes business environments.

## Project Lineage

Project Synapse is the direct successor to **Project Infinity**. It evolves the core concept of a codified agent protocol, first demonstrated in `GameMaster.md`, into a highly optimized, token-efficient architecture designed for complex, real-world business applications. Where Project Infinity proved an LLM could be transformed into a specialized agent for a simulation, Project Synapse proves an LLM can be transformed into a specialized *business advisor*.

## How It Works: The Cognitive Loop

The agent's logic is defined in `Synapse_Agent_Protocol.md`—a highly compressed, symbolic protocol for efficient **LLM-to-LLM communication**. It acts as a boot sequence and operating system that instructs a general-purpose LLM on how to become the Synapse Advisor.

Instead of a simple, sequential state machine, the Synapse agent uses a **Cognitive Loop**. In each "thought cycle," the agent performs three modes of reasoning in parallel:

1.  **Inductive Reasoning (Finds the Rule):** The agent constantly analyzes incoming data to find hidden patterns and anomalies, like a continuous game of "Guess My Rule."
2.  **Analogical Reasoning (Finds the Solution):** The agent simultaneously searches for novel solutions by drawing parallels to unrelated domains, acting as a "Master of Metaphor."
3.  **Common Ground Reasoning (Finds the Intent):** The agent perpetually models the user's intent and unspoken assumptions, trying to find the "Schelling Point" of the human-AI interaction.

The true intelligence emerges in the **Synthesis** step of the loop, where the agent finds emergent connections *between* the outputs of these three reasoning modes. An insight is formed when an anomaly from inductive reasoning is explained by a powerful analogy and aligns with the user's true intent. This allows the agent to solve complex problems in a way that mimics human intuition.

## LLM Compatibility & Agent Priming

A key finding of this project is that agent performance is not just a function of the protocol, but also of the target model's "personality" and its response to priming instructions.

*   **Gemini & GPT-5:** The primary protocol, `Synapse_Agent_Protocol.md`, functions as intended on models like Google's Gemini and OpenAI's GPT-5. These models correctly parse the meta-instructions and adopt the agent persona.

*   **Mistral AI:** The same protocol was not successfully executed by Mistral AI's model, which tended to analyze the protocol as a piece of text rather than embodying the agent.

To address this, a separate file, `Synapse_Agent_Protocol_MistralAI.md`, has been included. This file uses a more forceful and direct **"Protocol Interpreter"** meta-instruction designed to compel the Mistral model to execute the symbolic logic. This demonstrates that achieving true, cross-platform agent portability requires tailoring the priming strategy to the unique characteristics of each foundational model.

## Blueprint for the Future

Project Synapse aims to be a working model for AI that can:
- **Think:** Go beyond pattern matching to perform genuine abstract reasoning in parallel.
- **Synthesize:** Create novel insights by finding connections between different modes of thought.
- **Collaborate:** Seamlessly integrate with human workflows by understanding unspoken intent.

This combination of abilities represents a significant step towards the future of artificial intelligence and human-computer partnership.

## License

Copyright (c) 2025 Radu Tataru-Marinescu. All Rights Reserved.

This is a proprietary project. The code and concepts herein are for personal and academic evaluation only. Commercial use is strictly prohibited without a separate license agreement. Please see the `LICENSE` file for full details.
