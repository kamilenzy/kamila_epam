# kamila_epam
# Generative AI Applications: Research Report

**Course:** EPAM Generative AI  
**Author:** Kamila Orynbekova  
**Date:** 05 November 2026

## 1. Introduction

Generative Artificial Intelligence (GenAI) refers to AI systems capable of producing new content, including text, code, images, audio, and video. Large Language Models (LLMs) have significantly expanded the possibilities of applying GenAI to business processes, education, software development, and professional services.

This report explores six practical GenAI use cases, focusing on their business value, technical challenges, limitations, and existing implementations. Particular attention is given to the difference between generating plausible content and producing reliable, verifiable results.

## 2. Use Case 1: AI-Assisted Software Development

**Business Value and Application**

Generative AI coding assistants help software engineers generate code, explain unfamiliar implementations, create unit tests, and identify potential defects. They can reduce time spent on repetitive programming tasks and support developers working with unfamiliar frameworks. In business environments, this can accelerate prototyping, improve developer productivity, and shorten development cycles. LLMs are especially useful for generating boilerplate code, documentation, and initial solutions that engineers subsequently review.

**Technical Challenges and Weak Points**

The main technical challenges include understanding project-specific context, integrating with repositories, managing context-window limitations, and ensuring that generated code follows security and quality requirements. AI-generated code may contain logical errors, security vulnerabilities, outdated dependencies, or hallucinated APIs. Another limitation is that plausible code is not necessarily correct or efficient. Human code review, automated testing, static analysis, and continuous integration remain essential.

