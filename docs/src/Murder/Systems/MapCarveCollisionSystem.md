# MapCarveCollisionSystem

**Namespace:** Murder.Systems \
**Assembly:** Murder.dll

```csharp
public class MapCarveCollisionSystem : IReactiveSystem, ISystem
```

**Implements:** _[IReactiveSystem](../../Bang/Systems/IReactiveSystem.html), [ISystem](../../Bang/Systems/ISystem.html)_

### ⭐ Constructors
```csharp
public MapCarveCollisionSystem()
```

### ⭐ Methods
#### IsValidCarve(Entity, ColliderComponent, CarveComponent)
```csharp
protected bool IsValidCarve(Entity e, ColliderComponent collider, CarveComponent carve)
```

**Parameters** \
`e` [Entity](../../Bang/Entities/Entity.html) \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`carve` [CarveComponent](../../Murder/Components/CarveComponent.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### TrackEntityOnGrid(Map, Entity, IntRectangle)
```csharp
protected void TrackEntityOnGrid(Map map, Entity e, IntRectangle rect)
```

**Parameters** \
`map` [Map](../../Murder/Core/Map.html) \
`e` [Entity](../../Bang/Entities/Entity.html) \
`rect` [IntRectangle](../../Murder/Core/Geometry/IntRectangle.html) \

#### UntrackEntityOnGrid(Map, Entity, IntRectangle, bool)
```csharp
protected void UntrackEntityOnGrid(Map map, Entity e, IntRectangle rect, bool force)
```

**Parameters** \
`map` [Map](../../Murder/Core/Map.html) \
`e` [Entity](../../Bang/Entities/Entity.html) \
`rect` [IntRectangle](../../Murder/Core/Geometry/IntRectangle.html) \
`force` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### OnAdded(World, ImmutableArray<T>)
```csharp
public virtual void OnAdded(World world, ImmutableArray<T> entities)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`entities` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### OnModified(World, ImmutableArray<T>)
```csharp
public virtual void OnModified(World world, ImmutableArray<T> entities)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`entities` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### OnRemoved(World, ImmutableArray<T>)
```csharp
public virtual void OnRemoved(World world, ImmutableArray<T> entities)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`entities` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \



⚡