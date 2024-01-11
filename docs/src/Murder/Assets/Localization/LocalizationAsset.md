# LocalizationAsset

**Namespace:** Murder.Assets.Localization \
**Assembly:** Murder.dll

```csharp
public class LocalizationAsset : GameAsset
```

**Implements:** _[GameAsset](../../../Murder/Assets/GameAsset.html)_

### ⭐ Constructors
```csharp
public LocalizationAsset()
```

### ⭐ Properties
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
#### DialogueResources
```csharp
public ImmutableArray<T> DialogueResources { get; }
```

Expose all the dialogue resources (for editor, etc.).

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
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
#### Guid
```csharp
public Guid Guid { get; protected set; }
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
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
#### Name
```csharp
public string Name { get; public set; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### Rename
```csharp
public bool Rename { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Resources
```csharp
public ImmutableArray<T> Resources { get; }
```

Expose all the resources (for editor, etc.).

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
#### SaveLocation
```csharp
public virtual string SaveLocation { get; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
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
### ⭐ Methods
#### OnModified()
```csharp
protected virtual void OnModified()
```

#### HasResource(Guid)
```csharp
public bool HasResource(Guid id)
```

**Parameters** \
`id` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Duplicate(string)
```csharp
public GameAsset Duplicate(string name)
```

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[GameAsset](../../../Murder/Assets/GameAsset.html) \

#### FetchResourcesForDialogue(Guid)
```csharp
public ImmutableArray<T> FetchResourcesForDialogue(Guid guid)
```

Expose all resources tied to a particular dialogue.

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### AssetsToBeSaved()
```csharp
public List<T> AssetsToBeSaved()
```

**Returns** \
[List\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=net-7.0) \

#### AddResource(string, bool)
```csharp
public LocalizedString AddResource(string text, bool isGenerated)
```

**Parameters** \
`text` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`isGenerated` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

**Returns** \
[LocalizedString](../../../Murder/Assets/LocalizedString.html) \

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

#### TryGetResource(Guid)
```csharp
public T? TryGetResource(Guid id)
```

**Parameters** \
`id` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[T?](https://learn.microsoft.com/en-us/dotnet/api/System.Nullable-1?view=net-7.0) \

#### AfterDeserialized()
```csharp
public virtual void AfterDeserialized()
```

#### AddResource(Guid)
```csharp
public void AddResource(Guid id)
```

**Parameters** \
`id` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

#### MakeGuid()
```csharp
public void MakeGuid()
```

#### RemoveResource(Guid, bool)
```csharp
public void RemoveResource(Guid id, bool force)
```

**Parameters** \
`id` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`force` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### SetAllDialogueResources(ImmutableArray<T>)
```csharp
public void SetAllDialogueResources(ImmutableArray<T> resources)
```

**Parameters** \
`resources` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### SetResource(LocalizedStringData)
```csharp
public void SetResource(LocalizedStringData value)
```

**Parameters** \
`value` [LocalizedStringData](../../../Murder/Assets/Localization/LocalizedStringData.html) \

#### SetResourcesForDialogue(Guid, ImmutableArray<T>)
```csharp
public void SetResourcesForDialogue(Guid guid, ImmutableArray<T> resources)
```

**Parameters** \
`guid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`resources` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### TrackAssetOnSave(Guid)
```csharp
public void TrackAssetOnSave(Guid g)
```

**Parameters** \
`g` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

#### UpdateOrSetResource(Guid, string, string)
```csharp
public void UpdateOrSetResource(Guid id, string translated, string notes)
```

**Parameters** \
`id` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`translated` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`notes` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \



⚡