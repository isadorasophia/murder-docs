# EffectsServices

**Namespace:** Murder.Services \
**Assembly:** Murder.dll

```csharp
public static class EffectsServices
```

### ⭐ Methods
#### ApplyHighlight(World, Entity, HighlightSpriteComponent)
```csharp
public void ApplyHighlight(World world, Entity e, HighlightSpriteComponent highlight)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`e` [Entity](../../Bang/Entities/Entity.html) \
`highlight` [HighlightSpriteComponent](../../Murder/Components/HighlightSpriteComponent.html) \

#### FadeIn(World, float, Color, float)
```csharp
public void FadeIn(World world, float time, Color color, float sorting)
```

Add an entity which will apply a "fade-in" effect. Darkening the screen to black.

**Parameters** \
`world` [World](../../Bang/World.html) \
`time` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`color` [Color](../../Murder/Core/Graphics/Color.html) \
`sorting` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \

#### FadeOut(World, float, Color, float, int)
```csharp
public void FadeOut(World world, float duration, Color color, float delay, int bufferDrawFrames)
```

Add an entity which will apply a "fade-out" effect. Clearing the screen.

**Parameters** \
`world` [World](../../Bang/World.html) \
`duration` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`color` [Color](../../Murder/Core/Graphics/Color.html) \
`delay` [float](https://learn.microsoft.com/en-us/dotnet/api/System.Single?view=net-7.0) \
`bufferDrawFrames` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \

#### PlayAnimationAt(World, Portrait, Vector2)
```csharp
public void PlayAnimationAt(World world, Portrait blastAnimation, Vector2 position)
```

**Parameters** \
`world` [World](../../Bang/World.html) \
`blastAnimation` [Portrait](../../Murder/Core/Portrait.html) \
`position` [Vector2](https://learn.microsoft.com/en-us/dotnet/api/System.Numerics.Vector2?view=net-7.0) \

#### RemoveHighlight(Entity)
```csharp
public void RemoveHighlight(Entity e)
```

**Parameters** \
`e` [Entity](../../Bang/Entities/Entity.html) \



⚡