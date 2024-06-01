# Calculator

**Namespace:** Murder.Utilities \
**Assembly:** Murder.dll

```csharp
public static class Calculator
```

Calculator helper class.

### ⭐ Properties
#### LayersCount
```csharp
public static int LayersCount;
```

Default layers count.
            TODO: Make this customizable.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### TO_DEG
```csharp
public static const float TO_DEG;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### TO_RAD
```csharp
public static const float TO_RAD;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
### ⭐ Methods
#### AlmostEqual(float, float)
```csharp
public bool AlmostEqual(float num1, float num2)
```

**Parameters** \
`num1` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`num2` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Blink(float, bool)
```csharp
public bool Blink(float speed, bool scaled)
```

**Parameters** \
`speed` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`scaled` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### IsInteger(float)
```csharp
public bool IsInteger(float value)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### IsInteger(Vector2)
```csharp
public bool IsInteger(Vector2 value)
```

**Parameters** \
`value` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### SameSign(float, float)
```csharp
public bool SameSign(float num1, float num2)
```

**Parameters** \
`num1` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`num2` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### SameSignOrSimilar(float, float)
```csharp
public bool SameSignOrSimilar(float num1, float num2)
```

**Parameters** \
`num1` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`num2` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### MultiplyUnsigned8Bit(byte, int)
```csharp
public byte MultiplyUnsigned8Bit(byte a, int b)
```

Returns the result of multiplying two unsigned 8-bit values.

**Parameters** \
`a` [byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \
\
`b` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\

**Returns** \
[byte](https://learn.microsoft.com/en-us/dotnet/api/System.Byte?view=net-7.0) \
\

#### LerpSnap(float, float, double, float)
```csharp
public double LerpSnap(float origin, float target, double factor, float threshold)
```

**Parameters** \
`origin` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`target` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`factor` [double](https://learn.microsoft.com/en-us/dotnet/api/System.Double?view=net-7.0) \
`threshold` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[double](https://learn.microsoft.com/en-us/dotnet/api/System.Double?view=net-7.0) \

#### Approach(float, float, float)
```csharp
public float Approach(float from, float target, float amount)
```

**Parameters** \
`from` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`target` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`amount` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### CatmullRom(float, float, float, float, float)
```csharp
public float CatmullRom(float p0, float p1, float p2, float p3, float t)
```

**Parameters** \
`p0` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`p1` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`p2` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`p3` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`t` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### Clamp01(float)
```csharp
public float Clamp01(float v)
```

**Parameters** \
`v` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### Clamp01(int)
```csharp
public float Clamp01(int v)
```

**Parameters** \
`v` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### ClampNearZero(float, float)
```csharp
public float ClampNearZero(float value, float minimum)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`minimum` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### ClampTime(float, float, float, float)
```csharp
public float ClampTime(float elapsed, float inDuration, float delayDuration, float outDuration)
```

Normalizes elapsed time to a 0-1 range based on specified durations for an 'in', 'delay', and 'out' phase. The value goes from 0 to 1 then back to 0.

