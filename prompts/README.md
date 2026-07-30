# Prompt Entry Schema

Store each reviewed entry as Markdown with matching YAML front matter:

```yaml
title: ""
slug: ""
use_case: ""
ltx_version: ""
pipeline: ""
prompt: ""
negative_prompt: ""
seed: 0
settings: {}
expected_behavior: ""
tested_hardware: ""
last_tested: "YYYY-MM-DD"
input_rights: ""
output_rights: ""
```

The body should explain why the prompt is structured this way, what each
setting controls, known limitations, and links to canonical upstream guidance.
Do not publish placeholder values as tested data.
