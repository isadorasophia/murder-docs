# Color

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public sealed struct Color : IEquatable<T>
```

The color type as described by the engine. Values are represented as [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) from 0 to 1.
            To create a color using 0-255, use [Color.CreateFrom256(System.Int32,System.Int32,System.Int32)](../../../Murder/Core/Graphics/Color.html#createfrom256(int,).

**Implements:** _[IEquatable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=net-7.0)_

### ⭐ Constructors
```csharp
public Color(float r, float g, float b, float a)
```

Creates a color with the specified values. If the fourth
            argument is omitted, the value used for the alpha will be 1,
            meaning a completely opaque color.
            Do note colors in Murder use 0-1 as their range.
            To initialize a color using 0-255, please refer to [Color.CreateFrom256(System.Int32,System.Int32,System.Int32)](../../../Murder/Core/Graphics/Color.html#createfrom256(int,).

**Parameters** \
`r` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`g` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`b` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`a` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

### ⭐ Properties
#### A
```csharp
public readonly float A;
```

Transparency of this color.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### B
```csharp
public readonly float B;
```

Amount of blue in this color.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Black
```csharp
public static Color Black { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Blue
```csharp
public static Color Blue { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### BrightGray
```csharp
public static Color BrightGray { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### ColdGray
```csharp
public static Color ColdGray { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### G
```csharp
public readonly float G;
```

Amount of green in this color.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Gray
```csharp
public static Color Gray { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Green
```csharp
public static Color Green { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Magenta
```csharp
public static Color Magenta { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Orange
```csharp
public static Color Orange { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### R
```csharp
public readonly float R;
```

Amount of red in this color.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Red
```csharp
public static Color Red { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Transparent
```csharp
public static Color Transparent { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### WarmGray
```csharp
public static Color WarmGray { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### White
```csharp
public static Color White { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
### ⭐ Methods
#### CreateFrom256(int, int, int)
```csharp
public Color CreateFrom256(int r, int g, int b)
```

**Parameters** \
`r` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`g` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`b` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### Darken(float)
```csharp
public Color Darken(float r)
```

**Parameters** \
`r` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### FadeAlpha(float)
```csharp
public Color FadeAlpha(float alpha)
```

**Parameters** \
`alpha` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### FromHex(string)
```csharp
public Color FromHex(string hex)
```

Parses a string <paramref name="hex" /> to [Color](../../../Murder/Core/Graphics/Color.html).

**Parameters** \
`hex` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
\

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
\

#### Lerp(Color, Color, float)
```csharp
public Color Lerp(Color a, Color b, float factor)
```

**Parameters** \
`a` [Color](../../../Murder/Core/Graphics/Color.html) \
`b` [Color](../../../Murder/Core/Graphics/Color.html) \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### Parse(string)
```csharp
public Color Parse(string str)
```

**Parameters** \
`str` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### Premultiply()
```csharp
public Color Premultiply()
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### ToUint(Vector4)
```csharp
public uint ToUint(Vector4 Color)
```

**Parameters** \
`Color` [Vector4](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector4?view=net-7.0) \

**Returns** \
[uint](https://learn.microsoft.com/en-us/dotnet/api/System.UInt32?view=net-7.0) \

#### ToSysVector4()
```csharp
public Vector4 ToSysVector4()
```

**Returns** \
[Vector4](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector4?view=net-7.0) \

#### Equals(Color)
```csharp
public virtual bool Equals(Color other)
```

**Parameters** \
`other` [Color](../../../Murder/Core/Graphics/Color.html) \

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