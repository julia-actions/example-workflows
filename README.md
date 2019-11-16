# Julia Example Workflows

A collection of example workflows for GitHub Actions that are used for Julia projects and packages.

| Name | Description | Workflow file |
| --- | --- | --- |
| Package CI | Run common package CI tasks, including tests and coverage reports | [ci.yml](https://github.com/invenia/PkgTemplates.jl/blob/master/test/fixtures/DocumenterGitHubActions/.github/workflows/ci.yml) |
| [Registry Automerge Bot](https://github.com/JuliaRegistries/RegistryCI.jl) | Provides continuous integration (CI) tools, including automated testing and automatic merging (automerge) of pull requests |  [automerge.yml](https://github.com/JuliaRegistries/General/blob/master/.github/workflows/automerge.yml)
| [CompatHelper Bot](https://github.com/bcbi/CompatHelper.jl) | Automatically update the [compat] entries for your Julia package's dependencies | [CompatHelper.yml](https://github.com/bcbi/CompatHelper.jl/blob/master/.github/workflows/CompatHelper.yml)
| Documenter deployment | Deploys docs built by Documenter.jl | [docs.yml](https://github.com/fredrikekre/Literate.jl/blob/master/.github/workflows/docs.yml)
| Update Manifest.toml | Run `Pkg.update` on `Manifest.toml` files checked in to the repository | [pkg-update.yml](https://github.com/tkf/Kaleido.jl/blob/master/.github/workflows/pkg-update.yml)

## Using a workflow

You can find general information about GitHub Actions and workflows in the [GitHub Docs](https://help.github.com/en/actions/automating-your-workflow-with-github-actions)

If you want to get started as quickly as possible, check out [CompatHelper.jl's README](https://github.com/bcbi/CompatHelper.jl#installation) which contains information on how to add workflows. It's applicable to other workflows as well, though some may require additional configuration.

## Contributing

If you have built an action or workflow to be used with Julia projects, please submit a PR and add your examples!
