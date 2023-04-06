<div align="center">

# Routine-Express

[![Unity 2020.3](https://img.shields.io/badge/unity-2020.3%2B-blue.svg)](https://unity3d.com/get-unity/download)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://github.com/sgaumin/RoutineExpress/blob/main/LICENSE.md)
[![Twitter URL](https://img.shields.io/twitter/url/https/twitter.com/Seb_gamedev.svg?style=social&label=Follow%20%40Seb_gamedev)](https://twitter.com/Seb_gamedev)

**Lightweight Unity Utility to setup Routine on external MonoBehavior**
</div>

## Installation
You can install this library by the steps below.

1. Select **Window > Package Manager** from the menu bar.
2. Click the **+** button in the upper left corner of the window and select **Add package from git URL...**.
3. Enter the following URL in the input field and click **Add**.

```
https://github.com/sgaumin/RoutineExpress.git
```

## Demo
```csharp
using RoutineExpress;

public class RoutineExpressTester 
{
    private void Start()
    {
        RoutinePool.Run(MyIEnumeratorMethod);
    }
}
```

## Support

If you ever come across any issues please feel free to report to the [Issues](https://github.com/sgaumin/RoutineExpress/issues) page on this repository. All feedback is appreciated, and will be
taken on board for any future updates. 

## License

[MIT License](https://github.com/sgaumin/RoutineExpress/blob/main/LICENSE.md)
