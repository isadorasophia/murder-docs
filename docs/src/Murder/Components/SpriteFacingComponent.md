# SpriteFacingComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct SpriteFacingComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public SpriteFacingComponent()
```

### ⭐ Properties
#### AngleStart
```csharp
public float AngleStart { get; public set; }
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### DefaultFlip
```csharp
public bool DefaultFlip { get; public set; }
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### DefaultSuffix
```csharp
public string DefaultSuffix { get; public set; }
```

**Returns** \
[string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
#### FacingInfo
```csharp
public ImmutableArray<T> FacingInfo { get; public set; }
```

**Returns** \
[ImmutableArray\<T\>](https://learn.microsoft.com/en-us/dotnet/api/System.Collections.Immutable.ImmutableArray-1?view=net-7.0) \
### ⭐ Methods
#### Resize(int, int)
```csharp
public SpriteFacingComponent Resize(int atIndex, int slices)
```

Returns a new [Murder.Components.SpriteFacingComponent.FacingInfo]() resized.
            Trims the last items if 'slices' is smaller than current length, and adds default values if larger.

**Parameters** \
`atIndex` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`slices` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

**Returns** \
[SpriteFacingComponent](../../Murder/Components/SpriteFacingComponent.html) \

#### GetSuffixFromAngle(float)
```csharp
public ValueTuple<T1, T2> GetSuffixFromAngle(float angle)
```

Gets the suffix and flip state based on a specified angle.

**Parameters** \
`angle` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
\

**Returns** \
[ValueTuple\<T1, T2\>](https://learn.microsoft.com/en-us/dotnet/api/System.ValueTuple-2?view=net-7.0) \
\



⚡