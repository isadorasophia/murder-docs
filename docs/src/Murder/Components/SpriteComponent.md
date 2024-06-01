# SpriteComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct SpriteComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public SpriteComponent()
```

```csharp
public SpriteComponent(Portrait portrait, int batchId)
```

**Parameters** \
`portrait` [Portrait](../../Murder/Core/Portrait.html) \
`batchId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

```csharp
public SpriteComponent(Portrait portrait)
```

**Parameters** \
`portrait` [Portrait](../../Murder/Core/Portrait.html) \

```csharp
public SpriteComponent(Guid guid, Vector2 offset, ImmutableArray<T> id, int ySortOffset, bool rotate, bool flip, OutlineStyle highlightStyle, int targetSpriteBatch)
```

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`offset` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`id` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
`ySortOffset` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`rotate` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`flip` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`highlightStyle` [OutlineStyle](../../Murder/Core/Graphics/OutlineStyle.html) \
`targetSpriteBatch` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

### ⭐ Properties
#### AnimationGuid
```csharp
public Guid AnimationGuid { get; public set; }
```

The Guid of the Aseprite file.

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### CurrentAnimation
```csharp
public string CurrentAnimation { get; }
```

Current playing animation id.

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### FlipWithFacing
```csharp
public readonly bool FlipWithFacing;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### HighlightStyle
```csharp
public OutlineStyle HighlightStyle { get; public set; }
```

**Returns** \
[OutlineStyle](../../Murder/Core/Graphics/OutlineStyle.html) \
#### NextAnimations
```csharp
public ImmutableArray<T> NextAnimations { get; public set; }
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
#### Offset
```csharp
public readonly Vector2 Offset;
```

(0,0) is top left and (1,1) is bottom right

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### RotateWithFacing
```csharp
public readonly bool RotateWithFacing;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### TargetSpriteBatch
```csharp
public readonly int TargetSpriteBatch;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### UseUnscaledTime
```csharp
public readonly bool UseUnscaledTime;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### YSortOffset
```csharp
public int YSortOffset { get; public set; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
### ⭐ Methods
#### HasAnimation(string)
```csharp
public bool HasAnimation(string animationName)
```

**Parameters** \
`animationName` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### IsPlaying(ImmutableArray<T>)
```csharp
public bool IsPlaying(ImmutableArray<T> animations)
```

**Parameters** \
`animations` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Play(ImmutableArray<T>)
```csharp
public SpriteComponent Play(ImmutableArray<T> id)
```

**Parameters** \
`id` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

**Returns** \
[SpriteComponent](../../Murder/Components/SpriteComponent.html) \

#### Play(String[])
```csharp
public SpriteComponent Play(String[] id)
```

**Parameters** \
`id` [string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[SpriteComponent](../../Murder/Components/SpriteComponent.html) \

#### PlayAfter(string)
```csharp
public SpriteComponent PlayAfter(string id)
```

**Parameters** \
`id` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[SpriteComponent](../../Murder/Components/SpriteComponent.html) \

#### SetBatch(int)
```csharp
public SpriteComponent SetBatch(int batch)
```

**Parameters** \
`batch` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[SpriteComponent](../../Murder/Components/SpriteComponent.html) \

#### WithPortrait(Portrait)
```csharp
public SpriteComponent WithPortrait(Portrait portrait)
```

**Parameters** \
`portrait` [Portrait](../../Murder/Core/Portrait.html) \

**Returns** \
[SpriteComponent](../../Murder/Components/SpriteComponent.html) \

#### WithSort(int)
```csharp
public SpriteComponent WithSort(int sort)
```

**Parameters** \
`sort` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[SpriteComponent](../../Murder/Components/SpriteComponent.html) \



⚡