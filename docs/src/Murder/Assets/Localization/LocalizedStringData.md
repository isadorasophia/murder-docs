# LocalizedStringData

**Namespace:** Murder.Assets.Localization \
**Assembly:** Murder.dll

```csharp
public sealed struct LocalizedStringData
```

### ⭐ Constructors
```csharp
public LocalizedStringData()
```

```csharp
public LocalizedStringData(Guid guid)
```

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

### ⭐ Properties
#### Counter
```csharp
public T? Counter { get; public set; }
```

Total of references to this string data.

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### Guid
```csharp
public readonly Guid Guid;
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### IsGenerated
```csharp
public bool IsGenerated { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Notes
```csharp
public string Notes { get; public set; }
```

Any notes relevant to this string.

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### String
```csharp
public string String { get; public set; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \


⚡