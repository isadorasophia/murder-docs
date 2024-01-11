# SoundSpatialAttributes

**Namespace:** Murder.Core.Sounds \
**Assembly:** Murder.dll

```csharp
public sealed struct SoundSpatialAttributes
```

Properties

### ⭐ Properties
#### Direction
```csharp
public Direction Direction;
```

Forwards orientation, must be of unit length (1.0) and perpendicular to up.

**Returns** \
[Direction](../../../Murder/Helpers/Direction.html) \
#### Position
```csharp
public Vector2 Position;
```

Position in 2D space. Used for panning and attenuation.

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### Velocity
```csharp
public Vector2 Velocity;
```

Velocity in 2D space. Used for doppler effect.

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \


⚡