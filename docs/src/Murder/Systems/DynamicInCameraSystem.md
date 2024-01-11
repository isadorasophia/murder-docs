# DynamicInCameraSystem

**Namespace:** Murder.Systems \
**Assembly:** Murder.dll

```csharp
public class DynamicInCameraSystem : IMonoPreRenderSystem, IRenderSystem, ISystem
```

**Implements:** _[IMonoPreRenderSystem](../../Murder/Core/Graphics/IMonoPreRenderSystem.html), [IRenderSystem](../../Bang/Systems/IRenderSystem.html), [ISystem](../../Bang/Systems/ISystem.html)_

### ⭐ Constructors
```csharp
public DynamicInCameraSystem()
```

### ⭐ Methods
#### CalculateBounds(Vector2, Vector2, Point, Vector2)
```csharp
public Rectangle CalculateBounds(Vector2 position, Vector2 origin, Point size, Vector2 scale)
```

**Parameters** \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`origin` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
`size` [Point](../../Murder/Core/Geometry/Point.html) \
`scale` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

**Returns** \
[Rectangle](../../Murder/Core/Geometry/Rectangle.html) \

#### BeforeDraw(Context)
```csharp
public virtual void BeforeDraw(Context context)
```

**Parameters** \
`context` [Context](../../Bang/Contexts/Context.html) \



⚡