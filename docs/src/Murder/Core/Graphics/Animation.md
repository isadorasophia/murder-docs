# Animation

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public sealed struct Animation
```

### ⭐ Constructors
```csharp
public Animation()
```

```csharp
public Animation(ImmutableArray<T> frames, ImmutableArray<T> framesDuration, ImmutableDictionary<TKey, TValue> events, float animationDuration, T? sequence)
```

**Parameters** \
`frames` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
`framesDuration` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
`events` [ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \
`animationDuration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`sequence` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

```csharp
public Animation(Int32[] frames, Single[] framesDuration, Dictionary<TKey, TValue> events, T? sequence)
```

**Parameters** \
`frames` [int[]](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`framesDuration` [float[]](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`events` [Dictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2?view=net-7.0) \
`sequence` [T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

### ⭐ Properties
#### AnimationDuration
```csharp
public readonly float AnimationDuration;
```

The total duration of the animation, in seconds

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Empty
```csharp
public static Animation Empty;
```

**Returns** \
[Animation](../../../Murder/Core/Graphics/Animation.html) \
#### Events
```csharp
public readonly ImmutableDictionary<TKey, TValue> Events;
```

A dictionary associating integer indices with event strings

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \
#### FrameCount
```csharp
public int FrameCount { get; }
```

A property representing the number of frames in the animation

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Frames
```csharp
public readonly ImmutableArray<T> Frames;
```

An array of integers representing the indices of the frames in the animation

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
#### FramesDuration
```csharp
public readonly ImmutableArray<T> FramesDuration;
```

An array of floats representing the duration of each frame in the animation, in milliseconds

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
#### NextAnimation
```csharp
public readonly T? NextAnimation;
```

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \
### ⭐ Methods
#### WithMessageAt(int, string)
```csharp
public Animation WithMessageAt(int frame, string message)
```

Used by the editor when applying custom messages to an animation.

**Parameters** \
`frame` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`message` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Animation](../../../Murder/Core/Graphics/Animation.html) \

#### WithoutMessageAt(int)
```csharp
public Animation WithoutMessageAt(int frame)
```

Used by the editor when applying custom messages to an animation.

**Parameters** \
`frame` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[Animation](../../../Murder/Core/Graphics/Animation.html) \

#### Evaluate(float, bool)
```csharp
public FrameInfo Evaluate(float time, bool animationLoop)
```

Evaluates the current frame of the animation, given a time value (in seconds)
            and an optional maximum animation duration (in seconds)

**Parameters** \
`time` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`animationLoop` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[FrameInfo](../../../Murder/Core/FrameInfo.html) \

#### Evaluate(Single&, bool, float)
```csharp
public FrameInfo Evaluate(Single& time, bool animationLoop, float forceAnimationDuration)
```

**Parameters** \
`time` [float&](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`animationLoop` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`forceAnimationDuration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[FrameInfo](../../../Murder/Core/FrameInfo.html) \



⚡