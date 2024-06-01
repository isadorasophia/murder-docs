# EntityModifier

**Namespace:** Murder.Prefabs \
**Assembly:** Murder.dll

```csharp
public class EntityModifier
```

### ⭐ Constructors
```csharp
public EntityModifier(Guid guid)
```

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

### ⭐ Properties
#### Children
```csharp
public ImmutableArray<T> Children { get; }
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
#### Guid
```csharp
public readonly Guid Guid;
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
### ⭐ Methods
#### HasChild(Guid)
```csharp
public bool HasChild(Guid childId)
```

**Parameters** \
`childId` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### HasComponent(Type)
```csharp
public bool HasComponent(Type t)
```

**Parameters** \
`t` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### IsComponentRemoved(Type)
```csharp
public bool IsComponentRemoved(Type t)
```

**Parameters** \
`t` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### TryGetComponent(Type, out IComponent&)
```csharp
public bool TryGetComponent(Type t, IComponent& result)
```

**Parameters** \
`t` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
`result` [IComponent&](../../Bang/Components/IComponent.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### UndoCustomComponent(Type)
```csharp
public bool UndoCustomComponent(Type t)
```

**Parameters** \
`t` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### ApplyModifiersFrom(EntityModifier)
```csharp
public EntityModifier ApplyModifiersFrom(EntityModifier other)
```

Merge modifier with <paramref name="other" />.
            This will prioritize items present in <paramref name="other" />.

**Parameters** \
`other` [EntityModifier](../../Murder/Prefabs/EntityModifier.html) \

**Returns** \
[EntityModifier](../../Murder/Prefabs/EntityModifier.html) \

#### FetchChildren()
```csharp
public ImmutableArray<T> FetchChildren()
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FilterComponents(IEnumerable`1&)
```csharp
public ImmutableArray<T> FilterComponents(IEnumerable`1& allComponents)
```

**Parameters** \
`allComponents` [IEnumerable\<T\>&](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### AddChild(EntityInstance)
```csharp
public void AddChild(EntityInstance child)
```

**Parameters** \
`child` [EntityInstance](../../Murder/Prefabs/EntityInstance.html) \

#### AddOrReplaceComponent(IComponent)
```csharp
public void AddOrReplaceComponent(IComponent c)
```

**Parameters** \
`c` [IComponent](../../Bang/Components/IComponent.html) \

#### RemoveChild(Guid)
```csharp
public void RemoveChild(Guid guid)
```

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

#### RemoveComponent(Type)
```csharp
public void RemoveComponent(Type t)
```

**Parameters** \
`t` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \



⚡