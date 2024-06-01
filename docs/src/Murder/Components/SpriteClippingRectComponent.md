# SpriteClippingRectComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct SpriteClippingRectComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public SpriteClippingRectComponent(float left, float right, float top, float down, ClippingStyle clippingStyle)
```

**Parameters** \
`left` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`right` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`top` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`down` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`clippingStyle` [ClippingStyle](../../Murder/Components/ClippingStyle.html) \

### ⭐ Properties
#### Down
```csharp
public readonly float Down;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Left
```csharp
public readonly float Left;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Right
```csharp
public readonly float Right;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Style
```csharp
public readonly ClippingStyle Style;
```

**Returns** \
[ClippingStyle](../../Murder/Components/ClippingStyle.html) \
#### Top
```csharp
public readonly float Top;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
### ⭐ Methods
#### GetClippingRect(Point)
```csharp
public Rectangle GetClippingRect(Point spriteSize)
```

**Parameters** \
`spriteSize` [Point](../../Murder/Core/Geometry/Point.html) \

**Returns** \
[Rectangle](../../Murder/Core/Geometry/Rectangle.html) \



⚡