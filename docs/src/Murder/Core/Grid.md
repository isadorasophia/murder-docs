# Grid

**Namespace:** Murder.Core \
**Assembly:** Murder.dll

```csharp
public static class Grid
```

Helper static class that forwards the values of the default [Game.Grid](../../Murder/Game.html#grid) for easier access.

### ⭐ Properties
#### CellDimensions
```csharp
public static Point CellDimensions { get; }
```

**Returns** \
[Point](../../Murder/Core/Geometry/Point.html) \
#### CellSize
```csharp
public static int CellSize { get; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### HalfCellDimensions
```csharp
public static Point HalfCellDimensions { get; }
```

**Returns** \
[Point](../../Murder/Core/Geometry/Point.html) \
#### HalfCellSize
```csharp
public static int HalfCellSize { get; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
### ⭐ Methods
#### CeilToGrid(float)
```csharp
public int CeilToGrid(float value)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### FloorToGrid(float)
```csharp
public int FloorToGrid(float value)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### RoundToGrid(float)
```csharp
public int RoundToGrid(float value)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \



⚡