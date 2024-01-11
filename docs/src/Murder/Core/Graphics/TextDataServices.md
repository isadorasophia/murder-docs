# TextDataServices

**Namespace:** Murder.Core.Graphics \
**Assembly:** Murder.dll

```csharp
public static class TextDataServices
```

### ⭐ Methods
#### EscapeRegex()
```csharp
public Regex EscapeRegex()
```

**Returns** \
[Regex](https://learn.microsoft.com/en-us/dotnet/api/System.Text.RegularExpressions.Regex?view=net-7.0) \

#### GetOrCreateText(PixelFontSize, string, TextSettings)
```csharp
public RuntimeTextData GetOrCreateText(PixelFontSize font, string text, TextSettings settings)
```

**Parameters** \
`font` [PixelFontSize](../../../Murder/Core/Graphics/PixelFontSize.html) \
`text` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`settings` [TextSettings](../../../Murder/Core/Graphics/TextSettings.html) \

**Returns** \
[RuntimeTextData](../../../Murder/Core/Graphics/RuntimeTextData.html) \

#### GetOrCreateText(int, string, TextSettings)
```csharp
public RuntimeTextData GetOrCreateText(int fontId, string text, TextSettings settings)
```

**Parameters** \
`fontId` [int](https://learn.microsoft.com/en-us/dotnet/api/System.Int32?view=net-7.0) \
`text` [string](https://learn.microsoft.com/en-us/dotnet/api/System.String?view=net-7.0) \
`settings` [TextSettings](../../../Murder/Core/Graphics/TextSettings.html) \

**Returns** \
[RuntimeTextData](../../../Murder/Core/Graphics/RuntimeTextData.html) \



⚡