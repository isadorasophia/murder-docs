# GameScene

**Namespace:** Murder.Core \
**Assembly:** Murder.dll

```csharp
public class GameScene : Scene, IDisposable
```

**Implements:** _[Scene](../../Murder/Core/Scene.html), [IDisposable](https://learn.microsoft.com/en-us/dotnet/api/System.IDisposable?view=net-7.0)_

### ⭐ Constructors
```csharp
public GameScene(Guid guid)
```

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

### ⭐ Properties
#### _calledStart
```csharp
protected bool _calledStart;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Loaded
```csharp
public bool Loaded { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### RenderContext
```csharp
public RenderContext RenderContext { get; }
```

**Returns** \
[RenderContext](../../Murder/Core/Graphics/RenderContext.html) \
#### World
```csharp
public virtual MonoWorld World { get; }
```

**Returns** \
[MonoWorld](../../Murder/Core/MonoWorld.html) \
#### WorldGuid
```csharp
public Guid WorldGuid { get; }
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
### ⭐ Methods
#### ReplaceWorld(MonoWorld, bool)
```csharp
public bool ReplaceWorld(MonoWorld world, bool disposeWorld)
```

Replace world and return the previous one, which should be disposed.

**Parameters** \
`world` [MonoWorld](../../Murder/Core/MonoWorld.html) \
`disposeWorld` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### RefreshWindow(GraphicsDevice, GameProfile)
```csharp
public virtual int RefreshWindow(GraphicsDevice graphics, GameProfile settings)
```

**Parameters** \
`graphics` [GraphicsDevice](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.GraphicsDevice.html) \
`settings` [GameProfile](../../Murder/Assets/GameProfile.html) \

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### UnloadAsyncImpl()
```csharp
public virtual Task UnloadAsyncImpl()
```

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### Dispose()
```csharp
public virtual void Dispose()
```

#### Draw()
```csharp
public virtual void Draw()
```

#### DrawGui()
```csharp
public virtual void DrawGui()
```

#### FixedUpdate()
```csharp
public virtual void FixedUpdate()
```

#### Initialize(GraphicsDevice, GameProfile, RenderContextFlags)
```csharp
public virtual void Initialize(GraphicsDevice graphics, GameProfile settings, RenderContextFlags flags)
```

**Parameters** \
`graphics` [GraphicsDevice](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.GraphicsDevice.html) \
`settings` [GameProfile](../../Murder/Assets/GameProfile.html) \
`flags` [RenderContextFlags](../../Murder/Core/Graphics/RenderContextFlags.html) \

#### LoadContentImpl()
```csharp
public virtual void LoadContentImpl()
```

#### OnBeforeDraw()
```csharp
public virtual void OnBeforeDraw()
```

#### ReloadImpl()
```csharp
public virtual void ReloadImpl()
```

#### ResumeImpl()
```csharp
public virtual void ResumeImpl()
```

#### Start()
```csharp
public virtual void Start()
```

#### SuspendImpl()
```csharp
public virtual void SuspendImpl()
```

#### Update()
```csharp
public virtual void Update()
```

#### AddOnWindowRefresh(Action)
```csharp
public void AddOnWindowRefresh(Action notification)
```

**Parameters** \
`notification` [Action](https://learn.microsoft.com/en-us/dotnet/api/System.Action?view=net-7.0) \

#### LoadContent()
```csharp
public void LoadContent()
```

#### Reload()
```csharp
public void Reload()
```

#### ResetWindowRefreshEvents()
```csharp
public void ResetWindowRefreshEvents()
```

#### Resume()
```csharp
public void Resume()
```

#### Suspend()
```csharp
public void Suspend()
```

#### Unload()
```csharp
public void Unload()
```



⚡