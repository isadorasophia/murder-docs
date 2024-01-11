# ParticleRendererSystem

**Namespace:** Murder.Systems \
**Assembly:** Murder.dll

```csharp
public class ParticleRendererSystem : IStartupSystem, ISystem, IMurderRenderSystem, IRenderSystem, IUpdateSystem
```

**Implements:** _[IStartupSystem](../../Bang/Systems/IStartupSystem.html), [ISystem](../../Bang/Systems/ISystem.html), [IMurderRenderSystem](../../Murder/Core/Graphics/IMurderRenderSystem.html), [IRenderSystem](../../Bang/Systems/IRenderSystem.html), [IUpdateSystem](../../Bang/Systems/IUpdateSystem.html)_

### ⭐ Constructors
```csharp
public ParticleRendererSystem()
```

### ⭐ Methods
#### Draw(RenderContext, Context)
```csharp
public virtual void Draw(RenderContext render, Context context)
```

**Parameters** \
`render` [RenderContext](../../Murder/Core/Graphics/RenderContext.html) \
`context` [Context](../../Bang/Contexts/Context.html) \

#### Start(Context)
```csharp
public virtual void Start(Context context)
```

**Parameters** \
`context` [Context](../../Bang/Contexts/Context.html) \

#### Update(Context)
```csharp
public virtual void Update(Context context)
```

**Parameters** \
`context` [Context](../../Bang/Contexts/Context.html) \



⚡