**Parameters** \
`elapsed` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`inDuration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`delayDuration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`outDuration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### ClampTime(float, float, EaseKind)
```csharp
public float ClampTime(float elapsed, float maxTime, EaseKind ease)
```

Normalizes and eases elapsed time into a 0-1 range based on a maximum duration and an easing function.

**Parameters** \
`elapsed` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`maxTime` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`ease` [EaseKind](../../Murder/Utilities/EaseKind.html) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### ClampTime(float, float)
```csharp
public float ClampTime(float elapsed, float maxTime)
```

Normalizes the given elapsed time to a range of 0 to 1 based on the specified maximum time.

**Parameters** \
`elapsed` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`maxTime` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### ClampTime(float, float, float)
```csharp
public float ClampTime(float start, float now, float duration)
```

**Parameters** \
`start` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`now` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### ConvertLayerToLayerDepth(int)
```csharp
public float ConvertLayerToLayerDepth(int layer)
```

**Parameters** \
`layer` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### DeterministicFloat(int, float, float)
```csharp
public float DeterministicFloat(int seed, float min, float max)
```

**Parameters** \
`seed` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`min` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### InterpolateSmoothCurve(IList<T>, float)
```csharp
public float InterpolateSmoothCurve(IList<T> values, float t)
```

**Parameters** \
`values` [IList\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=net-7.0) \
`t` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### Lerp(float, float, float)
```csharp
public float Lerp(float origin, float target, float factor)
```

**Parameters** \
`origin` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`target` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### LerpSmooth(float, float, float, float)
```csharp
public float LerpSmooth(float a, float b, float deltaTime, float halfLife)
```

Smoothly interpolates between two float values over time using an exponential decay formula.

**Parameters** \
`a` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`b` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`deltaTime` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`halfLife` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### LerpSmoothAngle(float, float, float, float)
```csharp
public float LerpSmoothAngle(float a, float b, float deltaTime, float halfLife)
```

Smoothly interpolates between two angles over time using a linear interpolation method.

**Parameters** \
`a` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`b` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`deltaTime` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`halfLife` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### LerpSnap(float, float, float, float)
```csharp
public float LerpSnap(float origin, float target, float factor, float threshold)
```

**Parameters** \
`origin` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`target` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`threshold` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### Max(Single[])
```csharp
public float Max(Single[] values)
```

**Parameters** \
`values` [float[]](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### Min(Single[])
```csharp
public float Min(Single[] values)
```

**Parameters** \
`values` [float[]](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### NormalizeAngle(float)
```csharp
public float NormalizeAngle(float angle)
```

Normalizes the given angle to be within the range of 0 to 2π radians.

**Parameters** \
`angle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### Remap(float, float, float, float, float)
```csharp
public float Remap(float input, float inputMin, float inputMax, float min, float max)
```

**Parameters** \
`input` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`inputMin` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`inputMax` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`min` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### Remap(float, float, float)
```csharp
public float Remap(float input, float min, float max)
```

**Parameters** \
`input` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`min` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### SmoothStep(float, float, float)
```csharp
public float SmoothStep(float value, float min, float max)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`min` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### SnapAngle(float, int)
```csharp
public float SnapAngle(float finalAngle, int steps)
```

Snap the current angle into <paramref name="steps" /> degrees.

**Parameters** \
`finalAngle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`steps` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### ToSpringOscillation(float, float)
```csharp
public float ToSpringOscillation(float t, float frequency)
```

Converts a value to a spring oscillation.

**Parameters** \
`t` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`frequency` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### Wave(float, bool)
```csharp
public float Wave(float speed, bool scaled)
```

Generates a normalized sine wave value oscillating between 0 and 1.

**Parameters** \
`speed` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`scaled` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### Wave(float, float, float, bool)
```csharp
public float Wave(float speed, float min, float max, bool scaled)
```

Generates a sinusoidal wave value oscillating between a specified minimum and maximum.

**Parameters** \
`speed` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`min` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`max` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`scaled` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

#### CeilToInt(float)
```csharp
public int CeilToInt(float v)
```

**Parameters** \
`v` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### ConvertLayerDepthToLayer(float)
```csharp
public int ConvertLayerDepthToLayer(float layerDepth)
```

**Parameters** \
`layerDepth` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### DeterministicInt(int, int, int)
```csharp
public int DeterministicInt(int seed, int min, int max)
```

**Parameters** \
`seed` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`min` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`max` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### FloorToInt(float)
```csharp
public int FloorToInt(float v)
```

**Parameters** \
`v` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### LerpInt(float, float, float)
```csharp
public int LerpInt(float origin, float target, float factor)
```

**Parameters** \
`origin` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`target` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### ManhattanDistance(Point, Point)
```csharp
public int ManhattanDistance(Point point1, Point point2)
```

**Parameters** \
`point1` [Point](../../Murder/Core/Geometry/Point.html) \
`point2` [Point](../../Murder/Core/Geometry/Point.html) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### OneD(Point, int)
```csharp
public int OneD(Point p, int width)
```

**Parameters** \
`p` [Point](../../Murder/Core/Geometry/Point.html) \
`width` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### OneD(int, int, int)
```csharp
public int OneD(int x, int y, int width)
```

**Parameters** \
`x` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`y` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`width` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### PolarSnapToInt(float)
```csharp
public int PolarSnapToInt(float v)
```

