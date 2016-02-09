# .NET Core Targets for Windows Runtime

Creating a .NET Core library? Want to use native Windows Runtime APIs? You've come to the right place.

## Getting Started

Just add this to your `project.json` file:

```json
"frameworks": {
    "netcore451": {
        "Target.WindowsRuntime": "8.1.0"
    }
}
```

## License

[MIT](LICENSE)
