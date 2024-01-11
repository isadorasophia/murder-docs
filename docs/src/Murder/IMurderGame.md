# IMurderGame

**Namespace:** Murder \
**Assembly:** Murder.dll

```csharp
public abstract IMurderGame
```

This is the main loop of a murder game. This has the callbacks to relevant events in the game.

### ⭐ Properties
#### HasCursor
```csharp
public virtual bool HasCursor { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Name
```csharp
public abstract virtual string Name { get; }
```

This is the name of the game, used when creating assets and loading save data.

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Version
```csharp
public virtual float Version { get; }
```

This is the version of the game, used when checking for save compatibility.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
### ⭐ Methods
#### CreateGamePreferences()
```csharp
public virtual GamePreferences CreateGamePreferences()
```

Creates a custom game preferences for the game.

**Returns** \
[GamePreferences](../Murder/Save/GamePreferences.html) \

#### CreateGameProfile()
```csharp
public virtual GameProfile CreateGameProfile()
```

Creates a custom game profile for the game.

**Returns** \
[GameProfile](../Murder/Assets/GameProfile.html) \

#### CreateSoundPlayer()
```csharp
public virtual ISoundPlayer CreateSoundPlayer()
```

Creates the client custom sound player.

**Returns** \
[ISoundPlayer](../Murder/Core/Sounds/ISoundPlayer.html) \

#### CreateRenderContext(GraphicsDevice, Camera2D, RenderContextFlags)
```csharp
public virtual RenderContext CreateRenderContext(GraphicsDevice graphicsDevice, Camera2D camera, RenderContextFlags settings)
```

Creates a custom render context for the game.

**Parameters** \
`graphicsDevice` [GraphicsDevice](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.GraphicsDevice.html) \
`camera` [Camera2D](../Murder/Core/Graphics/Camera2D.html) \
`settings` [RenderContextFlags](../Murder/Core/Graphics/RenderContextFlags.html) \

**Returns** \
[RenderContext](../Murder/Core/Graphics/RenderContext.html) \

#### CreateSaveData(int)
```csharp
public virtual SaveData CreateSaveData(int slot)
```

Creates save data for the game.

**Parameters** \
`slot` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[SaveData](../Murder/Assets/SaveData.html) \

#### LoadContentAsync()
```csharp
public virtual Task LoadContentAsync()
```

This loads all the content within the game. Called after [IMurderGame.Initialize](../Murder/IMurderGame.html#initialize).

**Returns** \
[Task](https://learn.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task?view=net-7.0) \

#### Initialize()
```csharp
public virtual void Initialize()
```

Called once, when the executable for the game starts and initializes.

#### OnDraw()
```csharp
public virtual void OnDraw()
```

Called after each draw.

#### OnExit()
```csharp
public virtual void OnExit()
```

Called once the game exits.

#### OnLoadingDraw(RenderContext)
```csharp
public virtual void OnLoadingDraw(RenderContext context)
```

Called when a scene is unavailable due to loading of assets.
            Only assets at [GameDataManager.PreloadContent](../Murder/Data/GameDataManager.html#preloadcontent) are available.

**Parameters** \
`context` [RenderContext](../Murder/Core/Graphics/RenderContext.html) \
\

#### OnSceneTransition()
```csharp
public virtual void OnSceneTransition()
```

Called before a scene transition.

#### OnUpdate()
```csharp
public virtual void OnUpdate()
```

Called after each update.



⚡