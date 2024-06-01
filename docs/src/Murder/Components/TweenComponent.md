# TweenComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct TweenComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public TweenComponent()
```

```csharp
public TweenComponent(float timeStart, float timeEnd)
```

**Parameters** \
`timeStart` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`timeEnd` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

### ⭐ Properties
#### Ease
```csharp
public EaseKind Ease { get; public set; }
```

**Returns** \
[EaseKind](../../Murder/Utilities/EaseKind.html) \
#### Position
```csharp
public T? Position { get; public set; }
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### Scale
```csharp
public T? Scale { get; public set; }
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
#### Time
```csharp
public FloatRange Time { get; public set; }
```

**Returns** \
[FloatRange](../../Murder/Core/FloatRange.html) \


⚡