**Existing Implementations**
- [GitHub Copilot](https://github.com/features/copilot) — An AI coding assistant that supports code suggestions, development assistance, and programming workflows.
- [Cursor](https://www.cursor.com/) — An AI-focused code editor that provides codebase-aware assistance and natural-language development features.

## 3. Use Case 2: Generative AI in Education

**Business Value and Application**

Generative AI can support personalized learning, automated assessment generation, tutoring, and educational content creation. For example, instructors can use LLMs to draft multiple-choice questions, explanations, programming exercises, and formative feedback. Students can receive adaptive explanations and practice materials based on their learning needs. Educational institutions may benefit from reduced preparation time, scalable student support, and more flexible learning experiences.

**Technical Challenges and Weak Points**

Educational GenAI systems must maintain factual correctness, align generated content with learning objectives, and provide appropriate difficulty levels. Evaluation is challenging because fluent explanations or grammatically correct questions may still be pedagogically weak. Other concerns include hallucinations, student privacy, academic integrity, language bias, and overreliance on generated answers. Human-in-the-loop validation is important, especially for high-stakes assessments. Effective systems should evaluate not only linguistic quality but also pedagogical relevance, fairness, and learning outcomes.

**Existing Implementations**
- [Khanmigo by Khan Academy](https://www.khanacademy.org/khan-labs) — An AI-powered educational assistant designed to support tutoring and teaching activities.
- [Duolingo](https://www.duolingo.com/) — A language-learning platform that incorporates AI-powered conversational and personalized learning experiences.

## 4. Use Case 3: Enterprise Knowledge Assistants Using RAG

**Business Value and Application**

Organizations accumulate large volumes of information in documents, internal websites, knowledge bases, and communication platforms. Generative AI assistants can help employees retrieve relevant information and receive natural-language answers instead of manually searching multiple systems. Retrieval-Augmented Generation (RAG) combines information retrieval with LLM-based answer generation. The business value includes faster information access, reduced repetitive questions, better knowledge sharing, and improved employee productivity.

**Technical Challenges and Weak Points**

Implementing RAG requires document ingestion, text chunking, embedding generation, indexing, semantic search, and retrieval quality evaluation. Vector databases can support similarity-based retrieval, while reranking techniques can improve the relevance of selected documents. Major challenges include outdated information, inconsistent documents, access-control enforcement, prompt injection, and inaccurate retrieval. A system may generate a convincing answer even when retrieved evidence is incomplete. Grounding responses in trusted sources, displaying citations, respecting document permissions, and measuring retrieval accuracy are essential.

**Existing Implementations**
- [Glean](https://www.glean.com/) — An enterprise AI platform for searching organizational information and generating answers grounded in connected workplace resources.
- [Microsoft 365 Copilot](https://www.microsoft.com/en-us/microsoft-365/copilot) — An AI assistant integrated with Microsoft productivity applications and organizational information.

## 5. Use Case 4: AI-Powered Legal Document Analysis

**Business Value and Application**

Legal professionals frequently work with extensive collections of contracts, case materials, regulations, and supporting documents. Generative AI can assist with document summarization, contract review, information extraction, legal research, and drafting. A particularly interesting application is identifying potential inconsistencies between statements or related documents. These systems can reduce the time required for initial document examination and help professionals focus on complex reasoning and decision-making.

**Technical Challenges and Weak Points**

Legal documents contain specialized terminology, references, exceptions, and context-dependent interpretations. A GenAI system must distinguish factual contradictions from differences in wording, missing information, or changes over time. Long-document processing, confidential information protection, traceability, and jurisdiction-specific requirements create additional challenges. Hallucinated legal references or unsupported conclusions can have serious consequences. Therefore, legal AI should provide evidence-based outputs, preserve source references, and support expert review rather than replace professional judgment.

**Existing Implementations**
- [Harvey](https://www.harvey.ai/) — A legal AI platform supporting professional legal research, document review, drafting, and related workflows.
- [ChatPDF](https://www.chatpdf.com/) — A conversational document-analysis tool that allows users to ask questions about uploaded PDF files.

## 6. Use Case 5: Generative AI for Customer Support

**Business Value and Application**

AI-powered customer support agents can answer frequently asked questions, explain products, summarize conversations, and assist customers through multiple communication channels. Compared with traditional rule-based chatbots, LLM-based systems can interpret a wider variety of natural-language requests. When integrated with company knowledge bases and business systems, they can provide context-aware responses and automate selected service workflows. Business benefits include faster response times, increased service availability, and reduced workload for human support teams.

**Technical Challenges and Weak Points**

A reliable customer-support assistant needs accurate knowledge retrieval, conversation-state management, integration with customer relationship management systems, and safe escalation to human operators. Technical challenges include multilingual interactions, ambiguous requests, changing policies, and protecting personal data. Weak points include incorrect advice, inappropriate automated actions, failure to recognize complex cases, and inconsistent responses. Guardrails, access controls, human handoff mechanisms, and continuous evaluation are necessary to maintain service quality.

**Existing Implementations**
- [Intercom Fin](https://www.intercom.com/fin) — An AI customer agent that uses support knowledge and connected systems to answer questions and handle customer-service workflows.
- [Zendesk AI](https://www.zendesk.com/ai/) — AI capabilities for customer-service automation, agent assistance, and support operations.

## 7. Use Case 6: Generative AI for Multimedia Content Creation

**Business Value and Application**

Generative AI enables businesses and individuals to create images, videos, advertising materials, and other digital content from natural-language prompts. Marketing teams can rapidly explore visual concepts, generate draft assets, and adapt materials for different audiences. This can reduce the cost of early-stage content production and accelerate creative experimentation. Text-to-image and text-to-video systems also create opportunities for education, product visualization, and digital storytelling.

**Technical Challenges and Weak Points**

Major challenges include maintaining visual consistency, accurately following prompts, controlling generated details, and producing high-quality outputs at reasonable computational cost. Generative models may produce unrealistic objects, inconsistent characters, visual artifacts, or misleading content. Copyright, consent, provenance, and bias are important concerns. Professional use often requires human editing, content moderation, and verification of usage rights. Generated media should not automatically be treated as authentic evidence of real-world events.

**Existing Implementations**
- [Adobe Firefly](https://www.adobe.com/products/firefly.html) — A family of generative AI tools for creating and editing visual content within creative workflows.
- [Sora by OpenAI](https://openai.com/index/sora/) — A generative video technology for producing video content from prompts and other supported inputs.

## 8. Cross-Cutting Technical Considerations

Across these use cases, several common concepts are important for designing reliable GenAI applications:

- **Prompt engineering:** Creating clear instructions and contextual inputs to guide model behavior.
- **Tokenization and context windows:** Understanding how input is represented and how much information a model can process.
- **Embeddings and semantic search:** Representing and retrieving information based on meaning rather than exact keyword matching.
- **RAG and grounding:** Connecting generated responses to relevant external knowledge and verifiable sources.
- **Fine-tuning:** Adapting a pretrained model to specific tasks or domains when appropriate.
- **Inference and latency:** Managing the computational cost and response time of model execution.
- **AI agents and tool use:** Allowing models to interact with external tools and execute controlled workflows.
- **Guardrails and evaluation:** Applying safety constraints and systematically measuring reliability, accuracy, and usefulness.

These components should be selected based on the actual business problem. More complex architectures do not automatically produce better results.

## 9. Conclusion

Generative AI has practical applications across software engineering, education, enterprise knowledge management, legal services, customer support, and creative industries. Its main business value comes from accelerating knowledge-intensive work, supporting decision-making, and improving access to information.

However, successful implementation requires more than integrating an LLM into an application. Reliable GenAI systems depend on data quality, appropriate architecture, security, evaluation, and human oversight. In my view, the most important distinction is between a system that produces convincing outputs and a system whose outputs can be trusted, verified, and used responsibly.

## 10. References

1. GitHub Copilot: https://github.com/features/copilot
2. Cursor: https://www.cursor.com/
3. Khan Academy Khanmigo: https://www.khanacademy.org/khan-labs
4. Duolingo: https://www.duolingo.com/
5. Glean: https://www.glean.com/
6. Microsoft 365 Copilot: https://www.microsoft.com/en-us/microsoft-365/copilot
7. Harvey: https://www.harvey.ai/
8. ChatPDF: https://www.chatpdf.com/
9. Intercom Fin: https://www.intercom.com/fin
10. Zendesk AI: https://www.zendesk.com/ai/
11. Adobe Firefly: https://www.adobe.com/products/firefly.html
12. OpenAI Sora: https://openai.com/index/sora/
