German Passage Retrieval (MIRACL)
=====================================

German dev dataset from the [MIRACL challenge](https://project-miracl.github.io).

The dataset consists of 305 queries in the German language.

The `expected.tsv` file contains tab-separated identifiers of passages relevant to the queries (max 10 per query). The identifiers correspond to passages that are located in the German split of the dataset found [here](https://huggingface.co/datasets/miracl/miracl-corpus).

Directory structure
-------------------

* `README.md` — this file
* `config.txt` — configuration file
* `test-A` — directory with test data
* `test-A/in.tsv` — input data for the test set
* `test-A/expected.tsv` — expected output data for the test set