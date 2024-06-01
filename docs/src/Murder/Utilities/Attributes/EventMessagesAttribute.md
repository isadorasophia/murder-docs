# EventMessagesAttribute

**Namespace:** Murder.Utilities.Attributes \
**Assembly:** Murder.dll

```csharp
public class EventMessagesAttribute : Attribute
```

Notifies the editor that a set of events is available on this entity.

**Implements:** _[Attribute](https://learn.microsoft.com/en-us/dotnet/api/System.Attribute?view=net-7.0)_

### ⭐ Constructors
```csharp
public EventMessagesAttribute(EventMessageAttributeFlags flags, String[] events)
```

**Parameters** \
`flags` [EventMessageAttributeFlags](../../../Murder/Utilities/Attributes/EventMessageAttributeFlags.html) \
`events` [string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

```csharp
public EventMessagesAttribute(String[] events)
```

**Parameters** \
`events` [string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

### ⭐ Properties
#### Events
```csharp
public readonly String[] Events;
```

**Returns** \
[string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Flags
```csharp
public readonly EventMessageAttributeFlags Flags;
```

**Returns** \
[EventMessageAttributeFlags](../../../Murder/Utilities/Attributes/EventMessageAttributeFlags.html) \
#### TypeId
```csharp
public virtual Object TypeId { get; }
```

**Returns** \
[Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \


⚡