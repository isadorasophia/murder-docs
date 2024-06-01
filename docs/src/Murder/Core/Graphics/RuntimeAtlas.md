# RuntimeAtlas

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public class RuntimeAtlas : IDisposable
```

**Implements:** _[IDisposable](https://learn.microsoft.com/en-us/dotnet/api/System.IDisposable?view=net-7.0)_

### ⭐ Constructors
```csharp
public RuntimeAtlas(string name, Point atlasSize, Point chunkSize)
```

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`atlasSize` [Point](../../../Murder/Core/Geometry/Point.html) \
`chunkSize` [Point](../../../Murder/Core/Geometry/Point.html) \

### ⭐ Properties
#### _debug
```csharp
public bool _debug;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### AllLoadedAtlas
```csharp
public readonly static List<T> AllLoadedAtlas;
```

**Returns** \
[List\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=net-7.0) \
#### Size
```csharp
public readonly Vector2 Size;
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
### ⭐ Methods
#### Begin(int)
```csharp
public Batch2D Begin(int chunkId)
```

**Parameters** \
`chunkId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \

#### Draw(int, Batch2D, Vector2, DrawInfo)
```csharp
public bool Draw(int id, Batch2D batch, Vector2 position, DrawInfo drawInfo)
```

Draws a chunk to the screen and returns if it was successful

**Parameters** \
`id` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`batch` [Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`drawInfo` [DrawInfo](../../../Murder/Core/Graphics/DrawInfo.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### PlaceChunk()
```csharp
public int PlaceChunk()
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### GetBrush()
```csharp
public RenderTarget2D GetBrush()
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \

#### GetFullAtlas()
```csharp
public RenderTarget2D GetFullAtlas()
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \

#### Dispose()
```csharp
public virtual void Dispose()
```

#### Cleanup()
```csharp
public void Cleanup()
```

#### End()
```csharp
public void End()
```

#### FreeChunk(int)
```csharp
public void FreeChunk(int chunkId)
```

**Parameters** \
`chunkId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \



⚡