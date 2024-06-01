# WorldAsset

**Namespace:** Murder.Assets \
**Assembly:** Murder.dll

```csharp
public class WorldAsset : GameAsset, IWorldAsset
```

**Implements:** _[GameAsset](../../Murder/Assets/GameAsset.html), [IWorldAsset](../../Murder/Assets/IWorldAsset.html)_

### ⭐ Constructors
```csharp
public WorldAsset()
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
#### Features
```csharp
public ImmutableArray<T> Features { get; }
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
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
#### HasSystems
```csharp
public bool HasSystems { get; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### Icon
```csharp
public virtual char Icon { get; }
```

**Returns** \
[char](https://learn.microsoft.com/en-us/dotnet/api/System.Char?view=net-7.0) \
#### Instances
```csharp
public virtual ImmutableArray<T> Instances { get; }
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
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
#### Order
```csharp
public readonly int Order;
```

This is the order in which this world will be displayed in game (when selecting a lvel, etc.)

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### Rename
```csharp
public bool Rename { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
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
#### Systems
```csharp
public ImmutableArray<T> Systems { get; }
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
#### TaggedForDeletion
```csharp
public bool TaggedForDeletion;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### WorldGuid
```csharp
public virtual Guid WorldGuid { get; }
```

**Returns** \
[Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
#### WorldName
```csharp
public readonly string WorldName;
```

This is the world name used when fetching this world within the game.

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
### ⭐ Methods
#### OnModified()
```csharp
protected virtual void OnModified()
```

#### PostProcessEntities(World, Dictionary<TKey, TValue>)
```csharp
protected void PostProcessEntities(World world, Dictionary<TKey, TValue> instancesToEntities)
```

This makes any fancy post process once all entities were created in the world.
            This may trigger reactive components within the world.

**Parameters** \
`world` [World](../../Bang/World.html) \
\
`instancesToEntities` [Dictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.Dictionary-2?view=net-7.0) \
\

#### AddFilter(string)
```csharp
public bool AddFilter(string name)
```

Add a new filter to group entities.

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### AddGroup(string)
```csharp
public bool AddGroup(string name)
```

Add a new folder to group entities.

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### BelongsToAnyGroup(Guid)
```csharp
public bool BelongsToAnyGroup(Guid entity)
```

Checks whether an entity belongs to any group.

**Parameters** \
`entity` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### DeleteFilter(string)
```csharp
public bool DeleteFilter(string name)
```

Delete a new filter to group entities.

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### DeleteGroup(string)
```csharp
public bool DeleteGroup(string name)
```

Delete a new folder to group entities.

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### HasGroup(string)
```csharp
public bool HasGroup(string name)
```

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### IsOnFilter(Guid)
```csharp
public bool IsOnFilter(Guid g)
```

**Parameters** \
`g` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### MoveToGroup(string, Guid, int)
```csharp
public bool MoveToGroup(string targetGroup, Guid instance, int targetPosition)
```

**Parameters** \
`targetGroup` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`instance` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`targetPosition` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \

#### Duplicate(string)
```csharp
public GameAsset Duplicate(string name)
```

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[GameAsset](../../Murder/Assets/GameAsset.html) \

#### FetchFolderNames()
```csharp
public IEnumerable<T> FetchFolderNames()
```

This is for editor purposes, return all the available folder names as an[IEnumerable<T>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0)

**Returns** \
[IEnumerable\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.IEnumerable-1?view=net-7.0) \

#### FetchAllSystems()
```csharp
public ImmutableArray<T> FetchAllSystems()
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FetchEntitiesGuidInFilter(string)
```csharp
public ImmutableArray<T> FetchEntitiesGuidInFilter(string targetFilter)
```

**Parameters** \
`targetFilter` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FetchEntitiesOfGroup(string)
```csharp
public ImmutableArray<T> FetchEntitiesOfGroup(string name)
```

