# DrawRectangleComponent

**Namespace:** Murder.Components \
**Assembly:** Murder.dll

```csharp
public sealed struct DrawRectangleComponent : IComponent
```

**Implements:** _[IComponent](../../Bang/Components/IComponent.html)_

### ⭐ Constructors
```csharp
public DrawRectangleComponent()
```

```csharp
public DrawRectangleComponent(int spriteBatch, bool fill, Color color, float offset)
```

**Parameters** \
`spriteBatch` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`fill` [bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
`color` [Color](../../Murder/Core/Graphics/Color.html) \
`offset` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

### ⭐ Properties
#### Color
```csharp
public readonly Color Color;
```

**Returns** \
[Color](../../Murder/Core/Graphics/Color.html) \
#### Fill
```csharp
public readonly bool Fill;
```

**Returns** \
[bool](https://learn.microsoft.com/en-us/dotnet/api/System.Boolean?view=net-7.0) \
#### LineWidth
```csharp
public readonly int LineWidth;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
#### SortingOffset
```csharp
public readonly float SortingOffset;
```

**Returns** \
[float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
#### TargetSpriteBatch
```csharp
public readonly int TargetSpriteBatch;
```

**Returns** \
[int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \


⚡