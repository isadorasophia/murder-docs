# SpriteEventData

**Namespace:** Murder.Editor.Assets \
**Assembly:** Murder.dll

```csharp
public class SpriteEventData
```

### ⭐ Constructors
```csharp
public SpriteEventData()
```

### ⭐ Properties
#### DeletedEvents
```csharp
public readonly Dictionary<TKey, TValue> DeletedEvents;
```

**Returns** \
[Dictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2?view=net-7.0) \
#### Events
```csharp
public readonly Dictionary<TKey, TValue> Events;
```

**Returns** \
[Dictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2?view=net-7.0) \
### ⭐ Methods
#### GetEventsForAnimation(string)
```csharp
public Dictionary<TKey, TValue> GetEventsForAnimation(string animation)
```

**Parameters** \
`animation` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Dictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2?view=net-7.0) \

#### AddEvent(string, int, string)
```csharp
public void AddEvent(string animation, int frame, string message)
```

**Parameters** \
`animation` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`frame` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`message` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### FilterEventsForAnimation(string, Dictionary`2&)
```csharp
public void FilterEventsForAnimation(string animation, Dictionary`2& events)
```

**Parameters** \
`animation` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`events` [Dictionary\<TKey, TValue\>&](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2?view=net-7.0) \

#### RemoveEvent(string, int)
```csharp
public void RemoveEvent(string animation, int frame)
```

**Parameters** \
`animation` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`frame` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \



⚡