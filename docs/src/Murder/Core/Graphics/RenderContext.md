# RenderContext

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public class RenderContext : IDisposable
```

**Implements:** _[IDisposable](https://learn.microsoft.com/en-us/dotnet/api/System.IDisposable?view=net-7.0)_

### ⭐ Constructors
```csharp
public RenderContext(GraphicsDevice graphicsDevice, Camera2D camera, RenderContextFlags settings)
```

A context for how to render your game. Holds everything you need to draw on the screen.
            To make your own, extend this class and add it to [Game.CreateRenderContext(Microsoft.Xna.Framework.Graphics.GraphicsDevice,Murder.Core.Graphics.Camera2D,Murder.Core.Graphics.RenderContextFlags)](../../../Murder/Game.html#createrendercontext(graphicsdevice,)
            Extending your [Batches2D](../../../Murder/Core/Graphics/Batches2D.html) file is also recommended.

**Parameters** \
`graphicsDevice` [GraphicsDevice](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.GraphicsDevice.html) \
`camera` [Camera2D](../../../Murder/Core/Graphics/Camera2D.html) \
`settings` [RenderContextFlags](../../../Murder/Core/Graphics/RenderContextFlags.html) \

### ⭐ Properties
#### _debugTarget
```csharp
protected RenderTarget2D _debugTarget;
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### _debugTargetPreview
```csharp
protected RenderTarget2D _debugTargetPreview;
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### _finalTarget
```csharp
protected RenderTarget2D _finalTarget;
```

The final screen target, has the real screen size.

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### _floorBufferTarget
```csharp
protected RenderTarget2D _floorBufferTarget;
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### _graphicsDevice
```csharp
protected GraphicsDevice _graphicsDevice;
```

**Returns** \
[GraphicsDevice](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.GraphicsDevice.html) \
#### _mainTarget
```csharp
protected RenderTarget2D _mainTarget;
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### _spriteBatches
```csharp
public Batch2D[] _spriteBatches;
```

**Returns** \
[Batch2D[]](../../../Murder/Core/Graphics/Batch2D.html) \
#### _subPixelOffset
```csharp
protected Vector2 _subPixelOffset;
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### _tempTarget
```csharp
protected RenderTarget2D _tempTarget;
```

Temporary buffer with the camera size. Used so we can apply effects
            such as limited palette and bloom on a smaller screen before applying
            it to the final target

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### _uiTarget
```csharp
protected RenderTarget2D _uiTarget;
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### _useDebugBatches
```csharp
protected readonly bool _useDebugBatches;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### BackColor
```csharp
public Color BackColor { get; }
```

**Returns** \
[Color](../../../Murder/Core/Graphics/Color.html) \
#### CachedTextTextures
```csharp
public readonly CacheDictionary<TKey, TValue> CachedTextTextures;
```

**Returns** \
[CacheDictionary\<TKey, TValue\>](../../../Murder/Utilities/CacheDictionary-2.html) \
#### Camera
```csharp
public readonly Camera2D Camera;
```

The active camera used for rendering scenes.

**Returns** \
[Camera2D](../../../Murder/Core/Graphics/Camera2D.html) \
#### CAMERA_BLEED
```csharp
public readonly static int CAMERA_BLEED;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### CAMERA_BLEED_VECTOR
```csharp
public readonly static Vector2 CAMERA_BLEED_VECTOR;
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### ColorGrade
```csharp
public Texture2D ColorGrade;
```

**Returns** \
[Texture2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.Texture2D.html) \
#### DebugBatch
```csharp
public Batch2D DebugBatch { get; }
```

