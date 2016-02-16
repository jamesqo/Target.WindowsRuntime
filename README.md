# Windows Runtime APIs for .NET Core

<img src="http://i.imgur.com/5dzr6Wi.png" width="30%"/>

Creating a .NET Core library? Want to use native Windows Runtime APIs? You've come to the right place.

## Getting Started

Just add this to your `project.json` file:

```json
"dependencies": {
    "Target.WindowsRuntime": "8.1.1"
},

"frameworks": {
    "netcore451": { },
    "wpa81": { }
}
```

That's it! Then, you can write something like:

```csharp
using System;
using System.Collections.Generic;
using Windows.UI.Xaml;

public class MyApp : Application
{
    public MyApp()
    {
        Console.WriteLine("Hello, world!");
    }
}
```

and have it compile.

## Related Projects

- [Target.Windows](http://github.com/jamesqo/Target.Windows) - use Windows 8 APIs from .NET Core
- [Target.WindowsPhone](http://github.com/jamesqo/Target.WindowsPhone) - use Windows Phone APIs from .NET Core

## License

[MIT](LICENSE)
