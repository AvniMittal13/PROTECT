# PROTECT: Policy-Driven Organizational Taxonomy for Ethical Compliance and Trust

**PROTECT** is a value-driven taxonomy designed to model organizational compliance through the lens of ethical and policy-aligned decision-making. It defines a structured set of organizational values and enables the creation of scenario-based datasets for evaluating large language models on compliance tasks.

## Dataset

The dataset is included in the repository under the `data/` folder and is organized as follows:

* `data/train/` – Training set with multiple compliance scenarios.
* `data/test/` – Test set for evaluation.

Each entry in the dataset contains:

* `scenario`: A realistic organizational decision-making context.
* `compliance_status`: Indicates whether the response adheres to compliance expectations.
* `values`: A list of organizational values emphasized in the scenario.
* `response`: A generated response representing compliant or non-compliant behavior.

This dataset can be used for tasks such as value prediction, compliance classification, and instruction evaluation for LLMs.