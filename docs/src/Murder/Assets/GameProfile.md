# GameProfile

**Namespace:** Murder.Assets \
**Assembly:** Murder.dll

```csharp
public class GameProfile : GameAsset
```

Represents the game profile asset containing configuration and resource paths.

**Implements:** _[GameAsset](../../Murder/Assets/GameAsset.html)_

### ⭐ Constructors
```csharp
public GameProfile()
```

### ⭐ Properties
#### Aspect
```csharp
public float Aspect { get; }
```

Gets the game's intended aspect ratio

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### AssetResourcesPath
```csharp
public readonly string AssetResourcesPath;
```

Root path where our data .json files are stored.

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### AtlasFolderName
```csharp
public readonly string AtlasFolderName;
```

Where our atlas .png and .json files are stored.
            Under: 
              packed/ -&gt; bin/resources/
                atlas/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### BackColor
```csharp
public Color BackColor;
```

Background color for the game.

**Returns** \
[Color](../../Murder/Core/Graphics/Color.html) \
#### CanBeCreated
```csharp
public virtual bool CanBeCreated { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### CanBeDeleted
```csharp
public virtual bool CanBeDeleted { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### CanBeRenamed
```csharp
public virtual bool CanBeRenamed { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### CanBeSaved
```csharp
public virtual bool CanBeSaved { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### ContentAsepritePath
```csharp
public readonly string ContentAsepritePath;
```

Where our aseprite contents are stored.
            Under:
              packed/ -&gt; bin/resources/
                aseprite/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### ContentECSPath
```csharp
public readonly string ContentECSPath;
```

Where our ecs assets are stored.
            Under:
              resources/
                assets/
                  ecs/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### DefaultGridCellSize
```csharp
public readonly int DefaultGridCellSize;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### DialoguesPath
```csharp
public readonly string DialoguesPath;
```

Where our dialogues contents are stored.
            Under:
              packed/ -&gt; bin/resources/
                dialogues/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### EditorAssets
```csharp
public readonly EditorAssets EditorAssets;
```

**Returns** \
[EditorAssets](../../Murder/Assets/EditorAssets.html) \
#### EditorColor
```csharp
public virtual Vector4 EditorColor { get; }
```

**Returns** \
[Vector4](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector4?view=net-7.0) \
#### EditorFolder
```csharp
public virtual string EditorFolder { get; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Exploration
```csharp
public readonly Exploration Exploration;
```

**Returns** \
[Exploration](../../Murder/Assets/Exploration.html) \
#### FeedbackKey
```csharp
public readonly string FeedbackKey;
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### FeedbackUrl
```csharp
public readonly string FeedbackUrl;
```

Used for reporting bugs and feedback.

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### FileChanged
```csharp
public bool FileChanged { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### FilePath
```csharp
public string FilePath { get; public set; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### FixedUpdateFactor
```csharp
public readonly float FixedUpdateFactor;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### FontPath
```csharp
public readonly string FontPath;
```

Where our font contents are stored.
            Under:
              packed/ -&gt; bin/resources/
                fonts/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### FontsPath
```csharp
public readonly string FontsPath;
```

Where our sound contents are stored.
            Under:
              packed/ -&gt; bin/resources/
                fonts/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Fullscreen
```csharp
public bool Fullscreen;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### GameHeight
```csharp
public readonly int GameHeight;
```

Game desired display height. Use [RenderContext.Camera](../../Murder/Core/Graphics/RenderContext.html#camera) size for the runtime value.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### GameScale
```csharp
public readonly float GameScale;
```

Game scaling factor.

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### GameWidth
```csharp
public readonly int GameWidth;
```

Game desired display width. Use [RenderContext.Camera](../../Murder/Core/Graphics/RenderContext.html#camera) size for the runtime value.

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### GenericAssetsPath
```csharp
public readonly string GenericAssetsPath;
```

Where our generic assets are stored.
            Under:
              resources/
                assets/
                  data/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Guid
```csharp
public Guid Guid { get; protected set; }
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### HiResPath
```csharp
public readonly string HiResPath;
```

Where our high resolution contents are stored.
            Under:
              packed/ -&gt; bin/resources
                shaders/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Icon
```csharp
public virtual char Icon { get; }
```

**Returns** \
[char](https://learn.microsoft.com/en-us/dotnet/api/System.Char?view=net-7.0) \
#### IsStoredInSaveData
```csharp
public virtual bool IsStoredInSaveData { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### IsVSyncEnabled
```csharp
public readonly bool IsVSyncEnabled;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### LocalizationPath
```csharp
public readonly string LocalizationPath;
```

Where our localization assets are stored.
            Under:
              root/resources

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### LocalizationResources
```csharp
public ImmutableDictionary<TKey, TValue> LocalizationResources;
```

Dictionary mapping languages to the appropriate localization asset resource IDs.

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \
#### MissingImage
```csharp
public readonly Guid MissingImage;
```

ID of the default image used when an image is missing.

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### Name
```csharp
public string Name { get; public set; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### PreloadTextures
```csharp
public bool PreloadTextures;
```

Whether textures (e.g. fonts) should be preloaded. If true, startup time might be slower but
            actual game will be faster.

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### PushAwayInterval
```csharp
public readonly float PushAwayInterval;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### Rename
```csharp
public bool Rename { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### ResizeStyle
```csharp
public readonly ViewportResizeStyle ResizeStyle;
```

**Returns** \
[ViewportResizeStyle](../../Murder/Core/Graphics/ViewportResizeStyle.html) \
#### SaveLocation
```csharp
public virtual string SaveLocation { get; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### ScalingFilter
```csharp
public bool ScalingFilter { get; }
```

Texture scaling smoothing

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### ShadersPath
```csharp
public readonly string ShadersPath;
```

Where our aseprite contents are stored.
            Under:
              packed/ -&gt; bin/resources/
                shaders/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### ShowUiDebug
```csharp
public readonly bool ShowUiDebug;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### SoundsPath
```csharp
public readonly string SoundsPath;
```

Where our sound contents are stored.
            Under:
              packed/ -&gt; bin/resources/
                sounds/

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### StartingScene
```csharp
public readonly Guid StartingScene;
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### StoreInDatabase
```csharp
public virtual bool StoreInDatabase { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### TaggedForDeletion
```csharp
public bool TaggedForDeletion;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### TargetFps
```csharp
public readonly int TargetFps;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Theme
```csharp
public readonly Theme Theme;
```

**Returns** \
[Theme](../../Murder/Assets/Theme.html) \
### ⭐ Methods
#### OnModified()
```csharp
protected virtual void OnModified()
```

#### Duplicate(string)
```csharp
public GameAsset Duplicate(string name)
```

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[GameAsset](../../Murder/Assets/GameAsset.html) \

#### AssetsToBeSaved()
```csharp
public List<T> AssetsToBeSaved()
```

**Returns** \
[List\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=net-7.0) \

#### GetSimplifiedName()
```csharp
public string GetSimplifiedName()
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### GetSplitNameWithEditorPath()
```csharp
public String[] GetSplitNameWithEditorPath()
```

**Returns** \
[string[]](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

#### AfterDeserialized()
```csharp
public virtual void AfterDeserialized()
```

#### MakeGuid()
```csharp
public void MakeGuid()
```

#### TrackAssetOnSave(Guid)
```csharp
public void TrackAssetOnSave(Guid g)
```

**Parameters** \
`g` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \



⚡