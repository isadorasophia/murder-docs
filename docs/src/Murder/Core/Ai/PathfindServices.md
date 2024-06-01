# PathfindServices

**Namespace:** Murder.Core.Ai \
**Assembly:** Murder.dll

```csharp
public static class PathfindServices
```

### ⭐ Methods
#### FindPath(Map, World, Point, Point, PathfindAlgorithmKind, int)
```csharp
public ImmutableDictionary<TKey, TValue> FindPath(Map map, World world, Point initial, Point target, PathfindAlgorithmKind kind, int collisionMask)
```

Find a path between <paramref name="initial" /> and <paramref name="target" />.

**Parameters** \
`map` [Map](../../../Murder/Core/Map.html) \
`world` [World](../../../Bang/World.html) \
`initial` [Point](../../../Murder/Core/Geometry/Point.html) \
`target` [Point](../../../Murder/Core/Geometry/Point.html) \
`kind` [PathfindAlgorithmKind](../../../Murder/Core/Ai/PathfindAlgorithmKind.html) \
`collisionMask` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \

#### UpdatePathfind(World)
```csharp
public void UpdatePathfind(World world)
```

Update all cached pathfind on a map change.

**Parameters** \
`world` [World](../../../Bang/World.html) \
\



⚡