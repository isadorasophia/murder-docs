# Character

**Namespace:** Murder.Core.Dialogs \
**Assembly:** Murder.dll

```csharp
public sealed struct Character
```

### ⭐ Constructors
```csharp
public Character(Guid guid, Guid speaker, string portrait, ImmutableArray<T> situations)
```

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`speaker` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`portrait` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`situations` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

### ⭐ Properties
#### Guid
```csharp
public readonly Guid Guid;
```

The guid of the character asset being tracked by this.

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### Portrait
```csharp
public readonly string Portrait;
```

The default portrait for [Character.Speaker](../../../Murder/Core/Dialogs/Character.html#speaker). If null, use the speaker
            default portrait.

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Situations
```csharp
public readonly ImmutableDictionary<TKey, TValue> Situations;
```

All situations for the character.

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \
#### Speaker
```csharp
public readonly Guid Speaker;
```

The speaker is the owner of this dialog. Used when a null
            speaker is found.

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \


⚡