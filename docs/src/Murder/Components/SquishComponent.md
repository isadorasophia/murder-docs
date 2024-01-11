# SquishComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct SquishComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public SquishComponent(EaseKind easeIn, EaseKind easeOut, float start, float duration, float amount)
```

**Parameters** \
`easeIn` [EaseKind](../../Murder/Utilities/EaseKind.html) \
`easeOut` [EaseKind](../../Murder/Utilities/EaseKind.html) \
`start` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`amount` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

```csharp
public SquishComponent(EaseKind easeOut, float start, float duration, float amount)
```

**Parameters** \
`easeOut` [EaseKind](../../Murder/Utilities/EaseKind.html) \
`start` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`amount` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

### ⭐ Properties
#### Amount
```csharp
public readonly float Amount;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Duration
```csharp
public readonly float Duration;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### EaseIn
```csharp
public readonly T? EaseIn;
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### EaseOut
```csharp
public readonly T? EaseOut;
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### ScaledTime
```csharp
public bool ScaledTime { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Start
```csharp
public readonly float Start;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \


⚡