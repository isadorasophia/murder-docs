# RuntimeTextDataKey

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public sealed struct RuntimeTextDataKey : IEquatable<T>
```

**Implements:** _[IEquatable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=net-7.0)_

### ⭐ Constructors
```csharp
public RuntimeTextDataKey(string Text, int Font, int Width)
```

**Parameters** \
`Text` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`Font` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`Width` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

### ⭐ Properties
#### Font
```csharp
public int Font { get; public set; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Text
```csharp
public string Text { get; public set; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Width
```csharp
public int Width { get; public set; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
### ⭐ Methods
#### Equals(RuntimeTextDataKey)
```csharp
public virtual bool Equals(RuntimeTextDataKey other)
```

**Parameters** \
`other` [RuntimeTextDataKey](../../../Murder/Core/Graphics/RuntimeTextDataKey.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Equals(Object)
```csharp
public virtual bool Equals(Object obj)
```

**Parameters** \
`obj` [Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### GetHashCode()
```csharp
public virtual int GetHashCode()
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### ToString()
```csharp
public virtual string ToString()
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### Deconstruct(out String&, out Int32&, out Int32&)
```csharp
public void Deconstruct(String& Text, Int32& Font, Int32& Width)
```

**Parameters** \
`Text` [string&](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`Font` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`Width` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \



⚡