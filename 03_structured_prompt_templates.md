# Case Study 3: Structured Prompt Engineering Templates

## 1. Hallucination-Free Fact Verification Prompt
```text
Role: You are an objective fact-checking assistant.
Task: Verify whether the statement below is supported by the provided reference text.
Constraints:
- Rely ONLY on the provided reference text. Do not use outside knowledge.
- If the reference text lacks enough information, respond strictly with: "Insufficient information in source."
- Keep your explanation under 3 sentences.

Reference Text: [Insert source text]
Claim to Verify: [Insert claim]
```

## 2. Python Code Debugging & Explanation Prompt
```text
Role: Senior Python Mentor for students.
Task: Identify the syntax or runtime bug in the Python snippet below and provide the corrected code.
Output Format:
1. **Bug Identified:** One-sentence explanation of why the error occurs.
2. **Fixed Code:** Clean, commented Python 3 code block.
3. **Key Takeaway:** One practical tip to prevent this bug in the future.

Code Snippet: [Paste Python code]
```
