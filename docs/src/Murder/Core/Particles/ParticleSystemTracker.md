# ParticleSystemTracker

**Namespace:** Murder.Core.Particles \
**Assembly:** Murder.dll

```csharp
public sealed struct ParticleSystemTracker
```

### ⭐ Constructors
```csharp
public ParticleSystemTracker(Emitter emitter, Particle particle, int seed)
```

**Parameters** \
`emitter` [Emitter](../../../Murder/Core/Particles/Emitter.html) \
`particle` [Particle](../../../Murder/Core/Particles/Particle.html) \
`seed` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

### ⭐ Properties
#### CurrentTime
```csharp
public float CurrentTime { get; }
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Emitter
```csharp
public readonly Emitter Emitter;
```

**Returns** \
[Emitter](../../../Murder/Core/Particles/Emitter.html) \
#### LastEmitterPosition
```csharp
public Vector2 LastEmitterPosition { get; }
```

The last position of the emitter.

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### Particle
```csharp
public readonly Particle Particle;
```

**Returns** \
[Particle](../../../Murder/Core/Particles/Particle.html) \
#### Particles
```csharp
public ReadOnlySpan<T> Particles { get; }
```

**Returns** \
[ReadOnlySpan\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1?view=net-7.0) \
### ⭐ Methods
#### Step(bool, Vector2, int)
```csharp
public bool Step(bool allowSpawn, Vector2 emitterPosition, int id)
```

Makes a "step" throughout the particle system.

**Parameters** \
`allowSpawn` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\
`emitterPosition` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
\
`id` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

#### Start(Vector2, int)
```csharp
public void Start(Vector2 emitterPosition, int id)
```

**Parameters** \
`emitterPosition` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`id` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \



⚡