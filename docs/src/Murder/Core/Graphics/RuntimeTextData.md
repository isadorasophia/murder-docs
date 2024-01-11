# RuntimeTextData

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public sealed struct RuntimeTextData
```

This has runtime information about a text which is displayed in screen.

### ⭐ Constructors
```csharp
public RuntimeTextData()
```

```csharp
public RuntimeTextData(string text, ImmutableDictionary<TKey, TValue> letters)
```

**Parameters** \
`text` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`letters` [ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \

```csharp
public RuntimeTextData(string text)
```

**Parameters** \
`text` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

### ⭐ Properties
#### Empty
```csharp
public bool Empty { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Font
```csharp
public int Font { get; public set; }
```

Index of the font used to calculate the runtime text data.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### HiRes
```csharp
public bool HiRes { get; public set; }
```

Whether this is high resolution.

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Length
```csharp
public int Length { get; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Text
```csharp
public readonly string Text;
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
### ⭐ Methods
#### TryGetLetterProperty(int)
```csharp
public T? TryGetLetterProperty(int index)
```

**Parameters** \
`index` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \



⚡