# net-core-healthcheck-example

Example healthchecks for an API in .NET Core.

Exposes two healthcheck endpoints:

`/health` - text response

`/healthz` - JSON response

## Build

```
msbuild MockAPI.sln /p:DeployOnBuild=true /p:PublishProfile=Properties\PublishProfiles\FolderProfile.pubxml
```

## Authors

**Andre Silva** - [@andreswebs](https://github.com/andreswebs)

## License

This project is licensed under the [Unlicense](UNLICENSE.md).
