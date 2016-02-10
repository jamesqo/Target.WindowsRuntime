# Windows Runtime APIs for .NET Core

<img src="http://i.imgur.com/5dzr6Wi.png" width="30%"/>

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

## Related Projects

- [Target.Windows](http://github.com/jamesqo/Target.Windows) - use Windows 8 APIs from .NET Core
- [Target.WindowsPhone](http://github.com/jamesqo/Target.WindowsPhone) - use Windows Phone APIs from .NET Core

## License

[MIT](LICENSE)
