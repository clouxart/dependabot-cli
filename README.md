# dependabot-cli
It is a command line tool to help you generate Github's dependabot.yml based on your project.

![dependabot-config-generator demo gif](./media/dependabot-cli.gif)

## Getting started

### Install
```sh
npm install -g @clouxart/dependabot
# or
yarn global add @clouxart/dependabot
# or just run without installing it
npx @clouxart/dependabot
```

### Usage

```sh
dependabot
#or
dependabot ./my-projects-root-path
#or
dependabot --yes # it runs with default values
```

## TODOs
- ignore config per package manager. i.e:
```yaml
    ignore:
      # Starting with version 16.10.0, MSBuild requires .NET 5.0+
      - dependency-name: "Microsoft.Build"`;
```
- schedule config per package manager. i.e:
```yaml
    schedule:
      interval: "daily"
```
- registries config per package manager. i.e:
```yaml
    registries:
      - nuget-org
```
