# IgnoreUntilComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct IgnoreUntilComponent : IComponent
```

Useful for tagging an entity for some systems until X time

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public IgnoreUntilComponent(float until)
```

**Parameters** \
`until` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

### ⭐ Properties
#### Until
```csharp
public readonly float Until;
```

When to remove this component. A negative value will never be automatically removed.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \


⚡