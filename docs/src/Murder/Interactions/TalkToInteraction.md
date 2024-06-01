# TalkToInteraction

**Namespace:** Murder.Interactions \
**Assembly:** Murder.dll

```csharp
public sealed struct TalkToInteraction : IInteraction
```

**Implements:** _[IInteraction](../../Bang/Interactions/IInteraction.html)_

### ⭐ Constructors
```csharp
public TalkToInteraction()
```

### ⭐ Properties
#### DIALOGUE_CHILD
```csharp
public readonly static string DIALOGUE_CHILD;
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
### ⭐ Methods
#### CreateDialogueChild(World, Entity)
```csharp
public Entity CreateDialogueChild(World world, Entity interacted)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`interacted` [Entity](../../Bang/Entities/Entity.html) \

**Returns** \
[Entity](../../Bang/Entities/Entity.html) \

#### Interact(World, Entity, Entity)
```csharp
public virtual void Interact(World world, Entity interactor, Entity interacted)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`interactor` [Entity](../../Bang/Entities/Entity.html) \
`interacted` [Entity](../../Bang/Entities/Entity.html) \



⚡