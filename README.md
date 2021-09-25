# dependabot-cli
It is a command line tool to help you generate Github's dependabot.yml based on your project.

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
