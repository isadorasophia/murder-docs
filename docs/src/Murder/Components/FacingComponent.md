# FacingComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct FacingComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public FacingComponent(Direction direction)
```

Creates a FacingComponent using a Direction as a base.

**Parameters** \
`direction` [Direction](../../Murder/Helpers/Direction.html) \
\

```csharp
public FacingComponent(float angle)
```

**Parameters** \
`angle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

### ⭐ Properties
#### Angle
```csharp
public readonly float Angle;
```

The angle the agent is facing, in radians

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Direction
```csharp
public Direction Direction { get; }
```

The [FacingComponent.Direction](../../Murder/Components/FacingComponent.html#direction) that this entity is facing

**Returns** \
[Direction](../../Murder/Helpers/Direction.html) \


⚡