# SerializationHelper

**Namespace:** Murder.Utilities \
**Assembly:** Murder.dll

```csharp
public static class SerializationHelper
```

### ⭐ Methods
#### WithModifiers(IJsonTypeInfoResolver, Action`1[])
```csharp
public IJsonTypeInfoResolver WithModifiers(IJsonTypeInfoResolver resolver, Action`1[] modifiers)
```

**Parameters** \
`resolver` [IJsonTypeInfoResolver](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.IJsonTypeInfoResolver?view=net-7.0) \
`modifiers` [Action\<T\>[]](https://learn.microsoft.com/en-us/dotnet/api/System.Action-1?view=net-7.0) \

**Returns** \
[IJsonTypeInfoResolver](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.IJsonTypeInfoResolver?view=net-7.0) \

#### DeepCopy(T)
```csharp
public T DeepCopy(T c)
```

**Parameters** \
`c` [T](../../) \

**Returns** \
[T](../../) \

#### ApplyModifierForPrivateFieldsAndGetters(JsonTypeInfo)
```csharp
public void ApplyModifierForPrivateFieldsAndGetters(JsonTypeInfo jsonTypeInfo)
```

**Parameters** \
`jsonTypeInfo` [JsonTypeInfo](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.Metadata.JsonTypeInfo?view=net-7.0) \



⚡