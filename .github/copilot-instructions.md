PULL REQUEST REVIEW RULES (MANDATORY)

C++ RULE:
- Variable declarations in .cpp files MUST use explicit types.
- Usage of `auto` in .cpp files is NOT allowed.

WHEN REVIEWING PRS:
- Detect any use of `auto` in .cpp files.
- Explain why it violates the rule.
- Suggest a corrected version using an explicit type (e.g. int).
- Ignore formatting or unrelated issues.
