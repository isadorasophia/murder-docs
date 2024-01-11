# DebugServices

**Namespace:** Murder.Services \
**Assembly:** Murder.dll

```csharp
public static class DebugServices
```

### ⭐ Properties
#### DebugPreviewImage
```csharp
public static Texture2D DebugPreviewImage;
```

**Returns** \
[Texture2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.Texture2D.html) \
### ⭐ Methods
#### StopwatchStart()
```csharp
public DateTime StopwatchStart()
```

**Returns** \
[DateTime](https://learn.microsoft.com/en-us/dotnet/api/System.DateTime?view=net-7.0) \

#### StopwatchStop()
```csharp
public float StopwatchStop()
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### SaveLogAsync(string)
```csharp
public Task SaveLogAsync(string fullpath)
```

**Parameters** \
`fullpath` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### DrawLine(World, Vector2, Vector2, float, Color)
```csharp
public void DrawLine(World world, Vector2 start, Vector2 end, float duration, Color color)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`start` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`end` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`color` [Color](../../Murder/Core/Graphics/Color.html) \

#### DrawLine(World, Vector2, Vector2, float)
```csharp
public void DrawLine(World world, Vector2 start, Vector2 end, float duration)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`start` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`end` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### DrawPoint(World, Vector2, float)
```csharp
public void DrawPoint(World world, Vector2 point, float duration)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`point` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### DrawRect(World, Rectangle, float)
```csharp
public void DrawRect(World world, Rectangle rect, float duration)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`rect` [Rectangle](../../Murder/Core/Geometry/Rectangle.html) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### DrawText(World, string, Vector2, float, Color)
```csharp
public void DrawText(World world, string ev, Vector2 position, float duration, Color color)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`ev` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`color` [Color](../../Murder/Core/Graphics/Color.html) \

#### DrawText(World, string, Vector2, float)
```csharp
public void DrawText(World world, string ev, Vector2 position, float duration)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`ev` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \



⚡