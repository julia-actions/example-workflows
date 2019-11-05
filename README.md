# Julia Workflow Examples

A collection of example workflows for GitHub Actions that are used for Julia projects and packages.

| Name | Description | Workflow file |
| --- | --- | --- |
| Package CI | Run common package CI tasks, including tests and coverage reports | [ci-workflow.yml](https://github.com/davidanthoff/StringBuilders.jl/blob/master/.github/workflows/ci-workflow.yml) |
| [Registry Automerge Bot](https://github.com/JuliaRegistries/RegistryCI.jl) | Provides continuous integration (CI) tools, including automated testing and automatic merging (automerge) of pull requests |  [automerge.yml](https://github.com/JuliaRegistries/General/blob/master/.github/workflows/automerge.yml)
| [CompatHelper Bot](https://github.com/bcbi/CompatHelper.jl) | Automatically update the [compat] entries for your Julia package's dependencies | [CompatHelper.yml](https://github.com/bcbi/CompatHelper.jl/blob/master/.github/workflows/CompatHelper.yml)
| Documenter deployment | Deploys docs built by Documenter.jl | [docs.yml](https://github.com/fredrikekre/Literate.jl/blob/master/.github/workflows/docs.yml)

## Contributing

If you have built an action or workflow to be used with Julia projects, please submit a PR and add your examples!
