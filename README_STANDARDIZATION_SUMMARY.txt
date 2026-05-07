Sigma Rules Standardization Summary

Source: SIGMA_RULES_DEDUPLICATED.zip
Reference style: sigma_rules_aws(3).zip
Converted rule files: 7713
Output structure: sigma_rules_deduplicated_standardized/<product_or_category>/<service_or_category>/<rule>.yml

What was standardized:
- Clean folder layout similar to the AWS reference zip
- Direct .yml files inside service folders, no duplicated rule.yml/rule.yml nesting
- Standard Sigma field order matching the AWS style
- logsource.definition added where missing
- missing references/tags/falsepositives filled with safe defaults
- AWS-style commented sections added to every rule: notes, api_parameters, cli_examples, siem_examples, remediation, security_notes
