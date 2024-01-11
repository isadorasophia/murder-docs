# PhysicsServices

**Namespace:** Murder.Services \
**Assembly:** Murder.dll

```csharp
public static class PhysicsServices
```

### ⭐ Methods
#### CollidesAt(Map&, int, ColliderComponent, Vector2, IEnumerable<T>, int, out Int32&)
```csharp
public bool CollidesAt(Map& map, int ignoreId, ColliderComponent collider, Vector2 position, IEnumerable<T> others, int mask, Int32& hitId)
```

**Parameters** \
`map` [Map&](../../Murder/Core/Map.html) \
`ignoreId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`others` [IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \
`mask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`hitId` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### CollidesAt(Map&, int, ColliderComponent, Vector2, IEnumerable<T>, int)
```csharp
public bool CollidesAt(Map& map, int ignoreId, ColliderComponent collider, Vector2 position, IEnumerable<T> others, int mask)
```

**Parameters** \
`map` [Map&](../../Murder/Core/Map.html) \
`ignoreId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`others` [IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \
`mask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### CollidesAtTile(Map&, ColliderComponent, Vector2, int)
```csharp
public bool CollidesAtTile(Map& map, ColliderComponent collider, Vector2 position, int mask)
```

**Parameters** \
`map` [Map&](../../Murder/Core/Map.html) \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`mask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### CollidesWith(Entity, Entity, Vector2)
```csharp
public bool CollidesWith(Entity entityA, Entity entityB, Vector2 positionA)
```

**Parameters** \
`entityA` [Entity](../../Bang/Entities/Entity.html) \
`entityB` [Entity](../../Bang/Entities/Entity.html) \
`positionA` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### CollidesWith(Entity, Entity)
```csharp
public bool CollidesWith(Entity entityA, Entity entityB)
```

**Parameters** \
`entityA` [Entity](../../Bang/Entities/Entity.html) \
`entityB` [Entity](../../Bang/Entities/Entity.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### CollidesWith(IShape, Point, IShape, Point)
```csharp
public bool CollidesWith(IShape shape1, Point position1, IShape shape2, Point position2)
```

**Parameters** \
`shape1` [IShape](../../Murder/Core/Geometry/IShape.html) \
`position1` [Point](../../Murder/Core/Geometry/Point.html) \
`shape2` [IShape](../../Murder/Core/Geometry/IShape.html) \
`position2` [Point](../../Murder/Core/Geometry/Point.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### ContainsPoint(Entity, Point)
```csharp
public bool ContainsPoint(Entity entity, Point point)
```

**Parameters** \
`entity` [Entity](../../Bang/Entities/Entity.html) \
`point` [Point](../../Murder/Core/Geometry/Point.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### FindClosestEntityOnRange(World, Vector2, float, int, HashSet<T>, out Entity&, out Nullable`1&)
```csharp
public bool FindClosestEntityOnRange(World world, Vector2 fromPosition, float range, int collisionLayer, HashSet<T> excludeEntities, Entity& target, Nullable`1& location)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`fromPosition` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`range` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`collisionLayer` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`excludeEntities` [HashSet\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.HashSet-1?view=net-7.0) \
`target` [Entity&](../../Bang/Entities/Entity.html) \
`location` [T?&](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### GetFirstMtvAt(Map&, HashSet<T>, ColliderComponent, Vector2, IEnumerable<T>, int, out Int32&, out Int32&, out Vector2&)
```csharp
public bool GetFirstMtvAt(Map& map, HashSet<T> ignoreIds, ColliderComponent collider, Vector2 position, IEnumerable<T> others, int mask, Int32& hitId, Int32& layer, Vector2& mtv)
```

**Parameters** \
`map` [Map&](../../Murder/Core/Map.html) \
`ignoreIds` [HashSet\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.HashSet-1?view=net-7.0) \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`others` [IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \
`mask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`hitId` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`layer` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`mtv` [Vector2&](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### HasCachedCollisionWith(Entity, int)
```csharp
public bool HasCachedCollisionWith(Entity entity, int entityId)
```

Check if a trigger is colliding with an actor via the TriggerCollisionSystem.

**Parameters** \
`entity` [Entity](../../Bang/Entities/Entity.html) \
\
`entityId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### HasLineOfSight(World, Entity, Entity)
```csharp
public bool HasLineOfSight(World world, Entity from, Entity to)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`from` [Entity](../../Bang/Entities/Entity.html) \
`to` [Entity](../../Bang/Entities/Entity.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Raycast(World, Vector2, Vector2, int, IEnumerable<T>, out RaycastHit&)
```csharp
public bool Raycast(World world, Vector2 startPosition, Vector2 endPosition, int layerMask, IEnumerable<T> ignoreEntities, RaycastHit& hit)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`startPosition` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`endPosition` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`layerMask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`ignoreEntities` [IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \
`hit` [RaycastHit&](../../Murder/Services/RaycastHit.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### RaycastTiles(World, Vector2, Vector2, int, out RaycastHit&)
```csharp
public bool RaycastTiles(World world, Vector2 startPosition, Vector2 endPosition, int flags, RaycastHit& hit)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`startPosition` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`endPosition` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`flags` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`hit` [RaycastHit&](../../Murder/Services/RaycastHit.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### RemoveFromCollisionCache(Entity, int)
```csharp
public bool RemoveFromCollisionCache(Entity entity, int entityId)
```

Removes an ID from the IsColliding component. This is usually handled by TriggerPhysics system, since a message must be sent when exiting a collision.

**Parameters** \
`entity` [Entity](../../Bang/Entities/Entity.html) \
\
`entityId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

#### ConeCheck(World, Vector2, float, float, float, int)
```csharp
public IEnumerable<T> ConeCheck(World world, Vector2 coneStart, float range, float angle, float angleRange, int collisionLayer)
```

Checks for collisions in a cone.

**Parameters** \
`world` [World](../../Bang/World.html) \
`coneStart` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`range` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`angle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`angleRange` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`collisionLayer` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

#### GetAllCollisionsAt(World, Point, ColliderComponent, int, int)
```csharp
public IEnumerable<T> GetAllCollisionsAt(World world, Point position, ColliderComponent collider, int ignoreId, int mask)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`position` [Point](../../Murder/Core/Geometry/Point.html) \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`ignoreId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`mask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

#### Neighbours(Vector2, World)
```csharp
public IEnumerable<T> Neighbours(Vector2 position, World world)
```

Get all the neighbours of a position within the world.
            This does not check for collision (yet)!

**Parameters** \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`world` [World](../../Bang/World.html) \

**Returns** \
[IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

#### FilterEntities(World, int)
```csharp
public ImmutableArray<T> FilterEntities(World world, int layerMask)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`layerMask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FilterPositionAndColliderEntities(World, Func<T, TResult>)
```csharp
public ImmutableArray<T> FilterPositionAndColliderEntities(World world, Func<T, TResult> filter)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`filter` [Func\<T, TResult\>](https://learn.microsoft.com/en-us/dotnet/api/System.Func-2?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FilterPositionAndColliderEntities(World, int, Type[])
```csharp
public ImmutableArray<T> FilterPositionAndColliderEntities(World world, int layerMask, Type[] requireComponents)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`layerMask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`requireComponents` [Type[]](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FilterPositionAndColliderEntities(World, int)
```csharp
public ImmutableArray<T> FilterPositionAndColliderEntities(World world, int layerMask)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`layerMask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FilterPositionAndColliderEntities(IEnumerable<T>, int)
```csharp
public ImmutableArray<T> FilterPositionAndColliderEntities(IEnumerable<T> entities, int layerMask)
```

**Parameters** \
`entities` [IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \
`layerMask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### GetCarveBoundingBox(ColliderComponent, Point)
```csharp
public IntRectangle GetCarveBoundingBox(ColliderComponent collider, Point position)
```

**Parameters** \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Point](../../Murder/Core/Geometry/Point.html) \

**Returns** \
[IntRectangle](../../Murder/Core/Geometry/IntRectangle.html) \

#### GetColliderBoundingBox(Entity)
```csharp
public IntRectangle GetColliderBoundingBox(Entity target)
```

Get bounding box of an entity that contains both [ColliderComponent](../../Murder/Components/ColliderComponent.html)
            and [PositionComponent](../../Murder/Components/PositionComponent.html).

**Parameters** \
`target` [Entity](../../Bang/Entities/Entity.html) \

**Returns** \
[IntRectangle](../../Murder/Core/Geometry/IntRectangle.html) \

#### GetCollidersBoundingBox(ColliderComponent, Point, bool)
```csharp
public IntRectangle[] GetCollidersBoundingBox(ColliderComponent collider, Point position, bool gridCoordinates)
```

**Parameters** \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Point](../../Murder/Core/Geometry/Point.html) \
`gridCoordinates` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[IntRectangle[]](../../Murder/Core/Geometry/IntRectangle.html) \

#### GetMtvAt(Map&, int, ColliderComponent, Vector2, IEnumerable<T>, int, out Int32&)
```csharp
public List<T> GetMtvAt(Map& map, int ignoreId, ColliderComponent collider, Vector2 position, IEnumerable<T> others, int mask, Int32& hitId)
```

**Parameters** \
`map` [Map&](../../Murder/Core/Map.html) \
`ignoreId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`others` [IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \
`mask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`hitId` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[List\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=net-7.0) \

#### GetBoundingBox(ColliderComponent, Vector2)
```csharp
public Rectangle GetBoundingBox(ColliderComponent collider, Vector2 position)
```

**Parameters** \
`collider` [ColliderComponent](../../Murder/Components/ColliderComponent.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[Rectangle](../../Murder/Core/Geometry/Rectangle.html) \

#### FindNextAvailablePosition(World, Entity, Vector2, NextAvailablePositionFlags)
```csharp
public T? FindNextAvailablePosition(World world, Entity e, Vector2 target, NextAvailablePositionFlags flags)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`e` [Entity](../../Bang/Entities/Entity.html) \
`target` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`flags` [NextAvailablePositionFlags](../../Murder/Services/NextAvailablePositionFlags.html) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

#### AddToCollisionCache(Entity, int)
```csharp
public void AddToCollisionCache(Entity entity, int entityId)
```

**Parameters** \
`entity` [Entity](../../Bang/Entities/Entity.html) \
`entityId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### GetAllCollisionsAtGrid(World, Point, List`1&)
```csharp
public void GetAllCollisionsAtGrid(World world, Point grid, List`1& output)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`grid` [Point](../../Murder/Core/Geometry/Point.html) \
`output` [List\<T\>&](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=net-7.0) \



⚡