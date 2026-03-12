---
description: Review Terraform plans using internal conventions and risk checks
disable-model-invocation: false
---

Review the provided Terraform diff or plan output and return:

1. **Risk Summary** (Low/Medium/High)
2. **Breaking Change Checks**
3. **Security/Policy Notes**
4. **Cost/Scale Impact Notes**
5. **Recommended Next Command**

Use concise bullet points and clearly flag anything that should block merge.
