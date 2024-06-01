# DestroyOnBlackboardConditionComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct DestroyOnBlackboardConditionComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public DestroyOnBlackboardConditionComponent()
```

```csharp
public DestroyOnBlackboardConditionComponent(CriterionNode node)
```

**Parameters** \
`node` [CriterionNode](../../Murder/Core/Dialogs/CriterionNode.html) \

### ⭐ Properties
#### Rules
```csharp
public readonly ImmutableArray<T> Rules;
```

List of requirements for destroying this object.

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \


⚡