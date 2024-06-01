# InteractOnCollisionSystem

**Namespace:** Murder.Systems \
**Assembly:** Murder.dll

```csharp
public class InteractOnCollisionSystem : IMessagerSystem, ISystem
```

Interactors tag hightlights and interacts with InteractorComponents

**Implements:** _[IMessagerSystem](../../Bang/Systems/IMessagerSystem.html), [ISystem](../../Bang/Systems/ISystem.html)_

### ⭐ Constructors
```csharp
public InteractOnCollisionSystem()
```

### ⭐ Methods
#### IsInteractAllowed(Entity, InteractOnCollisionComponent)
```csharp
protected virtual bool IsInteractAllowed(Entity interactor, InteractOnCollisionComponent component)
```

**Parameters** \
`interactor` [Entity](../../Bang/Entities/Entity.html) \
`component` [InteractOnCollisionComponent](../../Murder/Components/InteractOnCollisionComponent.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### OnMessage(World, Entity, IMessage)
```csharp
public virtual void OnMessage(World world, Entity entity, IMessage message)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`entity` [Entity](../../Bang/Entities/Entity.html) \
`message` [IMessage](../../Bang/Components/IMessage.html) \



⚡