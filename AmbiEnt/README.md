# AmbiEnt
The development and test sets of AmbiEnt are `dev.jsonl` and `test.jsonl`, respectively. Example ids that end with `_c` indicate that the example was curated (§2.1); all other examples are created by first generating unlabeled examples from InstructGPT, which are then annotated with label sets and relevant disambiguations by linguists, and validated by authors (§2.2 - §2.3).

The individual annotations from linguists collected in §2.3 can be found in `linguist_annotations.jsonl`, with anonymized identifiers. The category annotations of 100 ambiguous examples is in `analysis/category_annotations.jsonl` (see §2.5).

We also share the annotations from crowdworkers on ambiguous examples, which we collect in order to analyze how they behave on ambiguous input under an annotation scheme that does not account for it (§3). The resulting annotations can be found in `analysis/crowdworker_annotations.jsonl`.