## Prompt Engineering for Biometric Security Auditing

Few-shot prompting with role assignment, negative output constraints, and three edge-case examples achieves production-grade biometric sensor classification without fine-tuning. Tested Amazon Nova Lite and Claude 4.5 Opus via AWS Bedrock across low light, 2D spoof, and ambiguous glare scenarios -- both models returned 100% JSON-compliant structured decisions. Parameter configuration is the critical design variable: Temperature 0 with low Top-K (10--20) produces deterministic audit logs; Temperature 1 with the same Top-K constraint produces prioritized, user-facing remediation instructions from the same prompt template.

## Portfolio Page

The [portfolio page](https://kchoover14.github.io/xai-prompt-engineering-bedrock/) includes a full project narrative, prompt design, test case results, and parameter optimization findings.

## Tools & Technologies

**Languages:** None (no analysis script)

**Tools:** AWS Bedrock | Amazon Nova Lite | Claude 4.5 Opus

**Packages:** None

## Expertise

Systematic evaluation of LLM prompt design and parameter configuration for constrained classification tasks -- demonstrating how to match Temperature and Top-K settings to operational audience (audit logs vs. user-facing instructions) using a single prompt template.

## License

- Code and scripts are licensed under the [MIT License](LICENSE).
- Data, figures, and written content © Kara C. Hoover, licensed under [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/).
