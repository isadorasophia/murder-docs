# FileHelper

**Namespace:** Murder.Serialization \
**Assembly:** Murder.dll

```csharp
public static class FileHelper
```

### ⭐ Methods
#### Clean(string)
```csharp
public ReadOnlySpan<T> Clean(string str)
```

**Parameters** \
`str` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[ReadOnlySpan\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1?view=net-7.0) \

#### EscapePath(string)
```csharp
public string EscapePath(string path)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### ExtensionForOperatingSystem()
```csharp
public string ExtensionForOperatingSystem()
```

Returns the assembly extension for the target operating system.
            For example, if targeting Windows, this returns ".dll".

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Exceptions** \
[PlatformNotSupportedException](https://learn.microsoft.com/en-us/dotnet/api/System.PlatformNotSupportedException?view=net-7.0) \
\
#### GetPath(String[])
```csharp
public string GetPath(String[] paths)
```

Gets the rooted path from a relative one

**Parameters** \
`paths` [string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

#### GetPathWithoutExtension(string)
```csharp
public string GetPathWithoutExtension(string path)
```

**Parameters** \
`path` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### GetSaveBasePath(string)
```csharp
public string GetSaveBasePath(string gameName)
```

Gets the base path for save files.

**Parameters** \
`gameName` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \



⚡