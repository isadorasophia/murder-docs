# FloorWithBatchOptimizationRenderSystem

**Namespace:** Murder.Systems \
**Assembly:** Murder.dll

```csharp
public class FloorWithBatchOptimizationRenderSystem : IMurderRenderSystem, IRenderSystem, ISystem, IExitSystem
```

Much, much faster than the regular Tilemap system, especially when you have many layers of tiles.
            Be careful because this WILL fail at higher resolutions!

**Implements:** _[IMurderRenderSystem](../../Murder/Core/Graphics/IMurderRenderSystem.html), [IRenderSystem](../../Bang/Systems/IRenderSystem.html), [ISystem](../../Bang/Systems/ISystem.html), [IExitSystem](../../Bang/Systems/IExitSystem.html)_

### ⭐ Constructors
```csharp
public FloorWithBatchOptimizationRenderSystem()
```

### ⭐ Methods
#### Draw(RenderContext, Context)
```csharp
public virtual void Draw(RenderContext render, Context context)
```

**Parameters** \
`render` [RenderContext](../../Murder/Core/Graphics/RenderContext.html) \
`context` [Context](../../Bang/Contexts/Context.html) \

#### Exit(Context)
```csharp
public virtual void Exit(Context context)
```

**Parameters** \
`context` [Context](../../Bang/Contexts/Context.html) \



⚡