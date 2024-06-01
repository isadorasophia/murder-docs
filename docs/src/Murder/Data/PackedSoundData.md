# PackedSoundData

**Namespace:** Murder.Data \
**Assembly:** Murder.dll

```csharp
public class PackedSoundData
```

This has the data regarding all the sounds that will be loaded in the game.

### ⭐ Constructors
```csharp
public PackedSoundData()
```

### ⭐ Properties
#### Banks
```csharp
public ImmutableDictionary<TKey, TValue> Banks { get; public set; }
```

This has all the banks used by the sound engine, sorted by the supported platform, e.g. "Desktop".

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \
#### Name
```csharp
public static const string Name;
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Plugins
```csharp
public ImmutableArray<T> Plugins { get; public set; }
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \


⚡