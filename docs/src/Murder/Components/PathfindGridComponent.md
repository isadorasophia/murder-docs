# PathfindGridComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct PathfindGridComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public PathfindGridComponent()
```

```csharp
public PathfindGridComponent(ImmutableArray<T> cells)
```

**Parameters** \
`cells` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

### ⭐ Properties
#### Cells
```csharp
public readonly ImmutableArray<T> Cells;
```

Unique collection of cell properties. "How do we keep this unique", you ask?
            This is responsability of the editor editing this. This cannot be a dictionary (I would love to!)
            because it will break the deterministic behavior of the world.

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \


⚡