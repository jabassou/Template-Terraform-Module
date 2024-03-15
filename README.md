# Backstage Terraform Module

This repo provides a template for new Terraform modules via Backstage.

## Installation

Update your `app-config.yaml` file in the Backstage repo and add the following to your catalog locations:

```yaml
- type: url
  target: https://gitlab.prod.aws.wescale.fr/jamel.abassou/template-terraform-module
  rules:
    - allow: [Template]
```

- `type`: url: Indicates that the configuration item type is a URL.

- `target`: The target URL to which the rule will apply. In this case, it is the URL of a `template.yaml` file located in a GitLab repository.

- `rules`: Defines the rules that apply to the target URL.

- `allow`: [Template]: Specifies that only items of type `Template` are allowed to be used or referenced from this URL.

The template should then appear in your options for creating a new entity.
