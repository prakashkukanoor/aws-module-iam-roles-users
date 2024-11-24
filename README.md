# aws-module-iam
Module to create IAM user, IAM role, user & user group

- Define iam role in json.tpl file
- json.tpl file should be in the format of 
```
[
    {
        "name": "networking-admins",
        "path": "/terraform/networking/admins/users/",
        "policy_statement": {}
    }
]
```





