# MoveToTargetComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct MoveToTargetComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public MoveToTargetComponent(int target, float minDistance, float slowDownDistance, Vector2 offset)
```

**Parameters** \
`target` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`minDistance` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`slowDownDistance` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`offset` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

```csharp
public MoveToTargetComponent(int target, float minDistance, float slowDownDistance)
```

**Parameters** \
`target` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`minDistance` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`slowDownDistance` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

### ⭐ Properties
#### MinDistance
```csharp
public readonly float MinDistance;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Offset
```csharp
public readonly Vector2 Offset;
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### SlowDownDistance
```csharp
public readonly float SlowDownDistance;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Target
```csharp
public readonly int Target;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \


⚡