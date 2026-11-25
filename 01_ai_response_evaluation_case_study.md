# Case Study 1: Side-by-Side AI Response Evaluation (Rubric Audit)

## User Prompt
> "Explain the difference between a list and a tuple in Python for a beginner in under 60 words. Use bullet points and do not include code examples."

## Model Outputs

### Model A Response
"In Python, lists and tuples both store multiple items, but they have key differences:
- **Mutability:** Lists can be changed after creation, while tuples cannot be modified.
- **Syntax:** Lists use square brackets, whereas tuples use parentheses.
- **Performance:** Tuples are slightly faster and use less memory than lists."

### Model B Response
"Lists and tuples are data structures in Python. For example, `my_list =` is mutable, meaning you can add or remove items anytime. On the other hand, `my_tuple = (1, 2, 3)` is immutable and fixed. Lists are great when your data changes frequently, while tuples protect constant data."

## Quality Evaluation & Justification

| Evaluation Metric | Model A | Model B |
| :--- | :--- | :--- |
| **Instruction Following** | **Pass** (49 words, bullets used, no code) | **Fail** (Included code examples and ignored bullet format) |
| **Factual Accuracy** | **Pass** (All technical claims accurate) | **Pass** (Definitions and syntax accurate) |
| **Clarity & Tone** | **Pass** (Beginner-friendly and concise) | **Partial** (Clear, but written as a dense paragraph) |

### Final Verdict
**Model A is significantly better.** Model B failed two explicit constraints by writing a paragraph instead of bullet points and adding inline code despite the negative constraint.