**Parameters** \
`v` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### Pow(int, int)
```csharp
public int Pow(int x, int y)
```

**Parameters** \
`x` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`y` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### RoundToEven(float)
```csharp
public int RoundToEven(float v)
```

**Parameters** \
`v` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### RoundToInt(double)
```csharp
public int RoundToInt(double v)
```

**Parameters** \
`v` [double](https://learn.microsoft.com/en-us/dotnet/api/System.Double?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### RoundToInt(float)
```csharp
public int RoundToInt(float v)
```

Rounds and converts a number to integer with [MathF.Round(System.Single)](https://learn.microsoft.com/en-us/dotnet/api/System.MathF?view=net-7.0).

**Parameters** \
`v` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### WrapAround(int, Int32&, Int32&)
```csharp
public int WrapAround(int value, Int32& min, Int32& max)
```

**Parameters** \
`value` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`min` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`max` [int&](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### AddOnce(IList<T>, T)
```csharp
public T AddOnce(IList<T> list, T item)
```

**Parameters** \
`list` [IList\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=net-7.0) \
`item` [T](../../) \

**Returns** \
[T](../../) \

#### TryGet(IList<T>, int)
```csharp
public T? TryGet(IList<T> values, int index)
```

**Parameters** \
`values` [IList\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IList-1?view=net-7.0) \
`index` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

#### TryGet(ImmutableArray<T>, int)
```csharp
public T? TryGet(ImmutableArray<T> values, int index)
```

**Parameters** \
`values` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
`index` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

#### RepeatingArray(T, int)
```csharp
public T[] RepeatingArray(T value, int size)
```

**Parameters** \
`value` [T](../../) \
`size` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[T[]](../../) \

#### Spring(float, float, float, float, float, float)
```csharp
public ValueTuple<T1, T2> Spring(float value, float velocity, float targetValue, float damping, float frequency, float deltaTime)
```

**Parameters** \
`value` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`velocity` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`targetValue` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`damping` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`frequency` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`deltaTime` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[ValueTuple\<T1, T2\>](https://learn.microsoft.com/en-us/dotnet/api/System.ValueTuple-2?view=net-7.0) \

#### Approach(Vector2&, Vector2&, float)
```csharp
public Vector2 Approach(Vector2& from, Vector2& target, float amount)
```

**Parameters** \
`from` [Vector2&](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`target` [Vector2&](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`amount` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### DeterministicVector2(int, float)
```csharp
public Vector2 DeterministicVector2(int seed, float radius)
```

**Parameters** \
`seed` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`radius` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### DeterministicVector2InACircle(int, float)
```csharp
public Vector2 DeterministicVector2InACircle(int seed, float radius)
```

**Parameters** \
`seed` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`radius` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### GetPositionInSemicircle(float, Vector2, float, float, float)
```csharp
public Vector2 GetPositionInSemicircle(float ratio, Vector2 center, float radius, float startAngle, float endAngle)
```

**Parameters** \
`ratio` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`center` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`radius` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`startAngle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`endAngle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### Lerp(Vector2, Vector2, float)
```csharp
public Vector2 Lerp(Vector2 origin, Vector2 target, float factor)
```

**Parameters** \
`origin` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`target` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`factor` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### LerpSmooth(Vector2, Vector2, float, float)
```csharp
public Vector2 LerpSmooth(Vector2 a, Vector2 b, float deltaTime, float halfLife)
```

Smoothly interpolates between two vectors over time using a linear interpolation method.

**Parameters** \
`a` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
\
`b` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
\
`deltaTime` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\
`halfLife` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
\

#### Normalized(Vector2&)
```csharp
public Vector2 Normalized(Vector2& vector2)
```

**Parameters** \
`vector2` [Vector2&](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### RandomPointInCircleEdge()
```csharp
public Vector2 RandomPointInCircleEdge()
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### RandomPointInsideCircle()
```csharp
public Vector2 RandomPointInsideCircle()
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### Populate(T[], T)
```csharp
public void Populate(T[] arr, T value)
```

**Parameters** \
`arr` [T[]](../../) \
`value` [T](../../) \



⚡