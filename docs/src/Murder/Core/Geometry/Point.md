# Point

**Namespace:** Murder.Core.Geometry \
**Assembly:** Murder.dll

```csharp
public sealed struct Point : IEquatable<T>
```

Represents a single point with coordinates [Point.Y](../../../Murder/Core/Geometry/Point.html#y).
            Points are also often used to store sizes, with X marking the right of an object and Y marking its bottom.

**Implements:** _[IEquatable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=net-7.0)_

### ⭐ Constructors
```csharp
public Point(float x, float y)
```

Creates a point by rounding the x and y parameters.

**Parameters** \
`x` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`y` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

```csharp
public Point(int v)
```

Creates a point where both x and y and equal to v.

**Parameters** \
`v` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

```csharp
public Point(int x, int y)
```

Creates a point.

**Parameters** \
`x` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`y` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

### ⭐ Properties
#### Down
```csharp
public static Point Down { get; }
```

Point with coordinates X = 0 and Y = 1.

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### Flipped
```csharp
public static Point Flipped { get; }
```

Point with coordinates X = -1 and Y = 1 (multiply your point by this and you get its mirror).

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### HalfCell
```csharp
public static Point HalfCell { get; }
```

Represents half a cell on the current [Grid](../../../Murder/Core/Grid.html).

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### One
```csharp
public static Point One { get; }
```

Point with coordinates X = 1 and Y = 1.

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### X
```csharp
public int X;
```

The value of X in this point.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### XY
```csharp
public ValueTuple<T1, T2> XY { get; }
```

Destructuring helper for obtaining a tuple from this point.

**Returns** \
[ValueTuple\<T1, T2\>](https://learn.microsoft.com/en-us/dotnet/api/System.ValueTuple-2?view=net-7.0) \
#### Y
```csharp
public int Y;
```

The value of Y in this point.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Zero
```csharp
public static Point Zero { get; }
```

Point with coordinates X = 0 and Y = 0.

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
### ⭐ Methods
#### Length()
```csharp
public float Length()
```

Calculates the length of this point.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### LengthSquared()
```csharp
public int LengthSquared()
```

Returns the length of this point, squared (IOW: X * X + Y * Y).

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### Max(Point)
```csharp
public Point Max(Point other)
```

**Parameters** \
`other` [Point](../../../Murder/Core/Geometry/Point.html) \

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \

#### Min(Point)
```csharp
public Point Min(Point other)
```

**Parameters** \
`other` [Point](../../../Murder/Core/Geometry/Point.html) \

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \

#### Mirror(Point)
```csharp
public Point Mirror(Point center)
```

Returns the mirror of this point across the X axis relative to the center point <paramref name="center" />

**Parameters** \
`center` [Point](../../../Murder/Core/Geometry/Point.html) \
\

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \

#### Scale(Point)
```csharp
public Point Scale(Point other)
```

Equivalent to this * other.

**Parameters** \
`other` [Point](../../../Murder/Core/Geometry/Point.html) \
\

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \

#### ToWorldPosition()
```csharp
public Point ToWorldPosition()
```

Converts this point into a world position by multiplying it by the cell size.

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \

#### BreakInTwo()
```csharp
public ValueTuple<T1, T2> BreakInTwo()
```

Deconstruction helper for obtaining a tuple from this point.

**Returns** \
[ValueTuple\<T1, T2\>](https://learn.microsoft.com/en-us/dotnet/api/System.ValueTuple-2?view=net-7.0) \

#### ToVector2()
```csharp
public Vector2 ToVector2()
```

Converts this point into a [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) with the same X and Y values.

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### ToVector3()
```csharp
public Vector3 ToVector3()
```

**Returns** \
[Vector3](https://docs.monogame.net/api/Microsoft.Xna.Framework.Vector3.html) \

#### Equals(Point)
```csharp
public virtual bool Equals(Point other)
```

Compares whether the point <paramref name="other" /> has the same X and Y value as this point.

**Parameters** \
`other` [Point](../../../Murder/Core/Geometry/Point.html) \

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

#### Deconstruct(out Int32&, out Int32&)
```csharp
public void Deconstruct(Int32& x, Int32& y)
```

**Parameters** \
`x` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`y` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \



⚡