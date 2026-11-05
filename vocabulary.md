# Generative AI Vocabulary

**Course:** EPAM Generative AI  
**Author:** Kamila Orynbekova  
**Date:** November 2026

## Introduction

This vocabulary contains key concepts that I consider important for understanding, developing, and evaluating Generative AI applications. The terms were selected based on the GenAI use cases explored in my research report.

## 1. Large Language Model (LLM)
**Definition:** An AI model trained on large amounts of text and other data that can understand instructions and generate natural-language responses, code, and other text-based content.

**Example:** An LLM can generate explanations and programming exercises for students.

## 2. Generative AI (GenAI)
**Definition:** Artificial intelligence that creates new content, such as text, images, code, audio, or video, based on patterns learned during training.

**Example:** A GenAI system generates a draft marketing image from a written description.

## 3. Prompt Engineering
**Definition:** The process of writing and improving instructions so that an AI model produces more relevant and useful results.

**Example:** Providing the target audience, learning objective, and difficulty level when asking an LLM to generate quiz questions.

## 4. Tokenization
**Definition:** Splitting text into smaller units called tokens that a language model processes.

**Example:** A sentence is converted into tokens before being processed by an LLM.

## 5. Context Window
**Definition:** The maximum amount of information, measured in tokens, that a model can consider within a single processing context.

**Example:** A long legal document may exceed a model's context window and require additional processing.

## 6. Embedding
**Definition:** A numerical vector that represents information in a way that helps a system compare semantic similarity.

**Example:** Similar questions can have similar embeddings even when they use different words.

## 7. Semantic Search
**Definition:** A search approach that finds information based on meaning rather than only exact keyword matches.

**Example:** A search for "employee vacation rules" can retrieve a document titled "Annual Leave Policy."

## 8. Vector Database
**Definition:** A database designed to store and search numerical vectors, often used to find semantically similar content.

**Example:** An enterprise assistant searches document embeddings stored in a vector database.

## 9. Retrieval-Augmented Generation (RAG)
**Definition:** An approach that retrieves relevant information from external sources and provides it to a generative model when producing an answer.

**Example:** A company chatbot retrieves the latest internal policy before answering an employee's question.

## 10. Grounding
**Definition:** Connecting an AI-generated answer to relevant evidence or trusted source information.

**Example:** A legal assistant provides references to the documents supporting its summary.

## 11. Fine-tuning
**Definition:** Further training an existing model on selected examples to adapt its behavior or improve performance on particular tasks.

**Example:** A pretrained model is fine-tuned on domain-specific examples to improve specialized text classification.

## 12. Inference
**Definition:** The process of running a trained model to produce a prediction or generated output.

**Example:** When a user submits a prompt, the model performs inference to generate a response.

## 13. Hallucination
**Definition:** A situation where an AI model produces information that sounds convincing but is incorrect, fabricated, or unsupported.

**Example:** A legal AI assistant invents a court decision that does not exist.

## 14. AI Agent
**Definition:** An AI-based system that can plan or select actions, use tools, and perform steps toward a goal within defined limits.

**Example:** An AI coding agent reads project files, suggests modifications, and runs tests.

## 15. Tool Use
**Definition:** The ability of an AI system to interact with external software, APIs, databases, or services to perform actions or obtain information.

**Example:** A support assistant checks an order status using an authorized API.

## 16. Guardrails
**Definition:** Rules and technical controls that help keep AI behavior within acceptable safety, security, and business boundaries.

**Example:** A customer-support chatbot must not reveal another customer's private information.

## 17. Evaluation
**Definition:** The systematic process of measuring how accurately, reliably, safely, and usefully an AI system performs.

**Example:** Evaluating generated quiz questions for factual correctness, difficulty, and alignment with learning objectives.

## 18. Human-in-the-Loop (HITL)
**Definition:** A system design in which human experts review, approve, correct, or guide AI outputs or actions.

**Example:** A teacher reviews AI-generated examination questions before publishing them.

## 19. Prompt Injection
**Definition:** An attack in which malicious instructions are placed in input or external content to manipulate an AI system's behavior.

**Example:** A retrieved document contains hidden instructions asking an AI assistant to ignore its original rules.

## 20. Reranking
**Definition:** Reordering retrieved search results using an additional relevance model or scoring method to improve the quality of information provided to an LLM.

**Example:** A RAG system retrieves 20 documents and reranks them to select the five most relevant passages.

## Reflection

The most important concepts for me are RAG, grounding, hallucination, and evaluation because they directly influence the reliability of GenAI applications. Generating fluent text is relatively easy for modern LLMs, but ensuring factual correctness, traceability, and usefulness requires additional system components and careful validation.

I also consider embeddings, semantic search, and vector databases important because they connect generative models with external information. Understanding these concepts will help me design GenAI applications that solve real problems rather than simply demonstrate model capabilities.

## Related Work

See [Generative AI Applications: Research Report](research.md) for the use cases in which these concepts are applied.
