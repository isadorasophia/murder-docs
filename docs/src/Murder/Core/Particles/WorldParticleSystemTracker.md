# WorldParticleSystemTracker

**Namespace:** Murder.Core.Particles \
**Assembly:** Murder.dll

```csharp
public class WorldParticleSystemTracker
```

### ⭐ Constructors
```csharp
public WorldParticleSystemTracker(int seed)
```

**Parameters** \
`seed` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

### ⭐ Methods
#### SetAlpha(int, float)
```csharp
public bool SetAlpha(int entityId, float alpha)
```

Set the alpha for a particle system itself according to the <paramref name="entityId" />.

**Parameters** \
`entityId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`alpha` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Synchronize(Entity)
```csharp
public bool Synchronize(Entity particleEntity)
```

**Parameters** \
`particleEntity` [Entity](../../../Bang/Entities/Entity.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Track(Entity)
```csharp
public bool Track(Entity particleEntity)
```

**Parameters** \
`particleEntity` [Entity](../../../Bang/Entities/Entity.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### FetchActiveParticleTrackers()
```csharp
public ReadOnlySpan<T> FetchActiveParticleTrackers()
```

Fetch all the active particle trackers.

**Returns** \
[ReadOnlySpan\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.ReadOnlySpan-1?view=net-7.0) \

#### Activate(int)
```csharp
public void Activate(int id)
```

**Parameters** \
`id` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### Deactivate(int)
```csharp
public void Deactivate(int id)
```

**Parameters** \
`id` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### Step(World)
```csharp
public void Step(World world)
```

**Parameters** \
`world` [World](../../../Bang/World.html) \

#### Untrack(Entity)
```csharp
public void Untrack(Entity particleEntity)
```

**Parameters** \
`particleEntity` [Entity](../../../Bang/Entities/Entity.html) \



⚡