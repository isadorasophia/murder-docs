# TetherPoint

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct TetherPoint
```

Represents a single tether point for an entity.

### ⭐ Constructors
```csharp
public TetherPoint(int target, float distance, float maxAngleDeviation, float snapDistance)
```

**Parameters** \
`target` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`distance` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`maxAngleDeviation` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`snapDistance` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

### ⭐ Properties
#### Length
```csharp
public readonly float Length;
```

The desired distance from the tether target.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### MaxAngleDeviation
```csharp
public readonly float MaxAngleDeviation;
```

The maximum allowable angle deviation from the target's facing direction.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### SnapDistance
```csharp
public readonly float SnapDistance;
```

The distance at which the entity snaps to the tether target.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Target
```csharp
public readonly int Target;
```

The entity ID of the tether target.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \


⚡