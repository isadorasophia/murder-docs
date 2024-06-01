# IntRange

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct IntRange
```

### ⭐ Constructors
```csharp
public IntRange(int single)
```

**Parameters** \
`single` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

```csharp
public IntRange(int start, int end)
```

**Parameters** \
`start` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`end` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

### ⭐ Properties
#### End
```csharp
public readonly int End;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Start
```csharp
public readonly int Start;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Zero
```csharp
public readonly static IntRange Zero;
```

**Returns** \
[IntRange](../../Murder/Components/IntRange.html) \
### ⭐ Methods
#### Contains(float)
```csharp
public bool Contains(float v)
```

**Parameters** \
`v` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Contains(int)
```csharp
public bool Contains(int v)
```

**Parameters** \
`v` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Get(float)
```csharp
public float Get(float progress)
```

**Parameters** \
`progress` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### GetRandom()
```csharp
public float GetRandom()
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### GetRandomFloat(Random)
```csharp
public float GetRandomFloat(Random random)
```

**Parameters** \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### GetRandom(Random)
```csharp
public int GetRandom(Random random)
```

**Parameters** \
`random` [Random](https://learn.microsoft.com/en-us/dotnet/api/System.Random?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \



⚡