# {{cookiecutter.app_name}}
{{cookiecutter.project_short_description}}

- Created with .NET Core 5.
- Runs on Windows, macOS, and Linux.
- To parse the options https://github.com/commandlineparser/commandline for parsing options.


## Build & Publish

### Build : 

```shell
cd {{cookiecutter.project_slug}}
dotnet restore
dotnet build
```

### Publish :

#### Windows

```shell
dotnet publish -r win-x64
```

#### macOS

```shell
dotnet publish -r osx-x64
```

#### Linux

```shell
dotnet publish -r linux-x64
```

## Usage

### Options

### Examples


