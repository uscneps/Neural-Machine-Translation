# Neural-Machine-Translation

Temporal Logic are mainly used in Formal Methods and Software Engineering to check properties in terms of time on the system's behaviour, in order to ensure its correctness and reliability.

These formal logics provide a more precise and strict syntax that requires an advanced expertise to comply with it, which is still not enough to ensure the absence of errors in the expressed properties.
For this reason, despite losing the benefits of the formal approaches, many companies avoid using them and resort instead to requirements written in natural language, specifically English.

In the literature several approaches try to ease the construction of formal properties starting from natural language.
However, most attempts focus on domain-specific use cases, so to reduce the generality of natural language and make the problem easier to face.
On the other hand, the possibility to translate unrestricted natural language requirements to temporal logic formulas would make it extensible to several domains with little to no effort.

In this Thesis we make a clear distinction between domain-specific and unbounded natural language requirements and how they could be translated into Temporal Logic formulas, specifically Linear Temporal Logic (LTL) ones.
We attempt to fill the lack of datasets containing English-to-LTL pairs by presenting a new approach for synthesizing pairs in both the unbounded and domain-specific forms.
Finally, we present an approach that makes use of pre-trained Language Models to perform the translation of English requirements to LTL formulas.
We also assess the difficulties of fine-tuning a single model to perform the translation of both forms, then we propose a first ensemble solution to solve the problem.

All the models reach high results on the out-of-vocabulary evaluation test sets, setting a good starting point for improvements in this direction.
