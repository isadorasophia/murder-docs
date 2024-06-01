# SoundServices

**Namespace:** Murder.Services \
**Assembly:** Murder.dll

```csharp
public static class SoundServices
```

### ⭐ Methods
#### GetGlobalParameter(ParameterId)
```csharp
public float GetGlobalParameter(ParameterId id)
```

**Parameters** \
`id` [ParameterId](../../Murder/Core/Sounds/ParameterId.html) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### ReplaceIdentifiers(ImmutableDictionary<TKey, TValue>, Func<T, TResult>)
```csharp
public ImmutableDictionary<TKey, TValue> ReplaceIdentifiers(ImmutableDictionary<TKey, TValue> source, Func<T, TResult> converter)
```

**Parameters** \
`source` [ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \
`converter` [Func\<T, TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Func-2?view=net-7.0) \

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \

#### StopAll(bool, HashSet<T>)
```csharp
public SoundEventId[] StopAll(bool fadeOut, HashSet<T> exceptFor)
```

**Parameters** \
`fadeOut` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`exceptFor` [HashSet\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.HashSet-1?view=net-7.0) \

**Returns** \
[SoundEventId[]](../../Murder/Core/Sounds/SoundEventId.html) \

#### StopAll(bool)
```csharp
public SoundEventId[] StopAll(bool fadeOut)
```

Stop all the ongoing events.

**Parameters** \
`fadeOut` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

**Returns** \
[SoundEventId[]](../../Murder/Core/Sounds/SoundEventId.html) \
\

#### GetSpatialAttributes(Entity)
```csharp
public T? GetSpatialAttributes(Entity target)
```

Return the spatial attributes for playing a sound from <paramref name="target" />.

**Parameters** \
`target` [Entity](../../Bang/Entities/Entity.html) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

#### TryGetSoundForEvent(Entity, string)
```csharp
public T? TryGetSoundForEvent(Entity e, string animationEventId)
```

Try to get a sound id associated with an <paramref name="animationEventId" />
            on an entity with an [EventListenerComponent](../../Murder/Components/EventListenerComponent.html).

**Parameters** \
`e` [Entity](../../Bang/Entities/Entity.html) \
\
`animationEventId` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
\

#### Play(SoundEventId, Entity, SoundProperties)
```csharp
public ValueTask Play(SoundEventId id, Entity target, SoundProperties properties)
```

**Parameters** \
`id` [SoundEventId](../../Murder/Core/Sounds/SoundEventId.html) \
`target` [Entity](../../Bang/Entities/Entity.html) \
`properties` [SoundProperties](../../Murder/Core/Sounds/SoundProperties.html) \

**Returns** \
[ValueTask](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.ValueTask?view=net-7.0) \

#### Play(SoundEventId, SoundProperties, T?)
```csharp
public ValueTask Play(SoundEventId id, SoundProperties properties, T? attributes)
```

**Parameters** \
`id` [SoundEventId](../../Murder/Core/Sounds/SoundEventId.html) \
`properties` [SoundProperties](../../Murder/Core/Sounds/SoundProperties.html) \
`attributes` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

**Returns** \
[ValueTask](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.ValueTask?view=net-7.0) \

#### PlayMusic(SoundEventId)
```csharp
public ValueTask PlayMusic(SoundEventId id)
```

**Parameters** \
`id` [SoundEventId](../../Murder/Core/Sounds/SoundEventId.html) \

**Returns** \
[ValueTask](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.ValueTask?view=net-7.0) \

#### SetGlobalParameter(ParameterId, T)
```csharp
public void SetGlobalParameter(ParameterId id, T value)
```

**Parameters** \
`id` [ParameterId](../../Murder/Core/Sounds/ParameterId.html) \
`value` [T](../../) \

#### Stop(T?, bool)
```csharp
public void Stop(T? id, bool fadeOut)
```

**Parameters** \
`id` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
`fadeOut` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### TrackEventSourcePosition(SoundEventId, Entity)
```csharp
public void TrackEventSourcePosition(SoundEventId eventId, Entity e)
```

**Parameters** \
`eventId` [SoundEventId](../../Murder/Core/Sounds/SoundEventId.html) \
`e` [Entity](../../Bang/Entities/Entity.html) \



⚡