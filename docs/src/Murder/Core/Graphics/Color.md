# Color

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public sealed struct Color : IEquatable<T>
```

The color type as described by the engine. Values are represented as [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) from 0 to 1.
            To create a color using 0-255, use [Color.CreateFrom256(System.Byte,System.Byte,System.Byte,System.Byte)](../../../Murder/Core/Graphics/Color.html#createfrom256(byte,).

**Implements:** _[IEquatable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.IEquatable-1?view=net-7.0)_

### ⭐ Constructors
```csharp
public Color(float r, float g, float b, float a)
```

Creates a color with the specified values. If the fourth
            argument is omitted, the value used for the alpha will be 1,
            meaning a completely opaque color.
            Do note colors in Murder use 0-1 as their range.
            To initialize a color using 0-255, please refer to [Color.CreateFrom256(System.Byte,System.Byte,System.Byte,System.Byte)](../../../Murder/Core/Graphics/Color.html#createfrom256(byte,).

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

Opaque color with 0 red, green or blue.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Blue
```csharp
public static Color Blue { get; }
```

Pure blue (no red or green).

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### BrightGray
```csharp
public static Color BrightGray { get; }
```

Opaque color with 65% red, 75% green and 75% blue.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### ColdGray
```csharp
public static Color ColdGray { get; }
```

Like [Color.Gray](../../../Murder/Core/Graphics/Color.html#gray) but with a blue-ish tint.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Cyan
```csharp
public static Color Cyan { get; }
```

Pure cyan (max green and blue, no red).

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

Opaque color with 50% red, green and blue.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Green
```csharp
public static Color Green { get; }
```

Pure green (no red or blue).

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Magenta
```csharp
public static Color Magenta { get; }
```

Pure magenta (max red and blue, no green).

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Orange
```csharp
public static Color Orange { get; }
```

A shade of orange.

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

Pure red (no green or blue).

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Transparent
```csharp
public static Color Transparent { get; }
```

[Color.Black](../../../Murder/Core/Graphics/Color.html#black) but with 0 alpha.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### WarmGray
```csharp
public static Color WarmGray { get; }
```

Like [Color.Gray](../../../Murder/Core/Graphics/Color.html#gray) but with a red-ish tint.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### White
```csharp
public static Color White { get; }
```

Opaque color with max red, green and blue.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### Yellow
```csharp
public static Color Yellow { get; }
```

Pure yellow (max red and green, no blue).

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
### ⭐ Methods
#### CreateFrom256(byte, byte, byte, byte)
```csharp
public Color CreateFrom256(byte r, byte g, byte b, byte a)
```

Creates a color using values from 0 to 255.

**Parameters** \
`r` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \
`g` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \
`b` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \
`a` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### CreateFrom256(byte, byte, byte)
```csharp
public Color CreateFrom256(byte r, byte g, byte b)
```

Creates a color using values from 0 to 255.

**Parameters** \
`r` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \
`g` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \
`b` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### Darken(float)
```csharp
public Color Darken(float r)
```

Multiplies all values except the alpha by the factor <paramref name="r" />.
            While this is named "Darken", values above 1.0f will effectively make the color lighter.

**Parameters** \
`r` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### FadeAlpha(float)
```csharp
public Color FadeAlpha(float factor)
```

Keeps all color values equal except for the alpha which is multiplied by <param ref="factor" />

**Parameters** \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
\

#### FadeHalfAlpha(float)
```csharp
public Color FadeHalfAlpha(float factor)
```

Fades all the colors by halft the factor, except for the alpha which is fully faded.

**Parameters** \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

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

Finds a color that is in the point <paramref name="factor" /> between <paramref name="a" /> and <paramref name="b" />.

**Parameters** \
`a` [Color](../../../Murder/Core/Graphics/Color.html) \
`b` [Color](../../../Murder/Core/Graphics/Color.html) \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### LerpSmooth(Color, Color, float, float)
```csharp
public Color LerpSmooth(Color a, Color b, float deltaTime, float halfLife)
```

**Parameters** \
`a` [Color](../../../Murder/Core/Graphics/Color.html) \
`b` [Color](../../../Murder/Core/Graphics/Color.html) \
`deltaTime` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`halfLife` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### Parse(string)
```csharp
public Color Parse(string str)
```

Tries to interpret a color from a string. Returns [Color.Magenta](../../../Murder/Core/Graphics/Color.html#magenta) in case of failure.

**Parameters** \
`str` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### Premultiply()
```csharp
public Color Premultiply()
```

Multiplies the R, G and B values of this color by the Alpha value.

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \

#### ToUint(Vector4)
```csharp
public uint ToUint(Vector4 color)
```

Interprets the Vector4 <paramref name="color" /> as a color and return the unsigned integer representation of that color.

**Parameters** \
`color` [Vector4](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector4?view=net-7.0) \

**Returns** \
[uint](https://learn.microsoft.com/en-us/dotnet/api/System.UInt32?view=net-7.0) \

#### ToSysVector4()
```csharp
public Vector4 ToSysVector4()
```

Converts this color into a [Vector4](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector4?view=net-7.0) with X = R, Y = G, Z = B and W = A.

**Returns** \
[Vector4](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector4?view=net-7.0) \

#### Equals(Color)
```csharp
public virtual bool Equals(Color other)
```

Checks if two colors are equal.

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