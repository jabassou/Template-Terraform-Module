# ${{ values.name }}

${{ values.description }}

## Documentation

Documentation for this module is managed via [mkdocs](https://www.mkdocs.org) so it can be read by Backstage.

If you wish to incorporate new documentation, all you need to do is update the files in the `docs/docs/` folder and submit your changes. Backstage will take care of compiling them automatically.

## CI/CD

The GitLab CI is set up to perform a series of checks on your code using the specified tools (Terraform, TFLint, Checkov) with the specified Docker image versions.