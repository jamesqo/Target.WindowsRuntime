# WinRT Targets for .NET Core

Creating a .NET Core library? Want to use native Windows Runtime APIs? You've come to the right place.

## Getting Started

Just add this to your `project.json` file:

```json
"frameworks": {
    "netcore45": {
        "Target.WindowsRuntime": "8.0.0"
    }
}
```

Want to target Windows 8.1? Bump the version:

```json
"netcore451": {
    "Target.WindowsRuntime": "8.1.0"
}
```

## License

[MIT](LICENSE)
