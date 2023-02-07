# Neural-Machine-Translation

Temporal Logic is a type of formal logic used in software engineering and formal methods to check properties of a system's behavior over time, with the goal of ensuring its reliability and correctness. Despite the advantages of using a precise syntax, the advanced expertise required to use temporal logic and the risk of errors in the expressed properties have led many companies to avoid using formal logics and instead rely on natural language requirements.

In the literature, there have been attempts to make the construction of formal properties from natural language easier, but most focus on restricted use cases to simplify the problem. However, the ability to translate unrestricted natural language requirements into temporal logic formulas could extend its use to various domains.

In this paper, we make a distinction between restricted (here called restricted) and unrestricted natural language requirements and how they can be translated into Temporal Logic formulas, specifically Linear Temporal Logic (LTL) formulas.
We present a new approach for synthesizing English-to-LTL pairs and we use pre-trained language models to perform the translation, reaching high performance on out-of-vocabulary test datasets.
We also propose an ensemble solution to address the difficulties of fine-tuning a single model to translate both forms of requirements
