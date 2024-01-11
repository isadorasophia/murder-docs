# IntRectangle

**Namespace:** Murder.Core.Geometry \
**Assembly:** Murder.dll

```csharp
public sealed struct IntRectangle : IEquatable<T>
```

**Implements:** _[IEquatable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=net-7.0)_

### ⭐ Constructors
```csharp
public IntRectangle(Point p, int width, int height)
```

**Parameters** \
`p` [Point](../../../Murder/Core/Geometry/Point.html) \
`width` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`height` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

```csharp
public IntRectangle(Point position, Point size)
```

**Parameters** \
`position` [Point](../../../Murder/Core/Geometry/Point.html) \
`size` [Point](../../../Murder/Core/Geometry/Point.html) \

```csharp
public IntRectangle(float x, float y, float width, float height)
```

**Parameters** \
`x` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`y` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`width` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`height` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

```csharp
public IntRectangle(int x, int y, int width, int height)
```

**Parameters** \
`x` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`y` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`width` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`height` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

### ⭐ Properties
#### Bottom
```csharp
public int Bottom { get; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### BottomLeft
```csharp
public Point BottomLeft { get; }
```

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### BottomRight
```csharp
public Point BottomRight { get; }
```

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### Center
```csharp
public Vector2 Center { get; }
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### CenterPoint
```csharp
public Point CenterPoint { get; }
```

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### Empty
```csharp
public static IntRectangle Empty { get; }
```

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \
#### Height
```csharp
public int Height;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Left
```csharp
public int Left { get; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### One
```csharp
public static IntRectangle One { get; }
```

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \
#### Right
```csharp
public int Right { get; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Size
```csharp
public Point Size { get; public set; }
```

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### Top
```csharp
public int Top { get; }
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### TopLeft
```csharp
public Point TopLeft { get; }
```

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### TopRight
```csharp
public Point TopRight { get; }
```

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### Width
```csharp
public int Width;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### X
```csharp
public int X;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Y
```csharp
public int Y;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
### ⭐ Methods
#### Contains(Point)
```csharp
public bool Contains(Point point)
```

**Parameters** \
`point` [Point](../../../Murder/Core/Geometry/Point.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Contains(Rectangle)
```csharp
public bool Contains(Rectangle other)
```

**Parameters** \
`other` [Rectangle](../../../Murder/Core/Geometry/Rectangle.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Contains(float, float)
```csharp
public bool Contains(float X, float Y)
```

**Parameters** \
`X` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`Y` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Contains(int, int)
```csharp
public bool Contains(int X, int Y)
```

**Parameters** \
`X` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`Y` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Touches(Rectangle)
```csharp
public bool Touches(Rectangle other)
```

Gets whether or not the other [Rectangle](../../../Murder/Core/Geometry/Rectangle.html) intersects with this rectangle.

**Parameters** \
`other` [Rectangle](../../../Murder/Core/Geometry/Rectangle.html) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

#### TouchesInside(Rectangle)
```csharp
public bool TouchesInside(Rectangle other)
```

Gets whether or not the other [Rectangle](../../../Murder/Core/Geometry/Rectangle.html) intersects with this rectangle.

**Parameters** \
`other` [Rectangle](../../../Murder/Core/Geometry/Rectangle.html) \
\

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

#### AddPosition(Point)
```csharp
public IntRectangle AddPosition(Point position)
```

**Parameters** \
`position` [Point](../../../Murder/Core/Geometry/Point.html) \

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

#### AddPosition(Vector2)
```csharp
public IntRectangle AddPosition(Vector2 position)
```

**Parameters** \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

#### CenterRectangle(Vector2, float, float)
```csharp
public IntRectangle CenterRectangle(Vector2 center, float width, float height)
```

**Parameters** \
`center` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`width` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`height` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

#### Expand(float)
```csharp
public IntRectangle Expand(float value)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

#### Expand(int)
```csharp
public IntRectangle Expand(int value)
```

**Parameters** \
`value` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

#### FromCoordinates(Point, Point)
```csharp
public IntRectangle FromCoordinates(Point topLeft, Point bottomRight)
```

**Parameters** \
`topLeft` [Point](../../../Murder/Core/Geometry/Point.html) \
`bottomRight` [Point](../../../Murder/Core/Geometry/Point.html) \

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

#### FromCoordinates(int, int, int, int)
```csharp
public IntRectangle FromCoordinates(int top, int bottom, int left, int right)
```

**Parameters** \
`top` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`bottom` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`left` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`right` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

#### ClampPosition(IntRectangle)
```csharp
public Point ClampPosition(IntRectangle innerRect)
```

**Parameters** \
`innerRect` [IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \

#### Clamp(Vector2)
```csharp
public Vector2 Clamp(Vector2 point)
```

**Parameters** \
`point` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### Equals(IntRectangle)
```csharp
public virtual bool Equals(IntRectangle other)
```

**Parameters** \
`other` [IntRectangle](../../../Murder/Core/Geometry/IntRectangle.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Equals(Object)
```csharp
public virtual bool Equals(Object obj)
```

**Parameters** \
`obj` [Object](https://learn.microsoft.com/en-us/dotnet/api/System.Object?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### GetHashCode()
```csharp
public virtual int GetHashCode()
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### ToString()
```csharp
public virtual string ToString()
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \



⚡