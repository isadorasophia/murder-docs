# LocalizedString

**Namespace:** Murder.Assets \
**Assembly:** Murder.dll

```csharp
public sealed struct LocalizedString
```

### ⭐ Constructors
```csharp
public LocalizedString()
```

```csharp
public LocalizedString(Guid id)
```

**Parameters** \
`id` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

```csharp
public LocalizedString(string overrideText)
```

**Parameters** \
`overrideText` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

### ⭐ Properties
#### Id
```csharp
public readonly Guid Id;
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### OverrideText
```csharp
public readonly string OverrideText;
```

Used when, for whatever reason, we need to override the data for a localized string
            with actual text (usually built in runtime).

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \


⚡