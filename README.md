# Azure DevOps Starter Templates

## Using the Templates

These templates are designed to be imported into your Azure DevOps organization and referenced via `resources:` within your existing YAML pipelines.

After importing the templates, you can add a template reference to your pipelines like so:

```
 resources:
    repositories:
    - repository: 'your-templates-repo-name'
      name: 'Templates'
```

## Dependencies

Please install the following Azure DevOps extensions prior to using these templates:

- [Azure DevOps Extension - Replace Tokens](https://marketplace.visualstudio.com/items?itemName=qetza.replacetokens)

## Created By

[Morrow Solutions](https://morrowsolutions.dev)
