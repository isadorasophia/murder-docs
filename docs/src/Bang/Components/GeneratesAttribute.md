# GeneratesAttribute

**Namespace:** Bang.Components \
**Assembly:** Bang.dll

```csharp
public class GeneratesAttribute : Attribute
```

Marks a component that generates another component in runtime.

**Implements:** _[Attribute](https://learn.microsoft.com/en-us/dotnet/api/System.Attribute?view=net-7.0)_

### ⭐ Constructors
```csharp
public GeneratesAttribute(Type type)
```

Creates a new [GeneratesAttribute](../../Bang/Components/GeneratesAttribute.html).

**Parameters** \
`type` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
\

### ⭐ Properties
#### Type
```csharp
public Type Type { get; public set; }
```

Component which will be generated from the component that has this attribute.

**Returns** \
[Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
#### TypeId
```csharp
public virtual Object TypeId { get; }
```

**Returns** \
[Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \


⚡