**Parameters** \
`name` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### FetchFilters()
```csharp
public ImmutableDictionary<TKey, TValue> FetchFilters()
```

This is for editor purposes, we group all entities in "folders" when visualizing them.
            This has no effect in the actual game.

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \

#### FetchFolders()
```csharp
public ImmutableDictionary<TKey, TValue> FetchFolders()
```

This is for editor purposes, we group all entities in "folders" when visualizing them.
            This has no effect in the actual game.

**Returns** \
[ImmutableDictionary\<TKey, TValue\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableDictionary-2?view=net-7.0) \

#### GroupsCount()
```csharp
public int GroupsCount()
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### AssetsToBeSaved()
```csharp
public List<T> AssetsToBeSaved()
```

**Returns** \
[List\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=net-7.0) \

#### FetchEntitiesInFilter(string)
```csharp
public List<T> FetchEntitiesInFilter(string targetFilter)
```

**Parameters** \
`targetFilter` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

**Returns** \
[List\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Generic.List-1?view=net-7.0) \

#### CreateInstance(Camera2D, ImmutableArray<T>)
```csharp
public MonoWorld CreateInstance(Camera2D camera, ImmutableArray<T> startingSystems)
```

**Parameters** \
`camera` [Camera2D](../../Murder/Core/Graphics/Camera2D.html) \
`startingSystems` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

**Returns** \
[MonoWorld](../../Murder/Core/MonoWorld.html) \

#### CreateInstanceFromSave(SavedWorld, Camera2D, ImmutableArray<T>)
```csharp
public MonoWorld CreateInstanceFromSave(SavedWorld savedInstance, Camera2D camera, ImmutableArray<T> startingSystems)
```

**Parameters** \
`savedInstance` [SavedWorld](../../Murder/Assets/SavedWorld.html) \
`camera` [Camera2D](../../Murder/Core/Graphics/Camera2D.html) \
`startingSystems` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

**Returns** \
[MonoWorld](../../Murder/Core/MonoWorld.html) \

#### GetGroupOf(Guid)
```csharp
public string GetGroupOf(Guid entity)
```

Returns the group that an entity belongs.

**Parameters** \
`entity` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \

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

#### TryGetInstance(Guid)
```csharp
public virtual EntityInstance TryGetInstance(Guid instanceGuid)
```

**Parameters** \
`instanceGuid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

**Returns** \
[EntityInstance](../../Murder/Prefabs/EntityInstance.html) \

#### AfterDeserialized()
```csharp
public virtual void AfterDeserialized()
```

#### AddInstance(EntityInstance)
```csharp
public void AddInstance(EntityInstance e)
```

**Parameters** \
`e` [EntityInstance](../../Murder/Prefabs/EntityInstance.html) \

#### MakeGuid()
```csharp
public void MakeGuid()
```

#### MoveToFilter(string, Guid, int)
```csharp
public void MoveToFilter(string targetFilter, Guid instance, int targetPosition)
```

**Parameters** \
`targetFilter` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`instance` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \
`targetPosition` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### RemoveInstance(Guid)
```csharp
public void RemoveInstance(Guid instanceGuid)
```

**Parameters** \
`instanceGuid` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

#### TrackAssetOnSave(Guid)
```csharp
public void TrackAssetOnSave(Guid g)
```

**Parameters** \
`g` [Guid](https://learn.microsoft.com/en-us/dotnet/api/System.Guid?view=net-7.0) \

#### UpdateFeatures(ImmutableArray<T>)
```csharp
public void UpdateFeatures(ImmutableArray<T> features)
```

**Parameters** \
`features` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### UpdateSystems(ImmutableArray<T>)
```csharp
public void UpdateSystems(ImmutableArray<T> systems)
```

**Parameters** \
`systems` [ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \

#### ValidateInstances()
```csharp
public void ValidateInstances()
```

Validate instances are remove any entities that no longer exist in the asset.



⚡