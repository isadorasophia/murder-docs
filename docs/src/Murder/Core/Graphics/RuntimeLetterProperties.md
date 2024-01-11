# RuntimeLetterProperties

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public sealed struct RuntimeLetterProperties : IEquatable<T>
```

Properties of a letter when printing it.

**Implements:** _[IEquatable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=net-7.0)_

### ⭐ Properties
#### Color
```csharp
public T? Color { get; public set; }
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### Glitch
```csharp
public float Glitch { get; public set; }
```

Whether this will trigger a ~GLITCH~.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Pause
```csharp
public int Pause { get; public set; }
```

Amount of pause after this letter is printed.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Properties
```csharp
public RuntimeLetterPropertiesFlag Properties { get; public set; }
```

**Returns** \
[RuntimeLetterPropertiesFlag](../../../Murder/Core/Graphics/RuntimeLetterPropertiesFlag.html) \
#### Shake
```csharp
public float Shake { get; public set; }
```

Whether this will trigger a !SHAKE! (and intensity).

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Speed
```csharp
public float Speed { get; public set; }
```

Override the text speed from this letter on.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
### ⭐ Methods
#### CombineWith(RuntimeLetterProperties)
```csharp
public RuntimeLetterProperties CombineWith(RuntimeLetterProperties other)
```

**Parameters** \
`other` [RuntimeLetterProperties](../../../Murder/Core/Graphics/RuntimeLetterProperties.html) \

**Returns** \
[RuntimeLetterProperties](../../../Murder/Core/Graphics/RuntimeLetterProperties.html) \

#### Equals(RuntimeLetterProperties)
```csharp
public virtual bool Equals(RuntimeLetterProperties other)
```

**Parameters** \
`other` [RuntimeLetterProperties](../../../Murder/Core/Graphics/RuntimeLetterProperties.html) \

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



⚡