Only used if [RenderContextFlags.Debug](../../../Murder/Core/Graphics/RenderContextFlags.html#debug) is set. Influenced by the camera.

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
#### DebugFxBatch
```csharp
public Batch2D DebugFxBatch { get; }
```

Only used if [RenderContextFlags.Debug](../../../Murder/Core/Graphics/RenderContextFlags.html#debug) is set, has a nice effect to it. Influenced by the camera.

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
#### FloorBatch
```csharp
public Batch2D FloorBatch { get; }
```

Renders behind the [RenderContext.GameplayBatch](../../../Murder/Core/Graphics/RenderContext.html#gameplaybatch), influenced by the camera.

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
#### GameBufferSize
```csharp
public Point GameBufferSize;
```

**Returns** \
[Point](../../../Murder/Core/Geometry/Point.html) \
#### GameplayBatch
```csharp
public Batch2D GameplayBatch { get; }
```

Intended to be the main gameplay batch, influenced by the camera.

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
#### GameUiBatch
```csharp
public Batch2D GameUiBatch { get; }
```

Renders in front of the [RenderContext.GameplayBatch](../../../Murder/Core/Graphics/RenderContext.html#gameplaybatch), influenced by the camera.

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
#### LastRenderTarget
```csharp
public RenderTarget2D LastRenderTarget { get; }
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### MainTarget
```csharp
public RenderTarget2D MainTarget { get; }
```

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
#### PreviewState
```csharp
public BatchPreviewState PreviewState;
```

**Returns** \
[BatchPreviewState](../../../Murder/Core/Graphics/BatchPreviewState.html) \
#### PreviewStretch
```csharp
public bool PreviewStretch;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### RenderToScreen
```csharp
public bool RenderToScreen;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Settings
```csharp
protected readonly RenderContextFlags Settings;
```

**Returns** \
[RenderContextFlags](../../../Murder/Core/Graphics/RenderContextFlags.html) \
#### SubPixelOffset
```csharp
public Vector2 SubPixelOffset { get; }
```

**Returns** \
[Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \
#### UiBatch
```csharp
public Batch2D UiBatch { get; }
```

Renders above everything, ignores any camera movement.

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
#### Viewport
```csharp
public Viewport Viewport;
```

**Returns** \
[Viewport](../../../Murder/Core/Viewport.html) \
### ⭐ Methods
#### SetupRenderTarget(RenderTarget2D, int, int, Color, bool)
```csharp
protected RenderTarget2D SetupRenderTarget(RenderTarget2D existingTarget, int width, int height, Color clearColor, bool preserveContents)
```

Sets up a new RenderTarget2D, disposing of the existing one if necessary.

**Parameters** \
`existingTarget` [RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
\
`width` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\
`height` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\
`clearColor` [Color](../../../Murder/Core/Graphics/Color.html) \
\
`preserveContents` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

**Returns** \
[RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
\

#### AfterMainRender(RenderTarget2D)
```csharp
protected virtual void AfterMainRender(RenderTarget2D mainTarget)
```

Called right after [RenderContext.GameUiBatch](../../../Murder/Core/Graphics/RenderContext.html#gameuibatch) end.

**Parameters** \
`mainTarget` [RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
\

#### AfterUiRender(RenderTarget2D)
```csharp
protected virtual void AfterUiRender(RenderTarget2D uiTarget)
```

Called right after the [RenderContext.UiBatch](../../../Murder/Core/Graphics/RenderContext.html#uibatch) ends.

**Parameters** \
`uiTarget` [RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
\

#### BeforeScreenRender(RenderTarget2D)
```csharp
protected virtual void BeforeScreenRender(RenderTarget2D finalTarget)
```

Last chance to render anything before the contents are drawn on the screen!

**Parameters** \
`finalTarget` [RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \
\

#### UnloadImpl()
```csharp
protected virtual void UnloadImpl()
```

Override for custom unload implementations in derived classes.

#### RegisterSpriteBatch(int, Batch2D)
```csharp
protected void RegisterSpriteBatch(int index, Batch2D batch)
```

Registers a SpriteBatch at a specified index. If the index is already taken, it will be overwritten.

**Parameters** \
`index` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
\
`batch` [Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \
\

#### TakeScreenshotIfNecessary(RenderTarget2D)
```csharp
protected void TakeScreenshotIfNecessary(RenderTarget2D target)
```

**Parameters** \
`target` [RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \

#### GetBatch(int)
```csharp
public Batch2D GetBatch(int index)
```

**Parameters** \
`index` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[Batch2D](../../../Murder/Core/Graphics/Batch2D.html) \

#### RefreshWindow(GraphicsDevice, Point, Point, ViewportResizeStyle)
```csharp
public bool RefreshWindow(GraphicsDevice graphicsDevice, Point viewportSize, Point nativeResolution, ViewportResizeStyle viewportResizeMode)
```

Refreshes the window with the new viewport size and camera scale.

**Parameters** \
`graphicsDevice` [GraphicsDevice](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.GraphicsDevice.html) \
`viewportSize` [Point](../../../Murder/Core/Geometry/Point.html) \
`nativeResolution` [Point](../../../Murder/Core/Geometry/Point.html) \
`viewportResizeMode` [ViewportResizeStyle](../../../Murder/Core/Graphics/ViewportResizeStyle.html) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
\

#### GetRenderTargetFromEnum(RenderTargets)
```csharp
public virtual Texture2D GetRenderTargetFromEnum(RenderTargets inspectingRenderTarget)
```

**Parameters** \
`inspectingRenderTarget` [RenderTargets](../../../Murder/Core/Graphics/RenderTargets.html) \

**Returns** \
[Texture2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.Texture2D.html) \

#### Begin()
```csharp
public virtual void Begin()
```

#### Dispose()
```csharp
public virtual void Dispose()
```

Disposes of all associated resources.

#### End()
```csharp
public virtual void End()
```

#### Initialize()
```csharp
public virtual void Initialize()
```

#### UpdateViewport()
```csharp
public virtual void UpdateViewport()
```

#### CreateDebugPreviewIfNecessary(BatchPreviewState, RenderTarget2D)
```csharp
public void CreateDebugPreviewIfNecessary(BatchPreviewState currentState, RenderTarget2D target)
```

**Parameters** \
`currentState` [BatchPreviewState](../../../Murder/Core/Graphics/BatchPreviewState.html) \
`target` [RenderTarget2D](https://docs.monogame.net/api/Microsoft.Xna.Framework.Graphics.RenderTarget2D.html) \

#### SaveScreenShot(Rectangle)
```csharp
public void SaveScreenShot(Rectangle cameraRect)
```

Saves a screenshot of the specified camera area.

**Parameters** \
`cameraRect` [Rectangle](../../../Murder/Core/Geometry/Rectangle.html) \
\

#### Unload()
```csharp
public void Unload()
```

Unload the render context.
            Called when the render context is no longer being actively displayed.



⚡