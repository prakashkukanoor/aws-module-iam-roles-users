# aws-module-iam
Module to create IAM user, IAM role, user & user group

- Define iam role in json.tpl file
- json.tpl file should be in below
```
[
    {
        "name": "<policy-name>",
        "path": "/<<policy-path>/",
        "policy_statement": {}
    }
]
```





