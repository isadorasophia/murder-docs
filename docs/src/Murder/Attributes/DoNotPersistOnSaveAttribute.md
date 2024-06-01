# DoNotPersistOnSaveAttribute

**Namespace:** Murder.Attributes \
**Assembly:** Murder.dll

```csharp
public class DoNotPersistOnSaveAttribute : Attribute
```

**Implements:** _[Attribute](https://learn.microsoft.com/en-us/dotnet/api/System.Attribute?view=net-7.0)_

### ⭐ Constructors
```csharp
public DoNotPersistOnSaveAttribute()
```

```csharp
public DoNotPersistOnSaveAttribute(Type exceptIfComponentIsPresent)
```

**Parameters** \
`exceptIfComponentIsPresent` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

### ⭐ Properties
#### ExceptIfComponentIsPresent
```csharp
public readonly Type ExceptIfComponentIsPresent;
```

This will dismiss this attribute and persist the component on the serialization if the following IComponent type is present.

**Returns** \
[Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
#### TypeId
```csharp
public virtual Object TypeId { get; }
```

**Returns** \
[Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \


⚡