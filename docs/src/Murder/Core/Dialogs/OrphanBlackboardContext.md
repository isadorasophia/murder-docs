# OrphanBlackboardContext

**Namespace:** Murder.Core.Dialogs \
**Assembly:** Murder.dll

```csharp
public sealed struct OrphanBlackboardContext
```

This is used to track variables created on the fly. This used to be an
            object, but the serialization doesn't really like that, so I'll follow a 
            similar pattern to other facts.

### ⭐ Constructors
```csharp
public OrphanBlackboardContext()
```

```csharp
public OrphanBlackboardContext(FactKind kind, T? boolValue, T? intValue, T? floatValue, string strValue)
```

**Parameters** \
`kind` [FactKind](../../../Murder/Core/Dialogs/FactKind.html) \
`boolValue` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
`intValue` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
`floatValue` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
`strValue` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

```csharp
public OrphanBlackboardContext(Object value)
```

**Parameters** \
`value` [Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \

### ⭐ Properties
#### BoolValue
```csharp
public readonly T? BoolValue;
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### FloatValue
```csharp
public readonly T? FloatValue;
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### IntValue
```csharp
public readonly T? IntValue;
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### Kind
```csharp
public readonly FactKind Kind;
```

**Returns** \
[FactKind](../../../Murder/Core/Dialogs/FactKind.html) \
#### StrValue
```csharp
public readonly string StrValue;
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
### ⭐ Methods
#### GetValue()
```csharp
public Object GetValue()
```

**Returns** \
[Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \



⚡