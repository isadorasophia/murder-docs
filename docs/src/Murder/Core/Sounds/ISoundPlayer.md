# ISoundPlayer

**Namespace:** Murder.Core.Sounds \
**Assembly:** Murder.dll

```csharp
public abstract ISoundPlayer
```

### ⭐ Methods
#### Stop(bool, out SoundEventId[]&)
```csharp
public abstract bool Stop(bool fadeOut, SoundEventId[]& stoppedEvents)
```

**Parameters** \
`fadeOut` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`stoppedEvents` [SoundEventId[]&](../../../Murder/Core/Sounds/SoundEventId.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Stop(T?, bool)
```csharp
public abstract bool Stop(T? id, bool fadeOut)
```

Stop a specific sound event id.
            If <paramref name="fadeOut" /> is set, this will stop with a fadeout.

**Parameters** \
`id` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
\
`fadeOut` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### UpdateEvent(SoundEventId, SoundSpatialAttributes)
```csharp
public abstract bool UpdateEvent(SoundEventId id, SoundSpatialAttributes attributes)
```

Update spatial attributes for a specific event instance.

**Parameters** \
`id` [SoundEventId](../../../Murder/Core/Sounds/SoundEventId.html) \
\
`attributes` [SoundSpatialAttributes](../../../Murder/Core/Sounds/SoundSpatialAttributes.html) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

#### GetGlobalParameter(ParameterId)
```csharp
public abstract float GetGlobalParameter(ParameterId parameter)
```

**Parameters** \
`parameter` [ParameterId](../../../Murder/Core/Sounds/ParameterId.html) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### LoadContentAsync()
```csharp
public abstract Task LoadContentAsync()
```

This will load the actual bank content asynchonously.

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### ReloadAsync()
```csharp
public abstract Task ReloadAsync()
```

This will reload the content of all the fmod banks in the application.

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### PlayEvent(SoundEventId, SoundProperties, T?)
```csharp
public abstract ValueTask PlayEvent(SoundEventId id, SoundProperties properties, T? attributes)
```

**Parameters** \
`id` [SoundEventId](../../../Murder/Core/Sounds/SoundEventId.html) \
`properties` [SoundProperties](../../../Murder/Core/Sounds/SoundProperties.html) \
`attributes` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

**Returns** \
[ValueTask](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.ValueTask?view=net-7.0) \

#### Initialize(string)
```csharp
public abstract void Initialize(string resourcesPath)
```

This will initialize the fmod libraries, but not load any banks.

**Parameters** \
`resourcesPath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

#### SetGlobalParameter(ParameterId, float)
```csharp
public abstract void SetGlobalParameter(ParameterId parameter, float value)
```

**Parameters** \
`parameter` [ParameterId](../../../Murder/Core/Sounds/ParameterId.html) \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### SetParameter(SoundEventId, ParameterId, float)
```csharp
public abstract void SetParameter(SoundEventId instance, ParameterId parameter, float value)
```

**Parameters** \
`instance` [SoundEventId](../../../Murder/Core/Sounds/SoundEventId.html) \
`parameter` [ParameterId](../../../Murder/Core/Sounds/ParameterId.html) \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### SetVolume(T?, float)
```csharp
public abstract void SetVolume(T? id, float volume)
```

Change volume.

**Parameters** \
`id` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
`volume` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### Update()
```csharp
public abstract void Update()
```

#### UpdateListener(SoundSpatialAttributes)
```csharp
public abstract void UpdateListener(SoundSpatialAttributes attributes)
```

Update listener information (e.g. position and facing).

**Parameters** \
`attributes` [SoundSpatialAttributes](../../../Murder/Core/Sounds/SoundSpatialAttributes.html) \
\

#### Stop(bool, HashSet<T>, out SoundEventId[]&)
```csharp
public virtual bool Stop(bool fadeOut, HashSet<T> exceptForSoundsList, SoundEventId[]& stoppedEvents)
```

**Parameters** \
`fadeOut` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`exceptForSoundsList` [HashSet\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.HashSet-1?view=net-7.0) \
`stoppedEvents` [SoundEventId[]&](../../../Murder/Core/Sounds/SoundEventId.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \



⚡