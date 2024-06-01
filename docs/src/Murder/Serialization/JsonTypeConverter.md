# JsonTypeConverter

**Namespace:** Murder.Serialization \
**Assembly:** Murder.dll

```csharp
public class JsonTypeConverter : JsonConverter<T>
```

**Implements:** _[JsonConverter\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Serialization.JsonConverter-1?view=net-7.0)_

### ⭐ Constructors
```csharp
public JsonTypeConverter()
```

### ⭐ Properties
#### HandleNull
```csharp
public virtual bool HandleNull { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Type
```csharp
public virtual Type Type { get; }
```

**Returns** \
[Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
### ⭐ Methods
#### CanConvert(Type)
```csharp
public virtual bool CanConvert(Type typeToConvert)
```

**Parameters** \
`typeToConvert` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Read(Utf8JsonReader&, Type, JsonSerializerOptions)
```csharp
public virtual Type Read(Utf8JsonReader& reader, Type typeToConvert, JsonSerializerOptions options)
```

**Parameters** \
`reader` [Utf8JsonReader&](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Utf8JsonReader?view=net-7.0) \
`typeToConvert` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
`options` [JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) \

**Returns** \
[Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

#### ReadAsPropertyName(Utf8JsonReader&, Type, JsonSerializerOptions)
```csharp
public virtual Type ReadAsPropertyName(Utf8JsonReader& reader, Type typeToConvert, JsonSerializerOptions options)
```

**Parameters** \
`reader` [Utf8JsonReader&](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Utf8JsonReader?view=net-7.0) \
`typeToConvert` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
`options` [JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) \

**Returns** \
[Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \

#### Write(Utf8JsonWriter, Type, JsonSerializerOptions)
```csharp
public virtual void Write(Utf8JsonWriter writer, Type value, JsonSerializerOptions options)
```

**Parameters** \
`writer` [Utf8JsonWriter](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Utf8JsonWriter?view=net-7.0) \
`value` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
`options` [JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) \

#### WriteAsPropertyName(Utf8JsonWriter, Type, JsonSerializerOptions)
```csharp
public virtual void WriteAsPropertyName(Utf8JsonWriter writer, Type value, JsonSerializerOptions options)
```

**Parameters** \
`writer` [Utf8JsonWriter](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.Utf8JsonWriter?view=net-7.0) \
`value` [Type](https://learn.microsoft.com/en-us/dotnet/api/System.Type?view=net-7.0) \
`options` [JsonSerializerOptions](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.JsonSerializerOptions?view=net-7.0) \

#### GetDefaultConverterStrategy()
```csharp
virtual ConverterStrategy GetDefaultConverterStrategy()
```

**Returns** \
[ConverterStrategy](https://learn.microsoft.com/en-us/dotnet/api/System.Text.Json.ConverterStrategy?view=net-7.0) \



⚡