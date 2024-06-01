# OnlyPersistThisComponentForEntityOnSaveAttribute

**Namespace:** Murder.Attributes \
**Assembly:** Murder.dll

```csharp
public class OnlyPersistThisComponentForEntityOnSaveAttribute : Attribute
```

This gets rather complicated, but this will persist only one component for the entity in the save.
            These are for cases that we want to persist an entity id for an entity with a specific property,
            e.g. the player.

**Implements:** _[Attribute](https://learn.microsoft.com/en-us/dotnet/api/System.Attribute?view=net-7.0)_

### ⭐ Constructors
```csharp
public OnlyPersistThisComponentForEntityOnSaveAttribute()
```

### ⭐ Properties
#### TypeId
```csharp
public virtual Object TypeId { get; }
```

**Returns** \
[Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \


⚡