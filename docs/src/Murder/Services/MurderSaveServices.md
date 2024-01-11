# MurderSaveServices

**Namespace:** Murder.Services \
**Assembly:** Murder.dll

```csharp
public static class MurderSaveServices
```

### ⭐ Methods
#### CreateOrGetSave()
```csharp
public SaveData CreateOrGetSave()
```

**Returns** \
[SaveData](../../Murder/Assets/SaveData.html) \

#### TryGetSave()
```csharp
public SaveData TryGetSave()
```

**Returns** \
[SaveData](../../Murder/Assets/SaveData.html) \

#### LoadSaveAndFetchTargetWorld(int)
```csharp
public T? LoadSaveAndFetchTargetWorld(int slot)
```

**Parameters** \
`slot` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

#### DoAction(BlackboardTracker, DialogAction)
```csharp
public void DoAction(BlackboardTracker tracker, DialogAction action)
```

**Parameters** \
`tracker` [BlackboardTracker](../../Murder/Save/BlackboardTracker.html) \
`action` [DialogAction](../../Murder/Core/Dialogs/DialogAction.html) \

#### RecordAndMaybeDestroy(Entity, World, bool)
```csharp
public void RecordAndMaybeDestroy(Entity entity, World world, bool destroy)
```

**Parameters** \
`entity` [Entity](../../Bang/Entities/Entity.html) \
`world` [World](../../Bang/World.html) \
`destroy` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \



⚡