# Random Color in C#
The C# Class for avable them in windows forms application

## How to use ?
Add the [ThemeColor.cs](https://github.com/AmirMahdyJebreily/ThemeColor/blob/main/ThemeColor.cs) file to your project and using its namespace:
```csharp
using AmirJCS;
```
now just call `SelectThemeColor()` method like follow : 
```csharp
// Console applications : 
Console.ForegroundColor = SelectThemeColor();

// Windows forms applications : 
lblUsername.ForegroundColor = SelectThemeColor();

// and outher places
```
