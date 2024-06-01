# Viewport

**Namespace:** Murder.Core \
**Assembly:** Murder.dll

```csharp
public sealed struct Viewport
```

### ⭐ Constructors
```csharp
public Viewport(Point viewportSize, Point nativeResolution, ViewportResizeStyle resizeStyle)
```

**Parameters** \
`viewportSize` [Point](../../Murder/Core/Geometry/Point.html) \
`nativeResolution` [Point](../../Murder/Core/Geometry/Point.html) \
`resizeStyle` [ViewportResizeStyle](../../Murder/Core/Graphics/ViewportResizeStyle.html) \

### ⭐ Properties
#### Center
```csharp
public readonly Vector2 Center;
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### NativeResolution
```csharp
public readonly Point NativeResolution;
```

The resolution that the game is actually rendered

**Returns** \
[Point](../../Murder/Core/Geometry/Point.html) \
#### OutputRectangle
```csharp
public readonly IntRectangle OutputRectangle;
```

The rectangle where the game should be rendered on the screen.

**Returns** \
[IntRectangle](../../Murder/Core/Geometry/IntRectangle.html) \
#### Scale
```csharp
public readonly Vector2 Scale;
```

The scale that is applied to the native resolution before rendering

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### Size
```csharp
public readonly Point Size;
```

The size of the viewport (tipically the game's window)

**Returns** \
[Point](../../Murder/Core/Geometry/Point.html) \
### ⭐ Methods
#### HasChanges(Point, Vector2)
```csharp
public bool HasChanges(Point size, Vector2 scale)
```

**Parameters** \
`size` [Point](../../Murder/Core/Geometry/Point.html) \
`scale` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \



⚡