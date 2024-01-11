# FrameInfo

**Namespace:** Murder.Core \
**Assembly:** Murder.dll

```csharp
public sealed struct FrameInfo
```

A struct representing information about a single animation frame, such as its index in the list and a flag indicating whether the animation is complete

### ⭐ Constructors
```csharp
public FrameInfo()
```

```csharp
public FrameInfo(Animation animation)
```

**Parameters** \
`animation` [Animation](../../Murder/Core/Graphics/Animation.html) \

```csharp
public FrameInfo(int frame, int internalFrame, bool animationComplete, Animation animation)
```

**Parameters** \
`frame` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`internalFrame` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`animationComplete` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`animation` [Animation](../../Murder/Core/Graphics/Animation.html) \

### ⭐ Properties
#### Animation
```csharp
public Animation Animation { get; public set; }
```

**Returns** \
[Animation](../../Murder/Core/Graphics/Animation.html) \
#### Complete
```csharp
public readonly bool Complete;
```

Whether the animation is complete

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Fail
```csharp
public static FrameInfo Fail { get; }
```

**Returns** \
[FrameInfo](../../Murder/Core/FrameInfo.html) \
#### Failed
```csharp
public bool Failed { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Frame
```csharp
public readonly int Frame;
```

The index of the current frame

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### InternalFrame
```csharp
public readonly int InternalFrame;
```

The index of the current frame inside the current animation

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \


⚡